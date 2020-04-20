GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data. GraphQL provides a complete and understandable description of the data in your API, gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools.

GraphQL presents your objects to the world as a graph structure rather than a more hierarchical structure to which you may be accustomed.

Core questions.
What is the difference between REST and GraphQL?
A REST API is an architectural concept for network-based software. GraphQL, on the other hand, is a query language, a specification, and a set of tools that operates over a single endpoint using HTTP. In addition, over the last few years, REST has been used to make new APIs, while the focus of GraphQL has been to optimize for performance and flexibility.

Why Graphs?
Graphs are powerful tools for modeling many real-world phenomena because they resemble our natural mental models and verbal descriptions of the underlying process. With GraphQL, you model your business domain as a graph by defining a schema; within your schema, you define different types of nodes and how they connect/relate to one another. On the client, this creates a pattern similar to Object-Oriented Programming: types that reference other types. On the server, since GraphQL only defines the interface, you have the freedom to use it with any backend (new or legacy!).

To summarize, GraphQL is meant to be used for client applications, where network bandwidth and latency are critical. It provides clients, the ability to query an object graph (a hierarchical structure of related objects). ... This makes it a whole lot simpler and easier to use and manage data fetching on the client's end.

**Resources.**
- https://www.apollographql.com/docs/apollo-server/ - JS
- https://github.com/graphql-python/flask-graphql
- https://medium.com/@marvinkome/creating-a-graphql-server-with-flask-ae767c7e2525
- https://docs.graphene-python.org/projects/sqlalchemy/en/latest/tutorial/
- https://www.rubrik.com/blog/graphql-vs-rest-apis/
- https://graphql.org/learn/thinking-in-graphs/

