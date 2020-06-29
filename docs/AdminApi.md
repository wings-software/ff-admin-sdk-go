# \AdminApi

All URIs are relative to *http://localhost:3000/api/1.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateFeatureFlag**](AdminApi.md#CreateFeatureFlag) | **Post** /admin/feature-flag | Create feature flag.
[**CreateTarget**](AdminApi.md#CreateTarget) | **Post** /admin/target | Create target.
[**CreateTargetSegment**](AdminApi.md#CreateTargetSegment) | **Post** /admin/target-segment | Create target segment.
[**DeleteFeatureFlag**](AdminApi.md#DeleteFeatureFlag) | **Delete** /admin/feature-flag/{id} | Delete feature flag.
[**DeleteTarget**](AdminApi.md#DeleteTarget) | **Delete** /admin/target/{id} | Delete target.
[**DeleteTargetSegment**](AdminApi.md#DeleteTargetSegment) | **Delete** /admin/target-segment/{id} | Delete target segment.
[**GetAllFeatureFlags**](AdminApi.md#GetAllFeatureFlags) | **Get** /admin/feature-flag | Retrieve all feature flags.
[**GetAllTargetSegments**](AdminApi.md#GetAllTargetSegments) | **Get** /admin/target-segment | Retrieve all target segments.
[**GetAllTargets**](AdminApi.md#GetAllTargets) | **Get** /admin/target | Retrieve all targets.
[**GetFeatureFlag**](AdminApi.md#GetFeatureFlag) | **Get** /admin/feature-flag/{id} | Retrieve feature flag.
[**GetTarget**](AdminApi.md#GetTarget) | **Get** /admin/target/{id} | Retrieve target.
[**GetTargetSegment**](AdminApi.md#GetTargetSegment) | **Get** /admin/target-segment/{id} | Retrieve target segment.
[**ModifyFeatureFlag**](AdminApi.md#ModifyFeatureFlag) | **Patch** /admin/feature-flag/{id} | Modify feature flag.
[**ModifyTarget**](AdminApi.md#ModifyTarget) | **Patch** /admin/target/{id} | Modify target.
[**ModifyTargetSegment**](AdminApi.md#ModifyTargetSegment) | **Patch** /admin/target-segment/{id} | Modify target segment.



## CreateFeatureFlag

> CreateFeatureFlag(ctx, featureFlag)

Create feature flag.

Used to create feature flag.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**featureFlag** | [**FeatureFlag**](FeatureFlag.md)|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateTarget

> CreateTarget(ctx, target)

Create target.

Used to create target.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**target** | [**Target**](Target.md)|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateTargetSegment

> CreateTargetSegment(ctx, targetSegment)

Create target segment.

Used to create target segment.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**targetSegment** | [**TargetSegment**](TargetSegment.md)|  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteFeatureFlag

> DeleteFeatureFlag(ctx, id)

Delete feature flag.

Used to delete feature flag with certain id and account id.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | [**string**](.md)| resource ID | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteTarget

> DeleteTarget(ctx, id)

Delete target.

Used to delete target with certain id and account id.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | [**string**](.md)| resource ID | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteTargetSegment

> DeleteTargetSegment(ctx, id)

Delete target segment.

Used to delete target segment with certain id and account id.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | [**string**](.md)| resource ID | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllFeatureFlags

> FeatureFlag GetAllFeatureFlags(ctx, )

Retrieve all feature flags.

Used to retrieve all feature flags for certain account id.

### Required Parameters

This endpoint does not need any parameter.

### Return type

[**FeatureFlag**](FeatureFlag.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllTargetSegments

> TargetSegment GetAllTargetSegments(ctx, )

Retrieve all target segments.

Used to retrieve all target segments for certain account id.

### Required Parameters

This endpoint does not need any parameter.

### Return type

[**TargetSegment**](TargetSegment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllTargets

> Target GetAllTargets(ctx, )

Retrieve all targets.

Used to retrieve all targets for certain account id.

### Required Parameters

This endpoint does not need any parameter.

### Return type

[**Target**](Target.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFeatureFlag

> FeatureFlag GetFeatureFlag(ctx, id)

Retrieve feature flag.

Used to retrieve certain feature flags for certain id and account id.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | [**string**](.md)| resource ID | 

### Return type

[**FeatureFlag**](FeatureFlag.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTarget

> Target GetTarget(ctx, id)

Retrieve target.

Used to retrieve certain target for certain id and account id.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | [**string**](.md)| resource ID | 

### Return type

[**Target**](Target.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTargetSegment

> TargetSegment GetTargetSegment(ctx, id)

Retrieve target segment.

Used to retrieve certain target segment for certain id and account id.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | [**string**](.md)| resource ID | 

### Return type

[**TargetSegment**](TargetSegment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ModifyFeatureFlag

> FeatureFlag ModifyFeatureFlag(ctx, id, featureFlag)

Modify feature flag.

Used to modify feature flag with certain id and account id.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | [**string**](.md)| resource ID | 
**featureFlag** | [**FeatureFlag**](FeatureFlag.md)|  | 

### Return type

[**FeatureFlag**](FeatureFlag.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ModifyTarget

> Target ModifyTarget(ctx, id, target)

Modify target.

Used to modify target with certain id and account id.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | [**string**](.md)| resource ID | 
**target** | [**Target**](Target.md)|  | 

### Return type

[**Target**](Target.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ModifyTargetSegment

> TargetSegment ModifyTargetSegment(ctx, id, targetSegment)

Modify target segment.

Used to modify target segment with certain id and account id.

### Required Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | [**string**](.md)| resource ID | 
**targetSegment** | [**TargetSegment**](TargetSegment.md)|  | 

### Return type

[**TargetSegment**](TargetSegment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

