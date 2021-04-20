# Related Resources and Integration Testing

### The relationships between Entity classes:

1. #### OneToOne Relation
2. #### OneToMany Relation
3. #### ManyToOne Relation
4. #### ManyToMany Relation

### One to One :one to one relationship refers to the relationship between two database tables A and B in which only one row of A may only be linked to one row of B, and vice versa.

### One to Many : In this relationship each row of one entity is referenced to many child records in other entity. The important thing is that child records cannot have multiple parents

### Many To One : Where one entity is referenced with another entity which contain unique values. In relational databases these relations are applicable by using foreign key

### mant to many : is where one or more rows from one entity are associated with more than one row in other entity.

### Some integration test we can write :

1. #### Verify View Name
2. #### Verify Response Body
3. #### Send GET Request With Path Variable
4. #### Send GET Request With Query Parameters
5. #### Send POST Request
