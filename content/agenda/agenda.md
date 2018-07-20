---
title: One Day Workshop
---

The high-level agenda for this GraphQL workshop will be split between two four-hour sessions. One session is primarily targeted at people newer to GraphQL or perhaps those that are unfamiliar with some of the concepts and benefits. The other session is primarily focused on those that have had a fair amount of experience with GraphQL, and so is focused on more "advanced" concepts in GraphQL and best practices as it relates to a GraphQL architecture.

The course will primarily focus on using tools from Apollo, but will mention other, competing libraries and tools like Graphcool and the graphql reference library, as well.

## GraphQL: An Introduction and Beyond

In this session, the intent is to gradually introduce the benefit and value statement for GraphQL, all the while teaching the foundational concepts. At the end of the session the attendees will have a greater understanding for not only the value of GraphQL, but also will feel confident to have a solid understanding of how to begin using it for their backend solution, today.

### What is GraphQL?

A high-level introduction to some of the foundational concepts that make GraphQL such an appealing technology.

### Why GraphQL?

GraphQL is taking the web by storm. What's so great about it? Why is it so transformative?

### The GraphQL Schema

The heart of GraphQL is the schema, which effectively describes your GraphQL API. We'll go through the ins and outs of the schema, and give a quick overview on a variety of concepts including types, using `graphql-tools` from Apollo, and more!

### The GraphQL Query Language in Detail

The query language is the way in which your GraphQL API is accessed. We'll go through the ins and outs of the power of this query language, and in particular, how to use and test it with tools like GraphQLPlayground and GraphiQL.

### GraphQL Integration / Usage

You're sold. GraphQL is the future of client and server-side interaction. How do we start using it, today? In particular, we'll make note of libraries from Apollo, as well as foundational concepts like resolvers.

## GraphQL: Advanced Topics and Architectural Best Practices

### Schema Stitching

One, monolithic GraphQL API for a number of disparate requests is probably not a best practice although it's very easy to do! In this section, we'll begin by introducing schema stitching and explaining best practices in creating a maintainable, scalable GraphQL API.

### Database Integration

GraphQL is unopinionated as far as backends go. Existing RESTful backend? MySQL DB? A NoSQL database like Mongo? GraphQL can handle each with ease. In this section, we'll dive deeper into resolvers and context to show to handle database integration with ease.

### Caching

Showing how to use cacheControl and globally unique IDs to only fetch resources, as needed.

### Security

Security for any API is important. We'll show best practices in implementing security into your GraphQL API using tools like Passport.

### Client-side Integration

You have a well-designed and sophisticated GraphQL API at this point. That raises the question... how do we best query this API from our client-side code? We'll begin to show how to best interact with this API using apollo-boost. As info, other libraries (or even going without a library) will also be briefly mentioned and demoed.
