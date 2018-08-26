---
swagger: "2.0"
x-collection-name: AWS Code Pipeline
x-complete: 0
info:
  title: AWS Code Pipeline API Put Approval Result
  version: 1.0.0
  description: Provides the response to a manual approval request to AWS CodePipeline.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListActionTypes:
    get:
      summary: List Action Types
      description: |-
        Gets a summary of all AWS CodePipeline action types associated with your
                    account.
      operationId: listActionTypes
      x-api-path-slug: actionlistactiontypes-get
      parameters:
      - in: query
        name: actionOwnerFilter
        description: Filters the list of action types to those created by a specified
          entity
        type: string
      - in: query
        name: AllocationId
        description: '[EC2-VPC] The allocation ID'
        type: string
      - in: query
        name: AllowReassociation
        description: '[EC2-VPC] For a VPC in an EC2-Classic account, specify true
          to allow an Elastic IP address that is already associated with an instance
          or network interface to be reassociated with the specified instance or network
          interface'
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: NetworkInterfaceId
        description: '[EC2-VPC] The ID of the network interface'
        type: string
      - in: query
        name: nextToken
        description: An identifier that was returned from the previous list action
          types call, which can            be used to return the next set of action
          types in the list
        type: string
      - in: query
        name: PrivateIpAddress
        description: '[EC2-VPC] The primary or secondary private IP address to associate
          with the Elastic IP address'
        type: string
      - in: query
        name: PublicIp
        description: The Elastic IP address
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Action
      - Types
  /?Action=PollForJobs:
    get:
      summary: Poll For Jobs
      description: Returns information about any jobs for AWS CodePipeline to act
        upon.
      operationId: pollForJobs
      x-api-path-slug: actionpollforjobs-get
      parameters:
      - in: query
        name: actionTypeId
        description: Represents information about an action type
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: maxBatchSize
        description: The maximum number of jobs to return in a poll for jobs call
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      - in: query
        name: PublicIp.N
        description: One or more Elastic IP addresses
        type: string
      - in: query
        name: queryParam
        description: A map of property names and values
        type: string
      responses:
        200:
          description: OK
      tags:
      - PollJobs
  /?Action=PutActionRevision:
    get:
      summary: Put Action Revision
      description: Provides information to AWS CodePipeline about new revisions to
        a source.
      operationId: putActionRevision
      x-api-path-slug: actionputactionrevision-get
      parameters:
      - in: query
        name: actionName
        description: The name of the action that will process the revision
        type: string
      - in: query
        name: actionRevision
        description: Represents information about the version (or revision) of an
          action
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: pipelineName
        description: The name of the pipeline that will start processing the revision
          to the            source
        type: string
      - in: query
        name: PublicIp
        description: The Elastic IP address
        type: string
      - in: query
        name: stageName
        description: The name of the stage that contains the action that will act
          upon the            revision
        type: string
      responses:
        200:
          description: OK
      tags:
      - Put
      - Action
      - Revision
  /?Action=PutApprovalResult:
    get:
      summary: Put Approval Result
      description: Provides the response to a manual approval request to AWS CodePipeline.
      operationId: putApprovalResult
      x-api-path-slug: actionputapprovalresult-get
      parameters:
      - in: query
        name: actionName
        description: The name of the action for which approval is requested
        type: string
      - in: query
        name: AllocationId
        description: '[EC2-VPC] The allocation ID'
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: pipelineName
        description: The name of the pipeline that contains the action
        type: string
      - in: query
        name: PublicIp
        description: '[EC2-Classic] The Elastic IP address'
        type: string
      - in: query
        name: result
        description: Represents information about the result of the approval request
        type: string
      - in: query
        name: stageName
        description: The name of the stage that contains the action
        type: string
      - in: query
        name: token
        description: The system-generated token used to identify a unique approval
          request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Put
      - Approval
      - Result
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---