---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API Update Identity Pool
  version: 1.0.0
  description: Updates a user pool.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateUserPool:
    get:
      summary: Create User Pool
      description: |-
        Creates a new Amazon Cognito user pool and sets the password policy for the
                    pool.
      operationId: createUserPool
      x-api-path-slug: actioncreateuserpool-get
      parameters:
      - in: query
        name: AdminCreateUserConfig
        description: The configuration for AdminCreateUser requests
        type: string
      - in: query
        name: AliasAttributes
        description: Attributes supported as an alias for this user pool
        type: string
      - in: query
        name: AutoVerifiedAttributes
        description: The attributes to be auto-verified
        type: string
      - in: query
        name: DeviceConfiguration
        description: The device configuration
        type: string
      - in: query
        name: EmailConfiguration
        description: The email configuration
        type: string
      - in: query
        name: EmailVerificationMessage
        description: A string representing the email verification message
        type: string
      - in: query
        name: EmailVerificationSubject
        description: A string representing the email verification subject
        type: string
      - in: query
        name: LambdaConfig
        description: The Lambda trigger configuration information for the new user
          pool
        type: string
      - in: query
        name: MfaConfiguration
        description: Specifies MFA configuration details
        type: string
      - in: query
        name: Policies
        description: The policies associated with the new user pool
        type: string
      - in: query
        name: PoolName
        description: A string used to name the user pool
        type: string
      - in: query
        name: Schema
        description: An array of schema attributes for the new user pool
        type: string
      - in: query
        name: SmsAuthenticationMessage
        description: A string representing the SMS authentication message
        type: string
      - in: query
        name: SmsConfiguration
        description: The SMS configuration
        type: string
      - in: query
        name: SmsVerificationMessage
        description: A string representing the SMS verification message
        type: string
      - in: query
        name: UserPoolTags
        description: The cost allocation tags for the user pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pools
  /?Action=DeleteUserPool:
    get:
      summary: Delete User Pool
      description: Deletes the specified Amazon Cognito user pool.
      operationId: deleteUserPool
      x-api-path-slug: actiondeleteuserpool-get
      parameters:
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pools
  /?Action=DeleteUserPoolClient:
    get:
      summary: Delete User Pool Client
      description: Allows the developer to delete the user pool client.
      operationId: deleteUserPoolClient
      x-api-path-slug: actiondeleteuserpoolclient-get
      parameters:
      - in: query
        name: ClientId
        description: The ID of the client associated with the user pool
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to delete the
          client
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pools
  /?Action=DescribeUserPool:
    get:
      summary: Describe User Pool
      description: |-
        Returns the configuration information and metadata of the specified user
                    pool.
      operationId: describeUserPool
      x-api-path-slug: actiondescribeuserpool-get
      parameters:
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pools
  /?Action=GetDevice:
    get:
      summary: Get Device
      description: Gets the device.
      operationId: getDevice
      x-api-path-slug: actiongetdevice-get
      parameters:
      - in: query
        name: AccessToken
        description: The access token
        type: string
      - in: query
        name: DeviceKey
        description: The device key
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pools
  /?Action=UpdateUserPool:
    get:
      summary: Update User Pool
      description: Updates the specified user pool with the specified attributes.
      operationId: updateUserPool
      x-api-path-slug: actionupdateuserpool-get
      parameters:
      - in: query
        name: AdminCreateUserConfig
        description: The configuration for AdminCreateUser requests
        type: string
      - in: query
        name: AutoVerifiedAttributes
        description: The attributes that are automatically verified when the Amazon
          Cognito service            makes a request to update user pools
        type: string
      - in: query
        name: DeviceConfiguration
        description: Device configuration
        type: string
      - in: query
        name: EmailConfiguration
        description: Email configuration
        type: string
      - in: query
        name: EmailVerificationMessage
        description: The contents of the email verification message
        type: string
      - in: query
        name: EmailVerificationSubject
        description: The subject of the email verification message
        type: string
      - in: query
        name: LambdaConfig
        description: The AWS Lambda configuration information from the request to
          update the user            pool
        type: string
      - in: query
        name: MfaConfiguration
        description: 'Can be one of the following values:'
        type: string
      - in: query
        name: Policies
        description: A container with the policies you wish to update in a user pool
        type: string
      - in: query
        name: SmsAuthenticationMessage
        description: The contents of the SMS authentication message
        type: string
      - in: query
        name: SmsConfiguration
        description: SMS configuration
        type: string
      - in: query
        name: SmsVerificationMessage
        description: A container with information about the SMS verification message
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool you want to update
        type: string
      - in: query
        name: UserPoolTags
        description: The cost allocation tags for the user pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pools
  /?Action=CreateUserPoolClient:
    get:
      summary: Create User Pool Client
      description: Creates the user pool client.
      operationId: createUserPoolClient
      x-api-path-slug: actioncreateuserpoolclient-get
      parameters:
      - in: query
        name: ClientName
        description: The client name for the user pool client you would like to create
        type: string
      - in: query
        name: ExplicitAuthFlows
        description: The explicit authentication flows
        type: string
      - in: query
        name: GenerateSecret
        description: Boolean to specify whether you want to generate a secret for
          the user pool client            being created
        type: string
      - in: query
        name: ReadAttributes
        description: The read attributes
        type: string
      - in: query
        name: RefreshTokenValidity
        description: The validity of the refresh token, in days
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to create a
          user pool            client
        type: string
      - in: query
        name: WriteAttributes
        description: The write attributes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pool Clients
  /?Action=DescribeUserPoolClient:
    get:
      summary: Describe User Pool Client
      description: |-
        Client method for returning the configuration information and metadata of the
                    specified user pool client.
      operationId: describeUserPoolClient
      x-api-path-slug: actiondescribeuserpoolclient-get
      parameters:
      - in: query
        name: ClientId
        description: The ID of the client associated with the user pool
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pool Clients
  /?Action=UpdateUserPoolClient:
    get:
      summary: Update User Pool Client
      description: |-
        Allows the developer to update the specified user pool client and password
                    policy.
      operationId: updateUserPoolClient
      x-api-path-slug: actionupdateuserpoolclient-get
      parameters:
      - in: query
        name: ClientId
        description: The ID of the client associated with the user pool
        type: string
      - in: query
        name: ClientName
        description: The client name from the update user pool client request
        type: string
      - in: query
        name: ExplicitAuthFlows
        description: Explicit authentication flows
        type: string
      - in: query
        name: ReadAttributes
        description: The read-only attributes of the user pool
        type: string
      - in: query
        name: RefreshTokenValidity
        description: The validity of the refresh token, in days
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to update the
          user pool            client
        type: string
      - in: query
        name: WriteAttributes
        description: The writeable attributes of the user pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
      - Pool Clients
  /?Action=ListIdentityPools:
    get:
      summary: List Identity Pools
      description: Lists all of the Cognito identity pools registered for your account.
      operationId: listIdentityPools
      x-api-path-slug: actionlistidentitypools-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of identities to return
        type: string
      - in: query
        name: NextToken
        description: A pagination token
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=ListUserPools:
    get:
      summary: List User Pools
      description: Lists the user pools associated with an AWS account.
      operationId: listUserPools
      x-api-path-slug: actionlistuserpools-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of results you want the request to return
          when listing the user            pools
        type: string
      - in: query
        name: NextToken
        description: An identifier that was returned from the previous call to this
          operation, which can            be used to return the next set of items
          in the list
        type: string
      responses:
        200:
          description: OK
      tags:
      - user Pools
  /?Action=BulkPublish:
    get:
      summary: Bulk Publish
      description: Initiates a bulk publish of all existing datasets for an Identity
        Pool to the configured stream.
      operationId: bulkPublish
      x-api-path-slug: actionbulkpublish-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Publish
  /?Action=CreateIdentityPool:
    get:
      summary: Create Identity Pool
      description: Creates a new identity pool.
      operationId: createIdentityPool
      x-api-path-slug: actioncreateidentitypool-get
      parameters:
      - in: query
        name: AllowUnauthenticatedIdentities
        description: TRUE if the identity pool supports unauthenticated logins
        type: string
      - in: query
        name: CognitoIdentityProviders
        description: An array of Amazon Cognito Identity user pools and their client
          IDs
        type: string
      - in: query
        name: DeveloperProviderName
        description: The domain by which Cognito will refer to your users
        type: string
      - in: query
        name: IdentityPoolName
        description: A string that you provide
        type: string
      - in: query
        name: OpenIdConnectProviderARNs
        description: A list of OpendID Connect provider ARNs
        type: string
      - in: query
        name: SamlProviderARNs
        description: An array of Amazon Resource Names (ARNs) of the SAML provider
          for your identity         pool
        type: string
      - in: query
        name: SupportedLoginProviders
        description: Optional key:value pairs mapping provider names to provider app
          IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=DeleteIdentityPool:
    get:
      summary: Delete Identity Pool
      description: Deletes a user pool.
      operationId: deleteIdentityPool
      x-api-path-slug: actiondeleteidentitypool-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=DescribeIdentityPool:
    get:
      summary: Describe Identity Pool
      description: |-
        Gets details about a particular identity pool, including the pool name, ID
                 description, creation date, and current number of users.
      operationId: describeIdentityPool
      x-api-path-slug: actiondescribeidentitypool-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=DescribeIdentityPoolUsage:
    get:
      summary: Describe Identity Pool Usage
      description: Gets usage details (for example, data storage) about a particular
        identity pool.
      operationId: describeIdentityPoolUsage
      x-api-path-slug: actiondescribeidentitypoolusage-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)       created
          by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool Usage
  /?Action=GetIdentityPoolConfiguration:
    get:
      summary: Get Identity Pool Configuration
      description: Gets the configuration settings of an identity pool.
      operationId: getIdentityPoolConfiguration
      x-api-path-slug: actiongetidentitypoolconfiguration-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pools
  /?Action=GetIdentityPoolRoles:
    get:
      summary: Get Identity Pool Roles
      description: Gets the roles for an identity pool.
      operationId: getIdentityPoolRoles
      x-api-path-slug: actiongetidentitypoolroles-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool Roles
  /?Action=ListIdentityPoolUsage:
    get:
      summary: List Identity Pool Usage
      description: Gets a list of identity pools registered with Cognito.
      operationId: listIdentityPoolUsage
      x-api-path-slug: actionlistidentitypoolusage-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of results to be returned
        type: string
      - in: query
        name: NextToken
        description: A pagination token for obtaining the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pools
  /?Action=ListUserPoolClients:
    get:
      summary: List User Pool Clients
      description: Lists the clients that have been created for the specified user
        pool.
      operationId: listUserPoolClients
      x-api-path-slug: actionlistuserpoolclients-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of results you want the request to return
          when listing the user            pool clients
        type: string
      - in: query
        name: NextToken
        description: An identifier that was returned from the previous call to this
          operation, which can            be used to return the next set of items
          in the list
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to list user
          pool            clients
        type: string
      responses:
        200:
          description: OK
      tags:
      - user Pool Clients
  /?Action=SetIdentityPoolConfiguration:
    get:
      summary: Set Identity Pool Configuration
      description: Sets the necessary configuration for push sync.
      operationId: setIdentityPoolConfiguration
      x-api-path-slug: actionsetidentitypoolconfiguration-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pools
  /?Action=SetIdentityPoolRoles:
    get:
      summary: Set Identity Pool Roles
      description: Sets the roles for an identity pool.
      operationId: setIdentityPoolRoles
      x-api-path-slug: actionsetidentitypoolroles-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      - in: query
        name: RoleMappings
        description: How users for a specific identity provider are to mapped to roles
        type: string
      - in: query
        name: Roles
        description: The map of roles associated with this pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=UpdateIdentityPool:
    get:
      summary: Update Identity Pool
      description: Updates a user pool.
      operationId: updateIdentityPool
      x-api-path-slug: actionupdateidentitypool-get
      parameters:
      - in: query
        name: AllowUnauthenticatedIdentities
        description: TRUE if the identity pool supports unauthenticated logins
        type: string
      - in: query
        name: CognitoIdentityProviders
        description: A list representing an Amazon Cognito Identity User Pool and
          its client ID
        type: string
      - in: query
        name: DeveloperProviderName
        description: The domain by which Cognito will refer to your users
        type: string
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      - in: query
        name: IdentityPoolName
        description: A string that you provide
        type: string
      - in: query
        name: OpenIdConnectProviderARNs
        description: A list of OpendID Connect provider ARNs
        type: string
      - in: query
        name: SamlProviderARNs
        description: An array of Amazon Resource Names (ARNs) of the SAML provider
          for your identity         pool
        type: string
      - in: query
        name: SupportedLoginProviders
        description: Optional key:value pairs mapping provider names to provider app
          IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
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