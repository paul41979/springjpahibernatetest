# springjpahibernatetest
Test SpringData JPA and hibernate versions

- Uses JTA setup for transaction management
- H2
- Spring Data JPA
- Spring Boot
- Named query on entity
- JPA Repository which should lookup named query by default
- Works fine for Hibernate 5.0.2
- Fails for Hibernate 5.2.11 as resolving the count query causes an IllegalStateException


