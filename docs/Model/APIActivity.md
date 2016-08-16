# APIActivity

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**activity_id** | **int** | Unique ID for the Activity | [optional] 
**activityset_id** | **int** | Unique ID for the Activity Set record that this Activity belongs to | [optional] 
**activity_name** | **string** | The name for the Activity | [optional] 
**activity_details** | **string** | The details for the Activity | [optional] 
**activity_type** | **string** | The type of Activity | [optional] 
**category_id** | **int** | The unique ID for the category associated with the Activity. Only applicable if the ACTIVITY_TYPE is set to TASK. | [optional] 
**reminder** | **bool** | Whether or not a reminder is set on the Activity. Only applicable if the ACTIVITY_TYPE is set to TASK. | [optional] 
**reminder_days_before_due** | **int** | Number of days before due date of the Activity a reminder will be sent out. Only applicable if the ACTIVITY_TYPE is set to TASK. | [optional] 
**reminder_time** | **string** | The time when a reminder will be sent out for the Activity. Only applicable if the ACTIVITY_TYPE is set to TASK. | [optional] 
**publicly_visible** | **bool** | Whether the Activity is publicly visible. | [optional] 
**owner_visible** | **bool** | Whether the Activity is visible to the Owner. | [optional] 
**owner_user_id** | **int** | The unique ID for the Owner of the Activity. | [optional] 
**responsible_user_id** | **int** | The unique ID for the Responsible User of the Activity. Only applicable if the ACTIVITY_TYPE is set to TASK. | [optional] 
**assigned_team_id** | **int** | The unique ID for the Responsible Team of the Activity. Only applicable if the ACTIVITY_TYPE is set to TASK. | [optional] 
**skip_sun** | **bool** | Whether or not to skip scheduling of this Activity on a Sunday. | [optional] 
**skip_mon** | **bool** | Whether or not to skip scheduling of this Activity on a Monday. | [optional] 
**skip_tue** | **bool** | Whether or not to skip scheduling of this Activity on a Tuesday. | [optional] 
**skip_wed** | **bool** | Whether or not to skip scheduling of this Activity on a Wednesday. | [optional] 
**skip_thu** | **bool** | Whether or not to skip scheduling of this Activity on a Thursday. | [optional] 
**skip_fri** | **bool** | Whether or not to skip scheduling of this Activity on a Friday. | [optional] 
**skip_sat** | **bool** | Whether or not to skip scheduling of this Activity on a Saturday. | [optional] 
**due_days_after_start** | **int** | Determines the due date based on number of days after the Activity Set is created. Only applicable if the ACTIVITY_TYPE is set to TASK. | [optional] 
**due_days_before_end** | **int** | Determines the due date based on number of days before the Activity Set ends. Only applicable if the ACTIVITY_TYPE is set to TASK. | [optional] 
**event_days_after_start** | **int** | Determines the event date based on number of days after the Activity Set is created. Only applicable if the ACTIVITY_TYPE is set to EVENT. | [optional] 
**event_days_before_end** | **int** | Determines the event date based on number of days before the Activity Set ends. Only applicable if the ACTIVITY_TYPE is set to EVENT. | [optional] 
**event_time** | **string** | The time of the event. Only applicable if the ACTIVITY_TYPE is set to EVENT. | [optional] 
**all_day** | **bool** | Whether or not the event is an all day event. Only applicable if the ACTIVITY_TYPE is set to EVENT. | [optional] 
**duration** | **int** | Duration of the event in hours. Only applicable if the ACTIVITY_TYPE is set to EVENT. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


