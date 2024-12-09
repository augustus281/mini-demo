### THIS IS A MINI PROJECT FOR DEMO DOMAIN-DRIVEN DESIGN

#### STRUCTURE OF PROJECT
__1. DOMAIN__
- Storing all the subdomains.

__2. ENTITY__
- A struct that has an Identifier and that can change state.

__3. VALUE OBJECTS__
- There can be occurrences where we have structs that are immutable and do not need a unique identifier.
- Value objects are often found inside domains and used to describe certain aspects in that domain.
- We will be creating one value object for now which is Transaction, once a transaction is performed, it cannot change state.

__4. AGGREGATES__
- An Aggregate is a set of entities and value objects combined.


**_Reference:_**
- https://dev.to/techschoolguru/how-to-setup-github-actions-for-go-postgres-to-run-automated-tests-81o
- https://programmingpercy.tech/blog/how-to-domain-driven-design-ddd-golang/
- https://refactoring.guru/design-patterns/factory-method