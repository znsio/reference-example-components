# Postman collection to test the Product Catalog Component

Here is a sample postman collection to test the Product Catalog Component - you need to create an environment declaring the {{Hostname}} - get this from the API_ENDPOINT on the r1-productcatalog-productcatalogmanagement API resource - just use the first part of the URL with the hostname.

If you have applied API Keys or other authentication tokens in your deployment, you will need to add these in the headders in the postman collection.

There are three test colections:
* Functional test of the Product Catalog API
* Bulk deletion from the Product Catalog API
* Testing the role and event listeners
