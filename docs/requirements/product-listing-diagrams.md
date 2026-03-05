# Product Listing - Diagrams

## API Flow
```
GET /products → Spring Controller → ProductService → ProductRepository → Database → JSON Array
```

## Database Schema
```
products
├── id (BIGINT, PK)
├── name (VARCHAR)
└── price (DECIMAL)
```