# User

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **int** | Unique ID for the user record | [optional] 
**contact_id** | **int** | Unique ID for the Contact record corresponding to the User | [optional] 
**first_name** | **string** | First name | [optional] 
**last_name** | **string** | Last name | [optional] 
**timezone_id** | **string** | Timezone ID as set by the User in the User&#39;s regional settings | [optional] 
**email_address** | **string** | User&#39;s email address | [optional] 
**email_dropbox_identifier** | **string** | Identifier for the User&#39;s Email Mailbox | [optional] 
**email_dropbox_address** | **string** | The User&#39;s Email Mailbox address. Derived from the EMAIL_DROPBOX_IDENTIFIER. | [optional] 
**administrator** | **bool** | True, if the User is an Administrator for the Insightly instance | [optional] 
**account_owner** | **bool** | True, if the User is the Account owner for the Insightly instance | [optional] 
**active** | **bool** | True, if the account is active | [optional] 
**date_created_utc** | [**\DateTime**](\DateTime.md) | Date and time User record created, as Coordinated Universal Time | [optional] 
**date_updated_utc** | [**\DateTime**](\DateTime.md) | Date and time User record updated, as Coordinated Universal Time | [optional] 
**user_currency** | **string** | User&#39;s regional setting for Currency | [optional] 
**contact_display** | **string** | User&#39;s setting for Contact List display | [optional] 
**contact_order** | **string** | User&#39;s settting for Contact List order | [optional] 
**task_week_start** | **int** | User&#39;s start day of week | [optional] 
**instance_id** | **int** | Unique key of the Instance which this User belongs to | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


