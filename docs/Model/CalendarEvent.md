# CalendarEvent

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_id** | **int** | Unique ID for event record | [optional] 
**title** | **string** | Name or title of the event (required) | 
**location** | **string** | Location of the event | [optional] 
**details** | **string** | Details of the event | [optional] 
**start_date_utc** | [**\DateTime**](\DateTime.md) | Start date and time of the event, as Coordinated Universal Time | 
**end_date_utc** | [**\DateTime**](\DateTime.md) | End date and time of the event, as Coordinated Universal Time | 
**all_day** | **bool** | True, if event is an all-day event | [optional] 
**publicly_visible** | **bool** | True, if event is visible to others | [optional] 
**reminder_date_utc** | [**\DateTime**](\DateTime.md) | Reminder data and time of the event, as Coordinated Universal Time | [optional] 
**reminder_sent** | **bool** | True, if a reminder was sent | [optional] 
**eventlinks** | [**\Swagger\Client\Model\APIEventLink[]**](APIEventLink.md) | Set of links attached to the Event | [optional] 
**owner_user_id** | **int** | User ID of the event owner (must be a valid user ID) | [optional] 
**date_created_utc** | [**\DateTime**](\DateTime.md) | Date and time event record created, as Coordinated Universal Time | [optional] 
**date_updated_utc** | [**\DateTime**](\DateTime.md) | Date and time event record updated, as Coordinated Universal Time | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


