# Product Listing - Technical Document

## API Endpoint
- **GET /products** → Returns JSON array of products (id, name, price)

## Database Table: products
| Column | Type | Constraint |
|--------|------|----------|
| id | BIGINT | PRIMARY KEY |
| name | VARCHAR(255) | NOT NULL |
| price | DECIMAL(10,2) | NOT NULL |

## Initial Data
5 pre-populated products with realistic names and prices.