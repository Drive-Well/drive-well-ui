# Drive Well - Workshop Management System

A comprehensive **Workshop Management System** developed using **Angular 17** and **Spring Boot** to streamline daily operations at **Church Street Motors, Auckland, NZ**. This system effectively manages vehicle servicing tasks, customer invoicing, product, real-time job tracking, and automated email notifications for live updates on job status. It also integrates **Spring Security OAuth** for role and permission-based authentication.

## Features

### 1. Dashboard Overview
- Provides an **admin dashboard** displaying key business metrics.
- Shows **Revenue, Payments, Invoices, Visitors, Revenue Overview, and Inventory Insights**.

#### Admin Dashboard
![Admin Dashboard](./Screenshots/1.png)

---

### 2. Vehicle Management
- Supports **creating and editing vehicle details**.

#### List Vehicles
![List Vehicle](./Screenshots/15.png)

#### Create Vehicle
![Create Vehicle](./Screenshots/2.png)

#### Edit Vehicle
![Edit Vehicle](./Screenshots/3.png)

---

### 3. Customer Management
- Supports **creating and editing customer details** including **name, email, mobile number, and address**.

#### List Customers
![List Customer](./Screenshots/4.png)

#### Create Customer
![Create Customer](./Screenshots/5.png)

#### Edit Customer
![Edit Customer](./Screenshots/6.png)

---

### 4. Product Management
- Supports **creating and editing product details** including.

#### List Products
![List Products](./Screenshots/7.png)

#### View Product
![View Products](./Screenshots/8.png)

---

### 5. Quotation Management
- Enables **creating quotations** for customers with **products, quantities, and unit prices**.
- Displays a summary of **quotation details and total amount**.
- Supports **editing and listing quotations**.

#### List Quotations
![List Quotation](./Screenshots/9.png)

#### Create Quotation
![Create Quotation](./Screenshots/10.png)

---

### 6. Invoice Management
- Allows **creating invoices** for customers.
- Includes fields for **products, quantities, unit prices, and total calculations**.
- Displays **invoice summaries with subtotals, discounts, and payments received**.
- Supports **editing invoices** and tracking customer payments.

#### List Invoices
![List Invoice](./Screenshots/14.png)

#### Create Invoice
![Create Invoice](./Screenshots/11.png)

#### Edit Invoice
![Edit Invoice](./Screenshots/12.png)

#### View Invoice
![View Invoice](./Screenshots/13.png)

---

### 7. Payments Management
- Displays a list of invoices with payment details, including **Invoice No, Payment Reference, Payment Date, and Amount**.
- Provides action buttons to **view, edit, or delete** payment entries.

#### Payment List View
![Payment List](./Screenshots/16.png)

#### Creaate Payment Details Modal
![Create Payment](./Screenshots/17.png)

#### View Payment Details Modal
![View Payment](./Screenshots/18.png)

---

### 8. Notifications & System Feedback
- Provides **real-time success notifications** for various actions like **updating invoices**.

#### Success Notification
![Success Message](./Screenshots/19.png)

---

### 9. Quick Access Menu
- A **dropdown menu** for quick creation of **Invoices, Quotations, Customers, Vehicles, and Products**.

#### Quick Access Dropdown
![Quick Access](./Screenshots/20.png)

---

### 10. Login
- A **Login page** for authentication.

#### Quick Access Dropdown
![Login](./Screenshots/21.png)

---

### 11. Email Template
- A **Email template page** for invoice.

#### Email Template
![email](./Screenshots/22.png)


## Tech Stack
- **Frontend:** Angular 17
- **Backend:** Spring Boot
- **Database:** MySQL / PostgreSQL
- **Security:** Spring Security OAuth
- **Notifications:** Email Integration

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/drive-well.git
   ```
2. Navigate to the project directory:
   ```bash
   cd drive-well
   ```
3. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   ```
4. Run the frontend:
   ```bash
   npm start
   ```
5. Start the backend (Spring Boot):
   ```bash
   cd backend
   mvn spring-boot:run
   ```

---

For any inquiries, contact **Church Street Motors, Auckland, NZ**:
📞 (09) 6342142  |  📧 churchstmotors@hotmail.com

