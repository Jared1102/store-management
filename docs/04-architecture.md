# System Architecture

## Architectural Style

The system is designed as a monolithic application with a layered architecture. This approach was chosen to keep the system simple, maintainable, and suitable for a single-developer project while still following good software design practices.

## Layers Overview

- **Presentation Layer**  
  Exposes a RESTful API to interact with the system. This layer handles HTTP requests, input validation, and response formatting.

- **Application Layer**  
  Contains use cases and orchestrates business operations such as sales processing, inventory updates, and report generation.

- **Domain Layer**  
  Encapsulates core business logic, entities, and business rules. This layer is independent of frameworks and external technologies.

- **Infrastructure Layer**  
  Handles data persistence, database access, and integration with external systems such as the database.

## Technology Stack

- Backend: .NET 8
- Database: PostgreSQL
- API Style: REST
- Architecture Type: Monolith

## Data Flow Overview

1. Client sends a request to the API.
2. The Presentation Layer validates the request.
3. The Application Layer executes the corresponding use case.
4. The Domain Layer enforces business rules.
5. The Infrastructure Layer persists or retrieves data.
6. The response is returned to the client.

## Architectural Decisions

- A monolithic architecture was selected over microservices to reduce complexity and operational overhead.
- PostgreSQL was chosen for its reliability, performance, and support for relational data.
- The system prioritizes business logic clarity over UI complexity.
