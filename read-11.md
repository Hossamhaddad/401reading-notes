# Spring RESTful Routing

### The @RequestMapping annotation can be applied to class-level and/or method-level in a controller.

### The class-level annotation maps a specific request path or pattern onto a controller. You can then apply additional method-level annotations to make mappings more specific to handler methods.

### RequestMapping Methods :

1. #### @GetMapping
2. #### @PostMapping
3. #### @PutMapping
4. #### @DeleteMapping
5. #### @PatchMapping

### Spring Data repository:

1. #### CrudRepository
2. #### PagingAndSortingRepository
3. #### JpaRepository

### CrudRepository implements basic CRUD operations, including count, delete, deleteById, save, saveAll, findById, and findAll.

### JpaRepository : It contains the full API of CrudRepository and PagingAndSortingRepository. So it contains API for basic CRUD operations and also API for pagination and sorting.
