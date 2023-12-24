### GraphQL

GraphQL is a query language 
- Alternative to using a REST API using end-points. REST API is more of
an architectural choice for fetching data and making requests. Whereas,
graphQL is very much a query language with its own syntax and rules.
- GraphQL still uses HTTP requests under the hood, similar to making requests using REST APIs. It's just that in graphQL we have a control 
on what data we want to fetch and mutate.
- When your application scales it gets difficult to use REST APIs some of them are:
       1) Over fetching
       2) Under fetching
- These two drawbacks can be easily solved using GraphQL.
- GraphQL has a single endpoint. So whenever we send a query using graphql to the server its always going to be sent to probably one single end-point and then the server can handle it.
- Inorder to retrieve data from the server, you need to specify the required fields. You can also nest queries into a single query
- You can also perform mutations, you can ask the grapgQL Server to add new data/ update it / delete it similar to a POST/DELETE request



### Query basics
- Apollo explorer is a way for us to send test queries to a graphQL server and the responses that we get back. Similar to postman for REST APIs






- Node.js
- Libraray called Apollo Server - easily spins up a graphQL Sever