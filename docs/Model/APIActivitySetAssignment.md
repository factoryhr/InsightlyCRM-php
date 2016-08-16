# APIActivitySetAssignment

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**activityset_id** | **int** | Unique ID for the Activity Set | [optional] 
**start_date** | [**\DateTime**](\DateTime.md) | Start Date for the Activity Set | [optional] 
**end_date** | [**\DateTime**](\DateTime.md) | End Date for the Activity Set. If activity set contains activities with end date specification then END_DATE is required | [optional] 
**activity_assignments** | [**\Swagger\Client\Model\APIActivityAssignment[]**](APIActivityAssignment.md) | List of Activity Assignments. Only needed for Task Activities that have not been pre-assigned when configuring the Activity Set. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


