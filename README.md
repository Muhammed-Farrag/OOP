# Transportation Company System

A Java Spring Boot application demonstrating Object-Oriented Programming principles and UML design.

## Project Purpose

This project showcases **OOP skills** and proper software design through a Transportation Company System implementation.

## Technology Stack

- **Java 17** (OpenJDK)
- **Spring Boot 3.2.2**
- **Maven** - Build & dependency management
- **MySQL** - Database
- **Lombok** - Reduce boilerplate code
- **Spring Data JPA** - Database operations

## Architecture

Following the **layered architecture** pattern:

```
Controller → Service → Repository → Model
```

| Layer | Responsibility |
|-------|----------------|
| **Controller** | Handles requests, routes to service, returns JSON |
| **Service** | Business logic, rules & calculations |
| **Repository** | Database access, CRUD operations |
| **Model** | Data objects, entities |

## OOP Principles (4 Pillars)

| Pillar | Implementation |
|--------|----------------|
| **Encapsulation** | Private fields, controlled access via methods |
| **Inheritance** | Base classes (e.g., `Vehicle` → `Bus`, `Truck`) |
| **Polymorphism** | Method overriding, different behavior per type |
| **Abstraction** | Abstract classes & interfaces for contracts |

## Naming Conventions

| Type | Convention | Example |
|------|------------|---------|
| Classes | PascalCase | `TripController` |
| Methods | camelCase | `calculateFare()` |
| Variables | camelCase | `tripId` |
| Constants | SCREAMING_SNAKE_CASE | `MAX_PASSENGERS` |
| Packages | lowercase | `com.oop.transportation` |
| DB Columns | snake_case | `created_at` |

## Project Structure (Planned)

```
src/main/java/com/oop/transportation/
├── controller/    # REST endpoints
├── service/       # Business logic
├── repository/    # Data access
└── model/         # Entity classes
```

## UML Diagrams

See `Transportation Company System.drawio` for system design diagrams.

## Status

🚧 **Planning Phase** - Ready to start development