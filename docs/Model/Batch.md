# # Batch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source_request_id** | **string** |  | [optional] 
**events** | [**\OpenAPI\Client\Model\BaseEvent[]**](BaseEvent.md) | Provide a list of event objects - such as CustomEvent, ScreenViewEvent, or CommerceEvent | [optional] 
**device_info** | [**\OpenAPI\Client\Model\DeviceInformation**](DeviceInformation.md) |  | [optional] 
**application_info** | [**\OpenAPI\Client\Model\ApplicationInformation**](ApplicationInformation.md) |  | [optional] 
**user_attributes** | **map[string,object]** |  | [optional] 
**deleted_user_attributes** | **string[]** |  | [optional] 
**user_identities** | [**\OpenAPI\Client\Model\BatchUserIdentities**](BatchUserIdentities.md) |  | [optional] 
**environment** | **string** |  | [default to 'production']
**api_key** | **string** |  | [optional] 
**api_keys** | **string[]** |  | [optional] 
**ip** | **string** |  | [optional] 
**integration_attributes** | [**map[string,map[string,string]]**](map.md) |  | [optional] 
**partner_identity** | **string** |  | [optional] 
**source_info** | [**\OpenAPI\Client\Model\SourceInformation**](SourceInformation.md) |  | [optional] 
**mp_deviceid** | **string** |  | [optional] 
**attribution_info** | [**\OpenAPI\Client\Model\AttributionInfo**](AttributionInfo.md) |  | [optional] 
**timestamp_unixtime_ms** | **int** |  | [optional] 
**batch_id** | **int** |  | [optional] 
**mpid** | **int** |  | [optional] 
**sdk_version** | **string** |  | [optional] 
**consent_state** | [**\OpenAPI\Client\Model\ConsentState**](ConsentState.md) |  | [optional] 
**job_id** | **string** |  | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)


