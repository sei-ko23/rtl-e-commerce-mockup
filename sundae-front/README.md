Testing :

- Test checkbox button :

* checkbox is unchecked by default
* checking checkbox enables button
* unchecking checkbox again disables button

- Test popover
- Test text
- Test button

Testing HTTP Request with Mock Service Worker to mock responses:

- Test option images render
- Mock Service Worker for scoops and toppings

1. Create handlers: functions that will determine what is returned for any particular url,
2. Create test server to handle requests,
3. Make sure the test servers listens during all tests and reset the server handlers after each test

rest.get('http://localhost:3030/scoops',(req,res,ctx)=>{})
handle type : rest or graphql
HTTP method to mock : get, post ..
full url to mock
response resolver function :

- req: request object
- res: function to create response
- ctx: context utility to build response

When waiting to smth to appear asynchronously on the page (like server connections ) ALLWAYS use await and findBy
Handling Server Errors:
