# APIContact

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**contact_id** | **int** | Unique ID for the Contact record | [optional] 
**salutation** | **string** | Salutation | [optional] 
**first_name** | **string** | First/Given Name | [optional] 
**last_name** | **string** | Last/Family/Surname of the Contact | [optional] 
**background** | **string** | Additional background information | [optional] 
**image_url** | **string** | URL of the Image for the Contact. | [optional] 
**default_linked_organisation** | **int** | Unique key of the Organisation linked to the Contact, must be a valid ORGANISATION_ID | [optional] 
**owner_user_id** | **int** | User ID of the Contact owner | [optional] 
**date_created_utc** | [**\DateTime**](\DateTime.md) | Date and time Contact record created, as Coordinated Universal Time | [optional] 
**date_updated_utc** | [**\DateTime**](\DateTime.md) | Date and time Contact record updated, as Coordinated Universal Time | [optional] 
**visible_to** | **string** | Visible To | [optional] 
**visible_team_id** | **int** | If VISIBLE_TO is &#39;Team&#39;, then this should be a TEAM_ID | [optional] 
**visible_user_ids** | **string** | If VISIBLE_TO is &#39;Individuals, this should be a comma separated list of user IDs | [optional] 
**customfields** | [**\Swagger\Client\Model\APICustomField[]**](APICustomField.md) | Set of custom fields attached to the Contact | [optional] 
**addresses** | [**\Swagger\Client\Model\APIAddress[]**](APIAddress.md) | Set of addresses attached to the Contact | [optional] 
**contactinfos** | [**\Swagger\Client\Model\APIContactInfo[]**](APIContactInfo.md) | Set of contact infos attached to the Contact | [optional] 
**dates** | [**\Swagger\Client\Model\APIContactDate[]**](APIContactDate.md) | Set of dates to remember attached to the Contact | [optional] 
**tags** | [**\Swagger\Client\Model\APITag[]**](APITag.md) | Set of tags attached to the Contact | [optional] 
**links** | [**\Swagger\Client\Model\APILink[]**](APILink.md) | Set of links attached to the Contact | [optional] 
**contactlinks** | [**\Swagger\Client\Model\APIContactLink[]**](APIContactLink.md) | Set of links to other contacts attached to the Contact | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


