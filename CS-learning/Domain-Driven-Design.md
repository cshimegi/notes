# Domain Driven Design (DDD)

## Basics You Should Know Before DDD
- ### Process based thinking
- ### Forward design
- ### Object-oriented

## Domain Modeling with DDD
- ### Domains, Subdomains & Bounded Context
- ### Context Maps
- ### Entities
- ### Value Objects
- ### Aggregates
- ### Services
- ### Domain Events
- ### Architecture

## 4 Layer Architecture
```mermaid
graph TD
    u[User Interface Layer]
	a[Application Layer]
	d[Domain Layer]
	i[Infrastructure Layer]
	
	u --> a
	a --> d
	u --> d
	a --> i
	d --> i
	u --> i
	
```


## Strategic Design & Tactical Design
### Strategic
- Domains, Subdomains & Bounded Context
- Context Maps

### Tactical
- Entities
- Value Objects
- Aggregates
- Services
- Domain Events
- Architecture