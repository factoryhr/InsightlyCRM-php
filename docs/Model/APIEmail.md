# APIEmail

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email_id** | **int** | Unique ID for the email record | [optional] 
**gmail_message_id** | **string** | Unique key of the Gmail message | [optional] 
**email_date_utc** | [**\DateTime**](\DateTime.md) | Date and time email sent, as Coordinated Universal Time | [optional] 
**email_from** | **string** | From address of the email | [optional] 
**email_to** | **string** | To addresses of the email | [optional] 
**email_cc** | **string** | CC addresses of the email | [optional] 
**subject** | **string** | Subject of the Email | [optional] 
**body** | **string** | The body of the Email. This field is empty on list requests. | [optional] 
**body_extract** | **string** | An extract of the Email body. | [optional] 
**format** | **string** | Format of the email: text or html | [optional] 
**size** | **int** | The size of the email, in bytes | [optional] 
**owner_user_id** | **int** | Insightly User ID of the email owner | [optional] 
**date_created_utc** | [**\DateTime**](\DateTime.md) | Date and time Email record created, as Coordinated Universal Time | [optional] 
**visible_to** | **string** | Visible To: Everyone, Owner, Team or Individuals | [optional] 
**visible_team_id** | **int** | If VISIBLE_TO is &#39;Team&#39;, the TEAM_ID | [optional] 
**visible_user_ids** | **string** | If VISIBLE_TO is &#39;Individuals&#39;, a comma separated list of user IDs | [optional] 
**emaillinks** | [**\Swagger\Client\Model\APIEmailLink[]**](APIEmailLink.md) | Set of links attached to the Email | [optional] 
**tags** | [**\Swagger\Client\Model\APITag[]**](APITag.md) | Set of tags attached to the Email | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


