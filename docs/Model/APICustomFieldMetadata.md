# APICustomFieldMetadata

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_field_id** | **string** | Unique ID for the custom field record | 
**order_id** | **int** | ORDER_ID is required | 
**field_for** | **string** | The type of object this custom field is for: Contact, Organisation, Project or Opportunity | 
**field_name** | **string** | The name of the custom field | 
**field_type** | **string** | The type of data this custom field holds: text, date or dropdown | 
**field_help_text** | **string** | Help text that appears next to the custom field in the UI. | [optional] 
**default_value** | **object** | The default value of the custom field | [optional] 
**group_id** | **int** | Unique key of the custom field group | [optional] 
**editable** | **bool** | Whether or not the field is editable | [optional] 
**visible** | **bool** | Whether or not the field is visible | [optional] 
**custom_field_options** | [**\Swagger\Client\Model\APICustomFieldOption[]**](APICustomFieldOption.md) | A list of option values for a dropdown Custom Field | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


