# Architecture Document

## Components
- Controller: Spring REST endpoint for GET /api/v1/products
- Service: ProductService with business logic
- Repository: ProductRepository (Spring Data JPA)
- Database: PostgreSQL with products table

## Data Flow
Client -> Controller -> Service -> Repository -> Database -> JSON Response
