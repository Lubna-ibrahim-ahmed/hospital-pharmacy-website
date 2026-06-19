# Al Shifaa Hospital Pharmacy Website

A front-end Pharmacy IT System designed for the pharmacy department of a hospital.  
The project simulates a real pharmacy workflow including inventory management, medicine sales, reporting, dashboard monitoring, and account management.

---
## Live Demo

The system has **role-based access**. Explore it as Admin, then try the Doctor view:

**1. Enter as Admin →** **[Open the Admin panel](https://lubna-ibrahim-ahmed.github.io/hospital-pharmacy-website/Admin.html)**
Full access: dashboard, inventory, sales, reports, and **Manage Doctors** (create/edit/delete accounts).

**2. Create a Doctor account** on the Manage Doctors page — any username and password you like.

**3. Switch to the Doctor view** — use the profile icon (top-right) to log out, then log in with the
account you just created to see the standard Doctor access.

> **Inventory data:** On the inventory page, use the import button to upload the included
> `pharmacy_inventory.xlsx` file to populate the table.
---

## Features

### Authentication & User Management
- Pharmacist/doctor login system
- Admin access with additional privileges
- Account creation for pharmacists by admin
- Edit and delete pharmacist accounts
- Login/logout functionality
- Role-based access simulation

### Dashboard
- Summary cards displaying:
  - Total sales
  - Total profit
  - Expired medicines
  - Low stock medicines
- Warning and alert sections
- Navigation top bar
- Footer containing hospital information

### Inventory Management
- Search medicines by name
- Add medicines to inventory
- Update stock quantities
- Inventory tracking system
- Load medicine inventory from an Excel file using SheetJS
- Export as an Excel file
- Low stock and expiry alerts

### Point of Sale (POS)
- Search medicines
- Add medicines to cart
- Quantity selection
- Payment method selection
- Receipt generation
- Automatic stock reduction after sales
- Refund processing, validated against the original sale before approval

### Reports
- Sales transaction reports
- Inventory reports
- Expired medicine reports
- Data tables for tracking pharmacy operations
- Sales summary: total sales, profit, and quantity sold
- Print reports or export them to CSV

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Icons Libraries
- Git & GitHub for collaboration and version control
- SheetJS (xlsx) — reading and exporting Excel (.xlsx) data

---

## Challenges Faced

- Integrating features developed across multiple files and modules
- Managing project collaboration using GitHub
- Maintaining UI consistency across pages
- Simulating authentication and role management using front-end technologies only
- Coordinating interactions between inventory, POS, and reporting systems

---

## Learning Outcomes

Through this project, the team gained practical experience in:

- Front-end web development
- DOM manipulation using JavaScript
- Role-based workflow simulation
- Local storage concepts
- UI/UX organization
- GitHub collaboration and version control
- Team-based software development

---

### Managing Accounts Page
<img width="1600" height="761" alt="WebsiteImg6" src="https://github.com/user-attachments/assets/97a098e5-1e1e-405b-af8f-090343fa818d" />

### Login Page
<img width="1600" height="756" alt="WebsiteImg5" src="https://github.com/user-attachments/assets/e9b346b0-c3be-4027-8491-826071d9d968" />

### Dashboard Page
<img width="1600" height="755" alt="WebsiteImg1" src="https://github.com/user-attachments/assets/32bb050a-102e-41b9-bf1d-e7c541c4cfea" />

### Admin Dashboard Page
<img width="1600" height="761" alt="WebsiteImg7" src="https://github.com/user-attachments/assets/83492654-a251-4da0-8da8-ec561103dde5" />

### POS Page
<img width="1600" height="758" alt="WebsiteImg2" src="https://github.com/user-attachments/assets/899fbb6e-0aa4-40cc-a021-0be84685dda8" />

### Receipt Making Page
<img width="1600" height="764" alt="WebsiteImg3" src="https://github.com/user-attachments/assets/d8383167-fdae-4b31-87c1-1789fa818d" />

### Inventory Management Page
<img width="1901" height="919" alt="Screenshot 2026-06-09 002607" src="https://github.com/user-attachments/assets/c3378857-5800-411b-a360-9a3b333f79a8" />
<img width="1902" height="921" alt="Screenshot 2026-06-09 002631" src="https://github.com/user-attachments/assets/ac72f87e-7302-4ee6-8a5a-45f8a14d2530" />

---

## Authors and Workload

| Team Member             | Responsibilities                                                                                                                                                                      |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Yahia Ahmed Shaheen** | Developed the complete authentication system including login/logout functionality, admin pages, doctor account creation, account editing/deleting logic, and user management workflow |
| **Maya Ramy Essam**     | Developed dashboard components including summary cards, alerts, navigation bar, and dashboard UI                                                                                      |
| **Lubna Ibrahim**       | Developed Point of Sale (POS) features including cart system, payment workflow, receipt generation, medicine sales logic, expiry and refund logic, and database logic (SheetJS)       |
| **Amena Tamer**         | Developed reports pages and transaction history tables, summary cards, print, and CSV export                                                                                         |
| **Mariam Amr**          | Developed inventory management features including medicine search, stock quantity handling, and batch tracking                                                                        |

---
