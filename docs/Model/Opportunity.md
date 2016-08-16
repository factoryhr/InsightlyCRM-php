# Opportunity

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**opportunity_id** | **int** | Unique ID for the Opportunity record | [optional] 
**opportunity_name** | **string** | Name of the Opportunity | [optional] 
**opportunity_details** | **string** | Opportunity details | [optional] 
**probability** | **int** | Percentage probability of winning the Opportunity, as an integer value from 0 to 100 | [optional] 
**bid_currency** | **string** | Three character code for a currency | [optional] 
**bid_amount** | **int** | Potential value of the Opportunity, as an integer value | [optional] 
**bid_type** | **string** | Type of bid for the Opportunity: Fixed Bid, Per Hour, Per Day, Per Week, Per Month or Per Year | [optional] 
**bid_duration** | **int** | Duration of the bid of the Opportunity, if per hour/day/etc as an integer value | [optional] 
**opportunity_value** | **int** | Total value of the Opportunity, calculated based on BID_AMOUNT, BID_TYPE and BID_DURATION. This is a read-only field. | [optional] 
**forecast_close_date** | [**\DateTime**](\DateTime.md) | Forecast close date of the Opportunity, in YYYY-MM-DD format | [optional] 
**actual_close_date** | [**\DateTime**](\DateTime.md) | Actual close date of the Opportunity, in YYYY-MM-DD format | [optional] 
**category_id** | **int** | The Category ID of the Opportunity, if it has been assigned to one | [optional] 
**pipeline_id** | **int** | The Pipeline ID that the Opportunity is in, if it has been assigned to one. Note: This is a read-only field, to update the Pipeline please use the /Opportunities/{id}/Pipeline endpoint. | [optional] 
**stage_id** | **int** | The Stage ID of the Stage that the Opportunity is in, if it has been assigned to one. Note: This is a read-only field, to update the Pipeline Stage please use the /Opportunities/{id}/PipelineStage endpoint. | [optional] 
**opportunity_state** | **string** | Opportunity State (required): Open, Abandoned, Lost, Suspended, Won | 
**opportunity_state_reason_id** | **int** | Opportunity State Reason ID. Optional, if specified this field must have a valid State Reason ID. | [optional] 
**image_url** | **string** | URL of the Image for the Opportunity | [optional] 
**responsible_user_id** | **int** | ID of the responsible user for the Opportunity | [optional] 
**owner_user_id** | **int** | User ID of the record owner | [optional] 
**date_created_utc** | [**\DateTime**](\DateTime.md) | Date and time Opportunity record created, as Coordinated Universal Time | [optional] 
**date_updated_utc** | [**\DateTime**](\DateTime.md) | Date and time Opportunity record updated, as Coordinated Universal Time | [optional] 
**visible_to** | **string** | Visible To: Everyone, Owner, Team or Individuals | [optional] 
**visible_team_id** | **int** | If VISIBLE_TO is &#39;Team&#39;, the TEAM_ID | [optional] 
**visible_user_ids** | **string** | If VISIBLE_TO is &#39;Individuals&#39;, a comma separated list of User IDs | [optional] 
**customfields** | [**\Swagger\Client\Model\APICustomField[]**](APICustomField.md) | Set of Custom Fields attached to the Opportunity | [optional] 
**tags** | [**\Swagger\Client\Model\APITag[]**](APITag.md) | Set of Tags attached to the Opportunity | [optional] 
**links** | [**\Swagger\Client\Model\APILink[]**](APILink.md) | Set of Links attached to the Opportunity | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


