## Pagination

> The default limit is 100 items.

```shell
curl -X GET -H "Content-type: application/json" -H "Authorization: Bearer <ACCESS_TOKEN>"
https://api.companycam.com/v2/users?per_page=50&page=1
```


The CompanyCam API enables pagination by allowing users to include 'per_page'
and 'page' parameters on GET requests to index pages.
