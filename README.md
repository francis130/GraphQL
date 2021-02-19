# GraphQL
This is a repository that i created when i was following a tutorial on GraphQL from YouTube. link:https://www.youtube.com/watch?v=ZQL7tL2S0oQ&amp;t=673s

In this project, i follow the tutorial step by step.
1. The command 'npm init' is used to create the package.json file. When all initialisation requirments are done, a node-module file is created automatically.
2. The next step is to install all dependancies with the command;'npm i express express-graphql graphql'.
3. Then we install nodemon to help us start the server and keep it running with the command 'npm i --save-dev nodemon' followed by 'npm run devStart'
4. at this point we follow the tutorial guide as presented in https://www.youtube.com/watch?v=ZQL7tL2S0oQ&t=673s

Prerequisites

This course is based on NodeJs and Express. So, if you have a basic understanding of NodeJS, it will be easy to learn GraphQL. For frontend integration of GraphQL, we will be using ReactJs and Jquery. Since, illustrations in this tutorial uses EcmaScript 6 (ES6) syntax, knowledge in these areas can be helpful
GraphQL is an open source server-side technology which was developed by Facebook to optimize RESTful API calls. It is an execution engine and a data query language. In this chapter, we discuss about the advantages of using GraphQL.

Why GraphQL

RESTful APIs follow clear and well-structured resource-oriented approach. However, when the data gets more complex, the routes get longer. Sometimes it is not possible to fetch data with a single request. This is where GraphQL comes handy. GraphQL structures data in the form of a graph with its powerful query syntax for traversing, retrieving, and modifying data.

1. Ask for what you want − and get it
Send a GraphQL query to your API and get exactly what you need. GraphQL queries always return predictable results. Applications using GraphQL are fast and stable. Unlike Restful services, these applications can restrict data that should be fetched from the server.

2.Get many resources in a single request
GraphQL queries help to smoothly retrieve associated business objects, while typical REST APIs require loading from multiple URLs. GraphQL APIs fetch all the data your application need in a single request. Applications using GraphQL can be quick even on slow mobile network connections

3.Describe what’s possible with a type system
GraphQL is strongly typed and the queries are based on fields and their associated data types. If there is type mismatch in a GraphQL query, server applications return clear and helpful error messages. This helps in smooth debugging and easy detection of bugs by client applications. GraphQL also provides client side libraries that can help in reducing explicit data conversion and parsing.

4.Move faster with powerful developer tools
GraphQL provides rich developer tools for documentation and testing queries. GraphiQL is an excellent tool which generates documentation of the query and its schema. It also gives a query editor to test GraphQL APIs and intelligent code completion capability while building queries.

Source: https://www.tutorialspoint.com/graphql/graphql_environment_setup.htm
