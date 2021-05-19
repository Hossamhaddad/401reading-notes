# Room
### Room benefits : 
#### 1. Compile-time verification of SQL queries.
#### 2. Convenience annotations that minimize repetitive and error-prone boilerplate code
#### 3. Streamlined database migration paths.

### Room components :
#### 1. The database class 
#### 2. Data entities
#### 3. Data access objects (DAOs) 


## Entity
 ### Room creates a table for each class that has @Entity annotation, the fields in the class correspond to columns in the table. Therefore, the entity classes tend to be small model classes that don’t contain any logic

### Some Entities annotations : 
#### 1. @ColumnInfo
#### 2. @PrimaryKey
#### 3. @Ignore
#### 4. @Embeded

## Data access objects
### we can simply define our queries using annotations in the Dao class.

## Embedded
### Room Database enables us to create embedded objects. As, sometimes we need to express an objects as a cohesive whole in our database logic even if the object contains several fields. So, we can do that by using @Embedded annotation.

### Data Access Objects are used to access your application’s persisted data. They are a better and modular way to access your database as compared to query builders or direct queries.

### A Data Access Objects can be either an interface or an abstract class. If it’s an abstract class, it can optionally have a constructor that takes a RoomDatabase as its only parameter. Room creates each DAO implementation at compile time

### You can perform multiple operations using Data Access Objects :
#### 1. Insertion @Insert
#### 2. Updation @Update
#### 3. Deletion @Delete

#### @Query is the main annotation used in DAO classes. It allows you to perform read/write operations on a database. 
