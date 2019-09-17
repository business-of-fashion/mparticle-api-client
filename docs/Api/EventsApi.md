# OpenAPI\Client\EventsApi

All URIs are relative to *https://s2s.mparticle.com/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**bulkUploadEvents**](EventsApi.md#bulkUploadEvents) | **POST** /bulkevents | Send events to mParticle
[**uploadEvents**](EventsApi.md#uploadEvents) | **POST** /events | Send events to mParticle



## bulkUploadEvents

> bulkUploadEvents($batch)

Send events to mParticle

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


$apiInstance = new OpenAPI\Client\Api\EventsApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$batch = array(new \OpenAPI\Client\Model\Batch()); // \OpenAPI\Client\Model\Batch[] | 

try {
    $apiInstance->bulkUploadEvents($batch);
} catch (Exception $e) {
    echo 'Exception when calling EventsApi->bulkUploadEvents: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **batch** | [**\OpenAPI\Client\Model\Batch[]**](../Model/Batch.md)|  | [optional]

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../../README.md#documentation-for-models)
[[Back to README]](../../README.md)


## uploadEvents

> uploadEvents($batch)

Send events to mParticle

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


$apiInstance = new OpenAPI\Client\Api\EventsApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$batch = new \OpenAPI\Client\Model\Batch(); // \OpenAPI\Client\Model\Batch | 

try {
    $apiInstance->uploadEvents($batch);
} catch (Exception $e) {
    echo 'Exception when calling EventsApi->uploadEvents: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **batch** | [**\OpenAPI\Client\Model\Batch**](../Model/Batch.md)|  | [optional]

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../../README.md#documentation-for-models)
[[Back to README]](../../README.md)

