# Product Listing - Architecture Document

## Components
- **Controller**: Spring REST endpoint for GET `/products`
- **Service**: ProductService with business logic
- **Repository**: Data access layer
- **Database**: PostgreSQL with products table

## Data Flow
Client → Controller → Service → Repository → Database → JSON Response