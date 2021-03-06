# asposeomrcloud.OmrApi

All URIs are relative to *https://localhost/v1.1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**post_run_omr_task**](OmrApi.md#post_run_omr_task) | **POST** /omr/{name}/runOmrTask | Run specific OMR task


# **post_run_omr_task**
> OMRResponse post_run_omr_task(name, action_name, param=param, storage=storage, folder=folder)

Run specific OMR task

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **str**| Name of the file to recognize. | 
 **action_name** | **str**| Action name [&#39;CorrectTemplate&#39;, &#39;FinalizeTemplate&#39;, &#39;RecognizeImage&#39;] | 
 **param** | [**OMRFunctionParam**](OMRFunctionParam.md)| Function params, specific for each actionName | [optional] 
 **storage** | **str**| Image&#39;s storage. | [optional] 
 **folder** | **str**| Image&#39;s folder. | [optional] 

### Return type

[**OMRResponse**](OMRResponse.md)

### Authorization

Library uses OAUTH2 authorization internally

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

