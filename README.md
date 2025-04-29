# 👨‍💻 Author

**Mohammdhossein Darabi**  
*Information Systems and Databases — Course Project*  
Supervisor: Prof. Mauro Iacono

---

# 🛒 E-Commerce Database Design

This repository presents the **design of a relational database** for an e-commerce platform.  
The entire project is strictly based on the **specifications provided** and the **step-by-step analysis of functional requirements** presented in the accompanying PDF file.

> ⚠️ **NOTE:**  
> This is a **design-focused project** with no backend or implementation code.  
> All components reflect **relational database principles** and were developed based on formal specification only.

---

## 🧠 Project Objective

To model an e-commerce system capable of managing:
- 🧾 Physical & Digital Products  
- 🛠️ Services (Subscriptions & Training Programs)  
- 👥 Customers (Individuals & Companies)  
- 🚚 Orders, Deliveries, Reviews, Inventory  
- 🏢 Supplier management & Framework contracts  

---

## 📐 Design Process

### 1️⃣ Requirement Analysis  
- Extracted both **static** (entities, attributes) and **dynamic** (operations) specifications  
- Identified generalizations and logical components  

### 2️⃣ Conceptual ER Design  
- Created detailed **Entity-Relationship Diagram (ERD)**  
- Modeled cardinalities, roles, and entity types  
- Generalizations: `Item → Product/Subscription/Training`, `Customer → Individual/Company`

### 3️⃣ ER Restructuring  
- Eliminated generalizations and multivalued attributes for **relational compatibility**  
- Applied one-to-one links to replace inheritance structures  
- Restructured schema to **support normalization and translation**

### 4️⃣ Logical Schema (Relational Design)  
- Mapped ER to tables with **primary/foreign keys**  
- Followed **relational design standards**  
- Ensured structural flexibility and data integrity

### 5️⃣ Normalization  
- Verified all relations up to **Third Normal Form (3NF)**  
- Removed redundancies like derived fields (e.g., TotalAmount)  
- Enhanced schema clarity and maintainability

### 6️⃣ Query Layer  
- Wrote reusable **SQL queries** for:
  - Customer info, Orders, Inventory, Reviews, Services  
  - Advanced operations like stock tracking & rating aggregation

---

## 🎯 Use Case

Ideal for:
- Academic & course submissions  
- Database design portfolio  
- System architecture documentation  
- Prototyping backend schema for e-commerce apps

---

