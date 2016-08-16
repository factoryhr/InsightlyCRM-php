# ActivitySet

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**activityset_id** | **int** | Unique ID for the Activity Set record. | [optional] 
**name** | **string** | The name for the Activity Set. | [optional] 
**for_contacts** | **bool** | Whether or not the Activity Set is assignable to Contacts. | [optional] 
**for_organisations** | **bool** | Whether or not the Activity Set is assignable to Organisations. | [optional] 
**for_opportunities** | **bool** | Whether or not the Activity Set is assignable to Opportunities. | [optional] 
**for_projects** | **bool** | Whether or not the Activity Set is assignable to Projects. | [optional] 
**for_leads** | **bool** | Whether or not the Activity Set is assignable to Leads. | [optional] 
**owner_user_id** | **int** | The unique ID for the Owner of the Activity. | [optional] 
**activities** | [**\Swagger\Client\Model\APIActivity[]**](APIActivity.md) | The list of Activities that belong to the Activity Set. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


