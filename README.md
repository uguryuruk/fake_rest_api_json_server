# fake_rest_api_json_server
A fake api in order to test frontend apps.

type and run "npm run start:server" to start the app.

* /employees GET
* /employees/:id GET, POST, DELETE
* /roles GET
* /roles?_embed=employees  GET

For queries

* /employees?_page=1$_limit=5 ... GET
* /employees?q=keyword ... GET
* /employees?gender=Male&_page=1&_limit=5 ...GET
