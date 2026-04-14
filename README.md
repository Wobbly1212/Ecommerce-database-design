# E-Commerce Database Design

A complete **relational database design** for an e-commerce platform — covering requirement analysis, ER modeling, normalization (3NF), and SQL queries.

> **Note:** This is a design-focused project with no backend implementation. All components reflect relational database principles developed from formal specifications.

## Project Objective

Model an e-commerce system capable of managing:
- Physical and digital products
- Services (subscriptions and training programs)
- Customers (individuals and companies)
- Orders, deliveries, reviews, inventory
- Supplier management and framework contracts

## Design Process

| Phase | Description |
|-------|-------------|
| **1. Requirement Analysis** | Extracted static (entities, attributes) and dynamic (operations) specifications |
| **2. Conceptual ER Design** | Entity-Relationship Diagram with cardinalities, roles, and generalizations |
| **3. ER Restructuring** | Eliminated generalizations and multivalued attributes for relational compatibility |
| **4. Logical Schema** | Mapped ER to tables with primary/foreign keys following relational design standards |
| **5. Normalization** | Verified all relations up to Third Normal Form (3NF) |
| **6. Query Layer** | Reusable SQL queries for customers, orders, inventory, reviews, and services |

## Diagrams

| Diagram | Preview |
|---------|---------|
| Entity-Relationship Diagram | [ERD.png](docs/ERD.png) |
| Restructured ER | [Restructured_ER.png](docs/Restructured_ER.png) |
| Relational Model | [Relational_Model.png](docs/Relational_Model.png) |

## Project Structure

```
Ecommerce-database-design/
├── docs/
│   ├── ERD.png                      # Entity-Relationship Diagram
│   ├── Restructured_ER.png          # Restructured ER Diagram
│   ├── Relational_Model.png         # Relational Model
│   └── The E-commerce Platform.pdf  # Full documentation
├── LICENSE
└── README.md
```

## Use Cases

- Academic and course submissions
- Database design portfolio
- System architecture documentation
- Prototyping backend schema for e-commerce apps

## Author

**Diako Darabi**
*Information Systems and Databases — Course Project*
Supervisor: Prof. Mauro Iacono

## License

This project is licensed under the [MIT License](LICENSE).
