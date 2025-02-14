# Drive Well - Workshop Management System

A comprehensive **Workshop Management System** developed using **Angular 17** and **Spring Boot** to streamline daily operations at **Church Street Motors, Auckland, NZ**. This system effectively manages vehicle servicing tasks, customer invoicing, product inventory, real-time job tracking, and automated email notifications for live updates on job status. It also integrates **Spring Security OAuth** for role and permission-based authentication.

## Features

### 1. Dashboard Overview
- Provides an **admin dashboard** displaying key business metrics.
- Shows **Revenue, Payments, Invoices, Visitors, Revenue Overview, and Inventory Insights**.

#### Admin Dashboard
![Admin Dashboard](./images/image.png)

---

### 2. Payments Management
- Displays a list of invoices with payment details, including **Invoice No, Payment Reference, Payment Date, and Amount**.
- Provides action buttons to **view, edit, or delete** payment entries.

#### Payment List View
![Payment List](./images/Screenshot_2025-02-14_175215.png)

#### View Payment Details Modal
![View Payment](./images/Screenshot_2025-02-14_175241.png)

---

### 3. Quotation Management
- Enables **creating quotations** for customers with **products, quantities, and unit prices**.
- Displays a summary of **quotation details and total amount**.
- Supports **editing and listing quotations**.

#### Create Quotation
![Create Quotation](./images/Screenshot_2025-02-14_175314.png)

#### Quotation List
![Quotation List](./images/Screenshot_2025-02-14_180835.png)

---

### 4. Invoice Management
- Allows **creating invoices** for customers.
- Includes fields for **products, quantities, unit prices, and total calculations**.
- Displays **invoice summaries with subtotals, discounts, and payments received**.
- Supports **editing invoices** and tracking customer payments.

#### Create Invoice
![Create Invoice](./images/Screenshot_2025-02-14_175434.png)

#### Edit Invoice
![Edit Invoice](./images/Screenshot_2025-02-14_180911.png)

#### View Invoice
![View Invoice](./images/screencapture-localhost-4200-2025-02-14-17_51_10.png)

---

### 5. Customer Management
- Supports **creating and editing customer details** including **name, email, mobile number, and address**.

#### Create Customer
![Create Customer](./images/Screenshot_2025-02-14_175535.png)

#### Edit Customer
![Edit Customer](./images/Screenshot_2025-02-14_175605.png)

---

### 6. Notifications & System Feedback
- Provides **real-time success notifications** for various actions like **updating invoices**.

#### Success Notification
![Success Message](./images/Screenshot_2025-02-14_175702.png)

---

### 7. Quick Access Menu
- A **dropdown menu** for quick creation of **Invoices, Quotations, Customers, Vehicles, and Products**.

#### Quick Access Dropdown
![Quick Access](./images/Screenshot_2025-02-14_175511.png)

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

