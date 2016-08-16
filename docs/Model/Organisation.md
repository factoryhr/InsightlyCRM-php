# Organisation

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organisation_id** | **int** | Unique ID for the Organisation record | [optional] 
**organisation_name** | **string** | Name of the Organisation (required) | 
**background** | **string** | Additional background information | [optional] 
**image_url** | **string** | URL of the Image for the Organisation | [optional] 
**owner_user_id** | **int** | User ID of the Organisation record owner | [optional] 
**date_created_utc** | [**\DateTime**](\DateTime.md) | Date and time Organisation record created, as Coordinated Universal Time | [optional] 
**date_updated_utc** | [**\DateTime**](\DateTime.md) | Date and time Organisation record updated, as Coordinated Universal Time | [optional] 
**visible_to** | **string** | Visible To: Everyone, Owner, Team or Individuals | [optional] 
**visible_team_id** | **int** | If VISIBLE_TO is &#39;Team&#39;, the TEAM_ID | [optional] 
**visible_user_ids** | **string** | If VISIBLE_TO is &#39;Individuals&#39;, a comma separated list of User IDs | [optional] 
**customfields** | [**\Swagger\Client\Model\APICustomField[]**](APICustomField.md) | Set of Custom Fields atttached to the Organisation | [optional] 
**addresses** | [**\Swagger\Client\Model\APIAddress[]**](APIAddress.md) | Set of Addresses attached to the Organisation | [optional] 
**contactinfos** | [**\Swagger\Client\Model\APIContactInfo[]**](APIContactInfo.md) | Set of Contact Infos attached to the Organisation | [optional] 
**dates** | [**\Swagger\Client\Model\APIOrganisationDate[]**](APIOrganisationDate.md) | Set of Dates to Remember attached to the Organisation | [optional] 
**tags** | [**\Swagger\Client\Model\APITag[]**](APITag.md) | Set of Tags attached to the Organisation | [optional] 
**links** | [**\Swagger\Client\Model\APILink[]**](APILink.md) | Set of Links attached to the Organisation | [optional] 
**organisationlinks** | [**\Swagger\Client\Model\APIOrganisationLink[]**](APIOrganisationLink.md) | Set of Links to other Organisations attached to the Organisation | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


