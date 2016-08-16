# Team

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**team_id** | **int** | Unique ID for the Team record | [optional] 
**team_name** | **string** | Name of the Team, this field is required when creating a Team with ANONYMOUS_TEAM set to \&quot;false\&quot; | [optional] 
**anonymous_team** | **bool** | True, if this Team should not appear in the web UI | [optional] 
**date_created_utc** | [**\DateTime**](\DateTime.md) | Date and time Team record created, as Coorindated Universal Time | [optional] 
**date_updated_utc** | [**\DateTime**](\DateTime.md) | Date and time Team record updated, as Coordinated Universal Time | [optional] 
**teammembers** | [**\Swagger\Client\Model\APITeamMember[]**](APITeamMember.md) | Set of Team Members attached to the Team | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


