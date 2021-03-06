# DocuSign_eSign::FolderItemsResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**end_position** | **String** | The last position in the result set.  | [optional] 
**folder_items** | [**Array&lt;FolderItem&gt;**](FolderItem.md) | A list of the envelopes in the specified folder or folders.  | [optional] 
**next_uri** | **String** | The URI to the next chunk of records based on the search request. If the endPosition is the entire results of the search, this is null.  | [optional] 
**previous_uri** | **String** | The postal code for the billing address. | [optional] 
**result_set_size** | **String** | The number of results returned in this response.  | [optional] 
**start_position** | **String** | Starting position of the current result set. | [optional] 
**total_set_size** | **String** | The total number of items available in the result set. This will always be greater than or equal to the value of the property returning the results in the in the response. | [optional] 


