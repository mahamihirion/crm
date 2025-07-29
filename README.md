
# 🏢 Office Management Suite - CodeIgniter 4

An all-in-one Office Management Suite built with **CodeIgniter 4**, designed to streamline your business operations. This web-based software includes:

- ✅ CRM (Customer Relationship Management)
- 📦 Inventory Management
- 🛒 Product Selling
- 🛠️ Service Selling

---

## 🔧 Tech Stack

- Backend: PHP 8.1+ (CodeIgniter 4)
- Database: MySQL / MariaDB
- Frontend: Bootstrap 5 (customizable)
- Server: Apache/Nginx
- PDF: mPDF (for invoices, reports)

---

## 🚀 Features

### CRM
- Lead and customer management


### Inventory Management
- Stock level tracking
- Product categorization
- Supplier management


### Product Selling
- Product catalog
- Shopping cart & checkout
- Invoice generation
- Order tracking

### Service Selling
- Service listing & pricing
- Booking and appointment scheduling
- Status updates & staff assignment
- Feedback & rating system

---

## ⚙️ Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/office-management-suite.git
cd office-management-suite
```

### 2. Install Dependencies

```bash
composer install
```

### 3. Set Up Environment

Copy `.env.example` to `.env` and update the following:

```dotenv
CI_ENVIRONMENT = development
app.baseURL = 'http://localhost:8080/'

database.default.hostname = localhost
database.default.database = your_database_name
database.default.username = your_username
database.default.password = your_password
database.default.DBDriver = MySQLi
```

### 4. Set File Permissions

```bash
chmod -R 775 writable
```

### 5. Create Database

Create a MySQL database (e.g., `office_mgmt`) and import the included `database.sql` file OR run:

```bash
php spark migrate
```

### 6. Start the App

```bash
php spark serve
```

Open [http://localhost:8080](http://localhost:8080) in your browser.

---

## 📁 Directory Overview

```
app/
├── Config/
├── Controllers/
│   ├── CRM/
│   ├── Inventory/
│   ├── Sales/
│   ├── Services/
├── Models/
├── Views/
├── Filters/
public/
writable/
.env
composer.json
```

---

## 📦 Modules Included

- `CRMModule` – Manages contacts, leads, tasks
- `InventoryModule` – Products, stock, purchases
- `ProductSalesModule` – Online product catalog, checkout
- `ServiceSalesModule` – Bookings, appointments
- `AdminModule` – User management, roles, settings

---

## 🧩 Optional Integrations

- SMS Gateway (e.g. Twilio)
- Email (SMTP, Mailgun)
- Payment Gateway (Razorpay, Cashfree, Stripe)
- PDF Generation (mPDF)

---

## 🛡️ Security

- CSRF Protection enabled
- Input validation using CodeIgniter's Validation rules
- Session-based authentication
- Rate-limiting available via filters

---

## ✨ Roadmap (Coming Soon)

- Reports Dashboard with Charts
- REST API Support for Mobile App
- Live Chat/Support Ticket System
- Staff Attendance & Payroll

---

## 📄 License

Open-source under the MIT License. You can use, modify, and distribute this software freely.

---

## 👤 Author

**Shankar Dayal Bordoloi**  
🔗 [Portfolio](https://kundligenerator.com/shankar-bordoloi)  
📧 shankardayalbordoloi@gmail.com  
🌐 [kundligenerator.com](https://kundligenerator.com)

---

## ⭐️ Support

Leave a ⭐️ on the repo if this project helped you!  
For custom development or enterprise solutions, feel free to reach out.
