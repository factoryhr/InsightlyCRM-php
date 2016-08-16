# APIProject

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**project_id** | **int** | Unique ID for the Project record | [optional] 
**project_name** | **string** | Name of the Project (required) | 
**status** | **string** | Status: Abandoned, Cancelled, Completed, Deferred, In Progress or Not Started | 
**project_details** | **string** | Details of the Project | [optional] 
**opportunity_id** | **int** | Unique ID for the Opportunity from which the Project may have been converted | [optional] 
**started_date** | [**\DateTime**](\DateTime.md) | Date Project started, in YYYY-MM-DD format | [optional] 
**completed_date** | [**\DateTime**](\DateTime.md) | Date Project completed, in YYYY-MM-DD format | [optional] 
**image_url** | **string** | URL of the Image for the Project | [optional] 
**responsible_user_id** | **int** | Responsible user ID | [optional] 
**owner_user_id** | **int** | User ID of the Project record owner | [optional] 
**date_created_utc** | [**\DateTime**](\DateTime.md) | Date and time Project record created, as Coordinated Universal Time | [optional] 
**date_updated_utc** | [**\DateTime**](\DateTime.md) | Date and time Project record updated, as Coordinated Universal Time | [optional] 
**category_id** | **int** | The Category ID of the Project, if it has been assigned to one. | [optional] 
**pipeline_id** | **int** | The Pipeline ID that the Project is in, if it has been assigned to one. Note: This is a read-only field, to update the Pipeline please use the /Projects/{id}/Pipeline endpoint. | [optional] 
**stage_id** | **int** | The Stage ID of the Stage the Project is in, if it has been assigned to one. Note: This is a read-only field, to update the Pipeline Stage please use the /Projects/{id}/PipelineStage endpoint. | [optional] 
**visible_to** | **string** | Visible To: Everyone, Owner, Team or Individuals | [optional] 
**visible_team_id** | **int** | If VISIBLE_TO is &#39;Team&#39;, the TEAM_ID | [optional] 
**visible_user_ids** | **string** | If VISIBLE_TO is &#39;Individuals&#39;, a comma separated list of user IDs | [optional] 
**customfields** | [**\Swagger\Client\Model\APICustomField[]**](APICustomField.md) | Set of Custom Fields attached to the Project | [optional] 
**tags** | [**\Swagger\Client\Model\APITag[]**](APITag.md) | Set of Tags attached to the Project | [optional] 
**links** | [**\Swagger\Client\Model\APILink[]**](APILink.md) | Set of Links attached to the Project | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


