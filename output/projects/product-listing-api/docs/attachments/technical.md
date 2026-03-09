# Technical Document

## API Endpoint
GET /api/v1/products -> Returns JSON with data array and meta object

## Database Table: products
| Column | Type | Constraint |
|--------|------|------------|
| id | BIGINT | PRIMARY KEY, AUTO_INCREMENT |
| name | VARCHAR(255) | NOT NULL |
| price | DECIMAL(10,2) | NOT NULL, CHECK price > 0 |
| created_at | TIMESTAMP | DEFAULT CURRENT_TIMESTAMP |
| updated_at | TIMESTAMP | DEFAULT CURRENT_TIMESTAMP |

## Sample Data
5 products: Wireless Headphones 79.99, USB-C Cable 12.99, Laptop Stand 34.99, Mechanical Keyboard 129.99, 4K Monitor 299.99
