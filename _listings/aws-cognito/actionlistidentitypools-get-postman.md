{
  "info": {
    "name": "AWS Cognito API List Identity Pools",
    "_postman_id": "8ce7ede8-db06-4852-9376-2a1a669020d3",
    "description": "Lists all of the Cognito identity pools registered for your account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Attributes",
      "item": [
        {
          "id": "f58ccdb2-fef5-4bd4-b5d7-eba73e1bdcec",
          "name": "addCustomAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AddCustomAttributes?CustomAttributes=CustomAttributes&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds additional user attributes to the user pool schema."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd335a51-bd72-40c0-be05-ec8e835e2998"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "bb3ce1a5-dc33-481b-a8ae-7ffaa9c50521",
          "name": "adminAddUserToGroup",
          "request": {
            "url": "http://example.com/api/?Action=AdminAddUserToGroup?GroupName=GroupName&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified user to the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e49701c-92ab-41f1-9aa4-1a4e436338a3"
            }
          ]
        },
        {
          "id": "9be8e9a1-396b-40f3-8b97-8ba3e02e6d26",
          "name": "adminCreateUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminCreateUser?DesiredDeliveryMediums=DesiredDeliveryMediums&ForceAliasCreation=ForceAliasCreation&MessageAction=MessageAction&TemporaryPassword=TemporaryPassword&UserAttributes=UserAttributes&Username=Username&UserPoolId=UserPoolId&ValidationData=ValidationData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new user in the specified user pool and sends a welcome message via email\n            or phone (SMS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "566ec2c5-f0c6-4c07-a341-d2b00483f5b5"
            }
          ]
        },
        {
          "id": "1a9da164-f06a-4a42-b34d-9a118b90d747",
          "name": "adminDeleteUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminDeleteUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f18e8c3e-0ce1-44e9-8ad7-2fad3838fb6c"
            }
          ]
        },
        {
          "id": "bc1dc030-f93d-41c2-b493-88f1e1e65f7f",
          "name": "adminDeleteUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AdminDeleteUserAttributes?UserAttributeNames=UserAttributeNames&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the user attributes in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "969eabc8-7552-43d1-9618-58c1687ec0e1"
            }
          ]
        },
        {
          "id": "a6574b30-f7cf-4306-96b2-4926285fc87d",
          "name": "adminDisableUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminDisableUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables the specified user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8198ba30-66b6-4d91-bf92-dfc8c64ff37a"
            }
          ]
        },
        {
          "id": "13ee3dc5-fdf8-44de-b88b-1ac35bb8f8ff",
          "name": "adminEnableUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminEnableUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89304560-c3fa-4ce6-b953-a402fad834b6"
            }
          ]
        },
        {
          "id": "f58b283a-937e-470d-9762-4156e980cf13",
          "name": "adminGetUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminGetUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the specified user by user name in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6cdd251b-92f1-4f88-b820-e8d8a098e5c6"
            }
          ]
        },
        {
          "id": "ff2cf3d7-9295-4bae-9e4b-278484a52ef7",
          "name": "adminListGroupsForUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminListGroupsForUser?Limit=Limit&NextToken=NextToken&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the groups that the user belongs to."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6c8848da-b3fa-4543-8248-6503ea9fc7d7"
            }
          ]
        },
        {
          "id": "d672f792-c5d5-48dd-bb7f-a8d54534ff9d",
          "name": "adminRemoveUserFromGroup",
          "request": {
            "url": "http://example.com/api/?Action=AdminRemoveUserFromGroup?GroupName=GroupName&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified user from the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4531580c-0bf6-44e8-9965-365b074ea26b"
            }
          ]
        },
        {
          "id": "a9ed9839-fd25-4a88-95c0-19e0fb167692",
          "name": "adminResetUserPassword",
          "request": {
            "url": "http://example.com/api/?Action=AdminResetUserPassword?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the specified user's password in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b3d1704-5669-4a22-a5f3-b958fbe498a0"
            }
          ]
        },
        {
          "id": "589ad0de-2a8c-49d2-95ba-0340d9422d51",
          "name": "adminSetUserSettings",
          "request": {
            "url": "http://example.com/api/?Action=AdminSetUserSettings?MFAOptions=MFAOptions&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets all the user settings for a specified user name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "325cbf48-6da4-4cb7-9faf-bf005a2b757d"
            }
          ]
        },
        {
          "id": "95f0626a-2744-479d-b2e0-ac9d6df1ff9f",
          "name": "adminUpdateDeviceStatus",
          "request": {
            "url": "http://example.com/api/?Action=AdminUpdateDeviceStatus?DeviceKey=DeviceKey&DeviceRememberedStatus=DeviceRememberedStatus&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the device status as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab3fc4d1-e947-4315-ad9c-4d119b653337"
            }
          ]
        },
        {
          "id": "b9b634ca-a5bf-4791-ab60-0b845c751764",
          "name": "adminUpdateUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AdminUpdateUserAttributes?UserAttributes=UserAttributes&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified user's attributes, including developer attributes, as an\n            administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e636af4-f673-4e0d-bb13-26bf3adc9fd0"
            }
          ]
        },
        {
          "id": "d1f2b0ba-b0a1-4dfa-b144-f0b9be92a459",
          "name": "adminUserGlobalSignOut",
          "request": {
            "url": "http://example.com/api/?Action=AdminUserGlobalSignOut?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Signs out users from all devices, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "432ed624-d242-4c1d-8a54-3cd383ce3ea9"
            }
          ]
        },
        {
          "id": "e827ba92-154d-4589-8f66-e0c022aa1c9d",
          "name": "createUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserImportJob?CloudWatchLogsRoleArn=CloudWatchLogsRoleArn&JobName=JobName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41f7ffa0-6e7e-4a55-b85b-e66643951ba9"
            }
          ]
        },
        {
          "id": "e4167a58-df3c-4b56-ab25-4eb10001ad2e",
          "name": "createUserPool",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserPool?AdminCreateUserConfig=AdminCreateUserConfig&AliasAttributes=AliasAttributes&AutoVerifiedAttributes=AutoVerifiedAttributes&DeviceConfiguration=DeviceConfiguration&EmailConfiguration=EmailConfiguration&EmailVerificationMessage=EmailVerificationMessage&EmailVerificationSubject=EmailVerificationSubject&LambdaConfig=LambdaConfig&MfaConfiguration=MfaConfiguration&Policies=Policies&PoolName=PoolName&Schema=Schema&SmsAuthenticationMessage=SmsAuthenticationMessage&SmsConfiguration=SmsConfiguration&SmsVerificationMessage=SmsVerificationMessage&UserPoolTags=UserPoolTags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new Amazon Cognito user pool and sets the password policy for the\n            pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7421535c-dc41-493e-8a68-0b4e93009a31"
            }
          ]
        },
        {
          "id": "58a85004-da41-4f51-a8f5-62e7880a279a",
          "name": "createUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserPoolClient?ClientName=ClientName&ExplicitAuthFlows=ExplicitAuthFlows&GenerateSecret=GenerateSecret&ReadAttributes=ReadAttributes&RefreshTokenValidity=RefreshTokenValidity&UserPoolId=UserPoolId&WriteAttributes=WriteAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates the user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5443a8fa-3f8a-4700-b3c4-50f0664da53b"
            }
          ]
        },
        {
          "id": "33022f71-5fa8-43cc-ae7f-3cba3c18d468",
          "name": "deleteUser",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUser?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to delete one's self."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "021e5532-e4c8-414e-8390-d82694c23b0d"
            }
          ]
        },
        {
          "id": "52352cf5-c955-46f9-bd11-2712578cae6e",
          "name": "deleteUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserAttributes?AccessToken=AccessToken&UserAttributeNames=UserAttributeNames",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the attributes for a user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb72525e-74c1-47c0-a46b-e0ec61c79061"
            }
          ]
        },
        {
          "id": "3d7d1fec-f0db-4123-9bd2-b5fd687960b4",
          "name": "deleteUserPool",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPool?UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Amazon Cognito user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72e77ea7-9805-4fab-b761-274c324595b7"
            }
          ]
        },
        {
          "id": "1dd91fd1-2d22-4c45-a8d7-14b40ae077d7",
          "name": "deleteUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPoolClient?ClientId=ClientId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows the developer to delete the user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "343cd7f3-8b0f-4fb9-ba84-35477a0d7c10"
            }
          ]
        },
        {
          "id": "3155096b-f834-4685-bd8c-d2033ee4a94e",
          "name": "describeUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserImportJob?JobId=JobId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d65bca7-e63c-4588-9175-16597a50cf35"
            }
          ]
        },
        {
          "id": "491afdee-0947-4846-b856-711ee29aca6f",
          "name": "describeUserPool",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserPool?UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the configuration information and metadata of the specified user\n            pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eff23e64-32f4-4618-9160-56100fb6ffea"
            }
          ]
        },
        {
          "id": "aae816b2-4b2c-4383-a793-0294fb9465c0",
          "name": "describeUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserPoolClient?ClientId=ClientId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Client method for returning the configuration information and metadata of the\n            specified user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5ca7467-ec69-46c9-8fb8-7f5566c49521"
            }
          ]
        },
        {
          "id": "3a7f53a5-b956-411e-8008-a1ec96fe75da",
          "name": "getDevice",
          "request": {
            "url": "http://example.com/api/?Action=GetDevice?AccessToken=AccessToken&DeviceKey=DeviceKey",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6df2ff8-7b55-4078-a3fc-67b1501183c2"
            }
          ]
        },
        {
          "id": "33e7006a-1ff4-4bec-b434-b8ef425186cc",
          "name": "getUser",
          "request": {
            "url": "http://example.com/api/?Action=GetUser?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the user attributes and metadata for a user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e484156f-9f2f-4f59-b001-cecb8130a848"
            }
          ]
        },
        {
          "id": "726bc181-d749-442f-8c9d-9a6205f4a6d0",
          "name": "listUserImportJobs",
          "request": {
            "url": "http://example.com/api/?Action=ListUserImportJobs?MaxResults=MaxResults&PaginationToken=PaginationToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the user import jobs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85be23bb-126f-4438-86b0-4e97d61c203e"
            }
          ]
        },
        {
          "id": "e8b90d35-4882-40a6-b4d6-5a9908fd5281",
          "name": "listUsers",
          "request": {
            "url": "http://example.com/api/?Action=ListUsers?AttributesToGet=AttributesToGet&Filter=Filter&Limit=Limit&PaginationToken=PaginationToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the users in the Amazon Cognito user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "193e58c6-badf-4977-9080-9095061d96a6"
            }
          ]
        },
        {
          "id": "c71c306e-60f6-45be-a904-85bf7a3c578b",
          "name": "listUsersInGroup",
          "request": {
            "url": "http://example.com/api/?Action=ListUsersInGroup?GroupName=GroupName&Limit=Limit&NextToken=NextToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the users in the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "782a1a73-515c-493b-8ed9-1a5aad3ce65d"
            }
          ]
        },
        {
          "id": "88f02ce3-75ea-4d54-ac21-7b906fb04a49",
          "name": "setUserSettings",
          "request": {
            "url": "http://example.com/api/?Action=SetUserSettings?AccessToken=AccessToken&MFAOptions=MFAOptions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the user settings like multi-factor authentication (MFA)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3dd7bcff-b189-4621-8173-2af2fa4d97bb"
            }
          ]
        },
        {
          "id": "9b427348-065c-4036-b2c5-7b32b25cbdec",
          "name": "startUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=StartUserImportJob?JobId=JobId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts the user import."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "537d9df2-887d-429c-9fe1-ba46066724f6"
            }
          ]
        },
        {
          "id": "abcc6b94-7349-4da5-ad18-5329d5da8007",
          "name": "stopUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=StopUserImportJob?JobId=JobId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Stops the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69970a6e-ac11-47a0-87fe-4227e0ea94d6"
            }
          ]
        },
        {
          "id": "aafb159a-1327-46c1-a7e0-7b41034ebddd",
          "name": "updateUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=UpdateUserAttributes?AccessToken=AccessToken&UserAttributes=UserAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to update a specific attribute (one at a time)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa7bf0c0-7148-42c3-afe5-35f654193174"
            }
          ]
        },
        {
          "id": "0d94952b-3908-40ef-ba06-29979bfcf8a9",
          "name": "updateUserPool",
          "request": {
            "url": "http://example.com/api/?Action=UpdateUserPool?AdminCreateUserConfig=AdminCreateUserConfig&AutoVerifiedAttributes=AutoVerifiedAttributes&DeviceConfiguration=DeviceConfiguration&EmailConfiguration=EmailConfiguration&EmailVerificationMessage=EmailVerificationMessage&EmailVerificationSubject=EmailVerificationSubject&LambdaConfig=LambdaConfig&MfaConfiguration=MfaConfiguration&Policies=Policies&SmsAuthenticationMessage=SmsAuthenticationMessage&SmsConfiguration=SmsConfiguration&SmsVerificationMessage=SmsVerificationMessage&UserPoolId=UserPoolId&UserPoolTags=UserPoolTags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified user pool with the specified attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4dcdf85-f972-4ae4-8c5f-f44f39a2e5a5"
            }
          ]
        },
        {
          "id": "17d03091-4096-418f-a7b9-57bf6be44117",
          "name": "updateUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=UpdateUserPoolClient?ClientId=ClientId&ClientName=ClientName&ExplicitAuthFlows=ExplicitAuthFlows&ReadAttributes=ReadAttributes&RefreshTokenValidity=RefreshTokenValidity&UserPoolId=UserPoolId&WriteAttributes=WriteAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows the developer to update the specified user pool client and password\n            policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a259baa7-1522-44f1-af9d-789e194cf7c0"
            }
          ]
        },
        {
          "id": "4a617138-ec7c-4390-8132-6bc0fd74eac9",
          "name": "verifyUserAttribute",
          "request": {
            "url": "http://example.com/api/?Action=VerifyUserAttribute?AccessToken=AccessToken&AttributeName=AttributeName&Code=Code",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Verifies the specified user attributes in the user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6e83ebd-eeba-44e5-8dc6-72d78d4f2d6f"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Up",
      "item": [
        {
          "id": "a4858c73-608d-49f9-af44-65cbfb935251",
          "name": "adminConfirmSignUp",
          "request": {
            "url": "http://example.com/api/?Action=AdminConfirmSignUp?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms user registration as an admin without using a confirmation code."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "956bec72-56bf-4ae3-9b01-64eac3b1a439"
            }
          ]
        },
        {
          "id": "609ff9f8-e312-4d26-b32a-8ec0e1d64392",
          "name": "signUp",
          "request": {
            "url": "http://example.com/api/?Action=SignUp?ClientId=ClientId&Password=Password&SecretHash=SecretHash&UserAttributes=UserAttributes&Username=Username&ValidationData=ValidationData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers the user in the specified user pool and creates a user name, password,\n            and user attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb898fc5-d361-41b4-80e3-b14905ada857"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "346eaa41-d71b-402d-994c-3dd8af75f6a4",
          "name": "adminForgetDevice",
          "request": {
            "url": "http://example.com/api/?Action=AdminForgetDevice?DeviceKey=DeviceKey&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Forgets the device, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc2b3bbc-ffe4-4ec4-9999-054ba2a4bb76"
            }
          ]
        },
        {
          "id": "17b93bf7-bd94-4431-8c98-b39e83afd3d2",
          "name": "confirmDevice",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmDevice?AccessToken=AccessToken&DeviceKey=DeviceKey&DeviceName=DeviceName&DeviceSecretVerifierConfig=DeviceSecretVerifierConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms tracking of the device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d7426d0-0090-4198-8a87-191f3ffb9060"
            }
          ]
        },
        {
          "id": "227da86a-e469-4bbe-bc66-f124cfd40f59",
          "name": "forgetDevice",
          "request": {
            "url": "http://example.com/api/?Action=ForgetDevice?AccessToken=AccessToken&DeviceKey=DeviceKey",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Forgets the specified device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8cfc1e34-aec1-4bf9-9916-cc779ee35113"
            }
          ]
        },
        {
          "id": "3ea7a473-e251-4183-a46f-8ab9248b3da0",
          "name": "listDevices",
          "request": {
            "url": "http://example.com/api/?Action=ListDevices?AccessToken=AccessToken&Limit=Limit&PaginationToken=PaginationToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the devices."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85c20972-199b-4908-aad0-68a26c822451"
            }
          ]
        },
        {
          "id": "328351ae-843a-4f89-9dcc-e036f9d28fdc",
          "name": "updateDeviceStatus",
          "request": {
            "url": "http://example.com/api/?Action=UpdateDeviceStatus?AccessToken=AccessToken&DeviceKey=DeviceKey&DeviceRememberedStatus=DeviceRememberedStatus",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the device status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c86cedd5-fa56-45fc-b426-67ad4bbe179d"
            }
          ]
        }
      ]
    },
    {
      "name": "http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php",
      "item": [
        {
          "id": "16b8bf94-4fad-4466-b195-c578d7bff568",
          "name": "adminGetDevice",
          "request": {
            "url": "http://example.com/api/?Action=AdminGetDevice?DeviceKey=DeviceKey&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the device, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "125105a3-9497-4058-96e9-34a479d9e1d7"
            }
          ]
        },
        {
          "id": "85d30b15-3d2f-42ef-a578-ca39ccf23f45",
          "name": "adminListDevices",
          "request": {
            "url": "http://example.com/api/?Action=AdminListDevices?Limit=Limit&PaginationToken=PaginationToken&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists devices, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97f64974-3423-41eb-8a8f-a9714123d255"
            }
          ]
        }
      ]
    },
    {
      "name": "Authnetication",
      "item": [
        {
          "id": "815b5980-c4b3-4d9a-8ed0-12c2cbd1a4bc",
          "name": "adminInitiateAuth",
          "request": {
            "url": "http://example.com/api/?Action=AdminInitiateAuth?AuthFlow=AuthFlow&AuthParameters=AuthParameters&ClientId=ClientId&ClientMetadata=ClientMetadata&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the authentication flow, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "887594c1-1b69-40d3-a1f5-9187f4ae81d1"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenge",
      "item": [
        {
          "id": "7490c9cc-8136-4b69-9f0f-5fba2460cd66",
          "name": "adminRespondToAuthChallenge",
          "request": {
            "url": "http://example.com/api/?Action=AdminRespondToAuthChallenge?ChallengeName=ChallengeName&ChallengeResponses=ChallengeResponses&ClientId=ClientId&Session=Session&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Responds to an authentication challenge, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fdd13d8e-456c-4d41-857a-4f375da8cf57"
            }
          ]
        }
      ]
    },
    {
      "name": "Password",
      "item": [
        {
          "id": "60b3e8d9-059a-45e3-8f68-173efe2289ca",
          "name": "changePassword",
          "request": {
            "url": "http://example.com/api/?Action=ChangePassword?AccessToken=AccessToken&PreviousPassword=PreviousPassword&ProposedPassword=ProposedPassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the password for a specified user in a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8ae1070-63c8-4386-b270-5f24fa62107d"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "acc18bcd-5e70-4fdf-aeb2-4e98cbc3ba95",
          "name": "confirmForgotPassword",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmForgotPassword?ClientId=ClientId&ConfirmationCode=ConfirmationCode&Password=Password&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to enter a code provided when they reset their password to update\n            their password."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6fd229e1-b0f1-4cfe-910b-b86f3ebe3acc"
            }
          ]
        },
        {
          "id": "4ff813f3-4863-44f6-ad7f-02dd1e5d432d",
          "name": "forgotPassword",
          "request": {
            "url": "http://example.com/api/?Action=ForgotPassword?ClientId=ClientId&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the password for the specified client ID or username."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "546688af-d7a1-4fcb-8d77-e0aee0dbc8cb"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Ups",
      "item": [
        {
          "id": "11615b3c-5510-4692-aabf-415b7065620c",
          "name": "confirmSignUp",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmSignUp?ClientId=ClientId&ConfirmationCode=ConfirmationCode&ForceAliasCreation=ForceAliasCreation&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms registration of a user and handles the existing alias from a previous\n            user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be675cf7-ff99-459d-be59-e52212b6ab23"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "a4e1d464-e65b-4e5a-8c5b-4ae9546a9e67",
          "name": "createGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateGroup?Description=Description&GroupName=GroupName&Precedence=Precedence&RoleArn=RoleArn&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new group in the specified user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19d613a6-c3c6-4d8e-a75f-6de30b90f697"
            }
          ]
        },
        {
          "id": "03a672f9-94e2-4d03-8d90-42eda6daf7a9",
          "name": "deleteGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroup?GroupName=GroupName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d5aadf7-69b1-4a38-b9b6-f9153d10f440"
            }
          ]
        },
        {
          "id": "7c09e5d6-e172-49f4-b542-e3faa7459df5",
          "name": "getGroup",
          "request": {
            "url": "http://example.com/api/?Action=GetGroup?GroupName=GroupName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44091f88-1c08-48c7-8abb-bbcbad83acee"
            }
          ]
        },
        {
          "id": "c84ed414-faeb-46f9-8aed-bcb272e1d13c",
          "name": "listGroups",
          "request": {
            "url": "http://example.com/api/?Action=ListGroups?Limit=Limit&NextToken=NextToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the groups associated with a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "909e5549-4af3-495a-b58d-074cfa11e72f"
            }
          ]
        },
        {
          "id": "e3a15460-709e-42f6-acef-0d728cda6e92",
          "name": "updateGroup",
          "request": {
            "url": "http://example.com/api/?Action=UpdateGroup?Description=Description&GroupName=GroupName&Precedence=Precedence&RoleArn=RoleArn&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified group with the specified attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04c0fd51-745f-4a72-849c-86015cefc77d"
            }
          ]
        }
      ]
    },
    {
      "name": "CSV Header",
      "item": [
        {
          "id": "00fefb62-4584-4d68-9edb-c3223f727135",
          "name": "getCSVHeader",
          "request": {
            "url": "http://example.com/api/?Action=GetCSVHeader?UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the header information for the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b49cb64-66f3-42d4-bc8d-d3ef0d2beab1"
            }
          ]
        }
      ]
    },
    {
      "name": "Verification Codes",
      "item": [
        {
          "id": "4c32c4da-6e1c-4097-967a-eb4e91e41139",
          "name": "getUserAttributeVerificationCode",
          "request": {
            "url": "http://example.com/api/?Action=GetUserAttributeVerificationCode?AccessToken=AccessToken&AttributeName=AttributeName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the user attribute verification code for the specified attribute\n            name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37f571a4-fbb0-43c8-a989-00cfe79c1634"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Out",
      "item": [
        {
          "id": "4ecf458a-e415-4765-b357-e3f3734d72fb",
          "name": "globalSignOut",
          "request": {
            "url": "http://example.com/api/?Action=GlobalSignOut?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Signs out users from all devices."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a85231b-aa77-4905-b928-4650785b225a"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication",
      "item": [
        {
          "id": "92d4b0ce-9361-4785-b6e8-c172a73a1803",
          "name": "initiateAuth",
          "request": {
            "url": "http://example.com/api/?Action=InitiateAuth?AuthFlow=AuthFlow&AuthParameters=AuthParameters&ClientId=ClientId&ClientMetadata=ClientMetadata",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the authentication flow."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8536f780-3b73-4a53-bc8a-34d4d7d99003"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pool Clients",
      "item": [
        {
          "id": "2494d954-da39-4c98-8fc6-3b721eee954a",
          "name": "listUserPoolClients",
          "request": {
            "url": "http://example.com/api/?Action=ListUserPoolClients?MaxResults=MaxResults&NextToken=NextToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the clients that have been created for the specified user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "641f4b38-3911-4489-a7dd-971113ce9152"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pools",
      "item": [
        {
          "id": "43968d23-e9b7-4ae4-924e-36a258b6ad12",
          "name": "listUserPools",
          "request": {
            "url": "http://example.com/api/?Action=ListUserPools?MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the user pools associated with an AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ebc548f3-5266-4384-bb8f-6e33ca00de39"
            }
          ]
        }
      ]
    },
    {
      "name": "Confirmation Code",
      "item": [
        {
          "id": "40cc428c-66e2-470d-80fa-f8267c5c345c",
          "name": "resendConfirmationCode",
          "request": {
            "url": "http://example.com/api/?Action=ResendConfirmationCode?ClientId=ClientId&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resends the confirmation (for confirmation of registration) to a specific user in\n            the user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3b7c361-8bf8-4348-9271-d6fe4024f030"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenges",
      "item": [
        {
          "id": "2d6852ba-25ad-44d3-bd87-109f4cca7dbc",
          "name": "respondToAuthChallenge",
          "request": {
            "url": "http://example.com/api/?Action=RespondToAuthChallenge?ChallengeName=ChallengeName&ChallengeResponses=ChallengeResponses&ClientId=ClientId&Session=Session",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Responds to the authentication challenge."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e088d15-f8b5-4e6e-a965-74182c682c62"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Pool",
      "item": [
        {
          "id": "bcaea6d8-44bd-4471-8191-85eb737c5341",
          "name": "createIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=CreateIdentityPool?AllowUnauthenticatedIdentities=AllowUnauthenticatedIdentities&CognitoIdentityProviders=CognitoIdentityProviders&DeveloperProviderName=DeveloperProviderName&IdentityPoolName=IdentityPoolName&OpenIdConnectProviderARNs=OpenIdConnectProviderARNs&SamlProviderARNs=SamlProviderARNs&SupportedLoginProviders=SupportedLoginProviders",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0273a698-f219-48a8-801b-2ad14e5020cd"
            }
          ]
        },
        {
          "id": "4b1bc3ad-0dcf-463d-b760-165222f91e34",
          "name": "deleteIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentityPool?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "55758807-3ecd-4f54-9ab6-53baa9cb5306"
            }
          ]
        },
        {
          "id": "9e43c086-dea2-46ce-aa29-3003dda044dd",
          "name": "describeIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdentityPool?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets details about a particular identity pool, including the pool name, ID\n         description, creation date, and current number of users."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32c404c3-b690-4678-8172-8b2593c51c22"
            }
          ]
        },
        {
          "id": "137f9203-8f58-4a89-b147-b0705298798c",
          "name": "listIdentityPools",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentityPools?MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the Cognito identity pools registered for your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db476cfe-92eb-4dd6-bb89-8021cd00a8d1"
            }
          ]
        }
      ]
    },
    {
      "name": "Identities",
      "item": [
        {
          "id": "27e40656-67ee-4ac5-acdf-74b41b3d1299",
          "name": "deleteIdentities",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentities?IdentityIdsToDelete=IdentityIdsToDelete",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes identities from an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87814e36-653c-43f1-855d-c590de144940"
            }
          ]
        },
        {
          "id": "16d54442-8448-49a7-a349-94ef886b6339",
          "name": "describeIdentity",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdentity?IdentityId=IdentityId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns metadata related to the given identity, including when the identity was\n         created and any associated linked logins."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "130b5542-7223-413b-ab04-00f7bdef44f6"
            }
          ]
        },
        {
          "id": "670344a1-9fc6-4d46-a27c-05e35b3c996e",
          "name": "getCredentialsForIdentity",
          "request": {
            "url": "http://example.com/api/?Action=GetCredentialsForIdentity?CustomRoleArn=CustomRoleArn&IdentityId=IdentityId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns credentials for the provided identity ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "22cbe39a-5d99-4e82-9820-5132682de049"
            }
          ]
        },
        {
          "id": "7cb9cad6-2e20-41c3-bca1-c39778487c94",
          "name": "getId",
          "request": {
            "url": "http://example.com/api/?Action=GetId?AccountId=AccountId&IdentityPoolId=IdentityPoolId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates (or retrieves) a Cognito ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84a6b17f-d53d-4089-880d-351cb0dc57d7"
            }
          ]
        },
        {
          "id": "34c3c007-fa6e-4ef0-a6f3-48fb6d02f4ad",
          "name": "listIdentities",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentities?HideDisabled=HideDisabled&IdentityPoolId=IdentityPoolId&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the identities in a pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3f63b3d-f5ef-4682-a930-53386606f150"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Pool Roles",
      "item": [
        {
          "id": "828bc5f7-1c81-46c1-9ca3-89fcd83d4e2c",
          "name": "getIdentityPoolRoles",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityPoolRoles?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the roles for an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c08a087-d762-48b0-a8d6-f5163489f601"
            }
          ]
        }
      ]
    },
    {
      "name": "Open ID Token",
      "item": [
        {
          "id": "b2b87cf7-5117-453b-a9c5-afbe87dd830c",
          "name": "getOpenIdToken",
          "request": {
            "url": "http://example.com/api/?Action=GetOpenIdToken?IdentityId=IdentityId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets an OpenID token, using a known Cognito ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ae1500c-db3d-48db-9dfe-888336cf2cc7"
            }
          ]
        }
      ]
    },
    {
      "name": "Open ID Token for Developer Identities",
      "item": [
        {
          "id": "d103cc12-3f66-4b84-a7fd-f1bc0582c516",
          "name": "getOpenIdTokenForDeveloperIdentity",
          "request": {
            "url": "http://example.com/api/?Action=GetOpenIdTokenForDeveloperIdentity?IdentityId=IdentityId&IdentityPoolId=IdentityPoolId&Logins=Logins&TokenDuration=TokenDuration",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers (or retrieves) a Cognito IdentityId and an OpenID Connect\n         token for a user authenticated by your backend authentication process."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cdce4330-1b10-4e52-9372-195de18e9e70"
            }
          ]
        }
      ]
    }
  ]
}