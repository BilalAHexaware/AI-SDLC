# System Diagrams

## API Flow
GET /api/v1/products -> ProductController -> ProductService -> ProductRepository -> Database -> JSON

## Database Schema
products: id (BIGINT PK), name (VARCHAR NOT NULL), price (DECIMAL NOT NULL), created_at, updated_at
