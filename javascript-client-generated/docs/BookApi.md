# LibraryApiSpec.BookApi

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**createBook**](BookApi.md#createBook) | **POST** /v1/book | 
[**deleteBook**](BookApi.md#deleteBook) | **DELETE** /v1/book/{bookID} | 
[**getBookById**](BookApi.md#getBookById) | **GET** /v1/book/{bookID} | 
[**listBooks**](BookApi.md#listBooks) | **GET** /v1/book | 
[**updateBook**](BookApi.md#updateBook) | **PUT** /v1/book/{bookID} | 

<a name="createBook"></a>
# **createBook**
> createBook()



### Example
```javascript
import {LibraryApiSpec} from 'library_api_spec';

let apiInstance = new LibraryApiSpec.BookApi();
apiInstance.createBook((error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

<a name="deleteBook"></a>
# **deleteBook**
> deleteBook()



### Example
```javascript
import {LibraryApiSpec} from 'library_api_spec';

let apiInstance = new LibraryApiSpec.BookApi();
let  = new LibraryApiSpec.null(); //  | 

apiInstance.deleteBook(, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **** | [****](.md)|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

<a name="getBookById"></a>
# **getBookById**
> getBookById()



### Example
```javascript
import {LibraryApiSpec} from 'library_api_spec';

let apiInstance = new LibraryApiSpec.BookApi();
let  = new LibraryApiSpec.null(); //  | The unique identifier of the book to retrieve.

apiInstance.getBookById(, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **** | [****](.md)| The unique identifier of the book to retrieve. | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

<a name="listBooks"></a>
# **listBooks**
> listBooks()



### Example
```javascript
import {LibraryApiSpec} from 'library_api_spec';

let apiInstance = new LibraryApiSpec.BookApi();
apiInstance.listBooks((error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

<a name="updateBook"></a>
# **updateBook**
> updateBook()



### Example
```javascript
import {LibraryApiSpec} from 'library_api_spec';

let apiInstance = new LibraryApiSpec.BookApi();
let  = new LibraryApiSpec.null(); //  | The unique identifier of the book to update.

apiInstance.updateBook(, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **** | [****](.md)| The unique identifier of the book to update. | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

