# APINote

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**note_id** | **int** | Unique ID for the Note record | [optional] 
**title** | **string** | Title of the Note (required) | 
**body** | **string** | Body of the Note | [optional] 
**link_subject_id** | **int** | ID of the Contact, Organisation, Opportunity or Project the Note is linked to | 
**link_subject_type** | **string** | Link subject type: CONTACT, ORGANISATION, OPPORTUNITY or PROJECT | 
**owner_user_id** | **int** | User ID of the Note owner | [optional] 
**date_created_utc** | [**\DateTime**](\DateTime.md) | Date and time Note record created, as Coordinated Universal Time | [optional] 
**date_updated_utc** | [**\DateTime**](\DateTime.md) | Date and time Note record updated, as Coordinated Universal Time | [optional] 
**visible_to** | **string** | Visible To: Everyone, Team, Owner or Individuals | [optional] 
**visible_team_id** | **int** | If VISIBLE_TO is &#39;Team&#39;, the TEAM_ID | [optional] 
**visible_user_ids** | **string** | If VISIBLE_TO is &#39;Individuals&#39;, a comma separated list of User IDs | [optional] 
**notelinks** | [**\Swagger\Client\Model\APINoteLink[]**](APINoteLink.md) | Set of Links attached to the Note | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


