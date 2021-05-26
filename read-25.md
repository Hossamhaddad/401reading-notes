# GraphQL

### GraphQL is a way of building and accessing APIs that allows for more flexibility and efficiency than traditional REST API endpoints.

### we use @connection annotation to specify relationships between models @model

### GraphQL realationship :

#### 1. one-to-one connection

#### 2. one-to-many

#### 3. many-to-many

### One to One Example

type Project @model {
id: ID!
name: String
team: Team @connection
}

type Team @model {
id: ID!
name: String!
}

### One to many Example

type Post @model {
id: ID!
title: String!
comments: [Comment] @connection(keyName: "byPost", fields: ["id"])
}

type Comment @model
@key(name: "byPost", fields: ["postID", "content"]) {
id: ID!
postID: ID!
content: String!
}

### one-to-many connection needs an @key

### many to many Example

type Post @model {
id: ID!
title: String!
editors: [PostEditor] @connection(keyName: "byPost", fields: ["id"])
}

# Create a join model and disable queries as you don't need them

# and can query through Post.editors and User.posts

type PostEditor
@model(queries: null)
@key(name: "byPost", fields: ["postID", "editorID"])
@key(name: "byEditor", fields: ["editorID", "postID"]) {
id: ID!
postID: ID!
editorID: ID!
post: Post! @connection(fields: ["postID"])
editor: User! @connection(fields: ["editorID"])
}

type User @model {
id: ID!
username: String!
posts: [PostEditor] @connection(keyName: "byEditor", fields: ["id"])
}

### many-to-many connection needs two @key
