<h1 align="center">
  FPTBook 📚
</h1>

<p align="center">
  <strong>A cutting-edge e-commerce platform reinventing the book-selling and inventory management process.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/.NET_MVC-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET MVC" />
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" />
  <img src="https://img.shields.io/badge/HTML5_%26_CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML & CSS" />
</p>

---

## 📖 About The Project

> Simplifying inventory management for store owners while providing a welcoming and seamless purchasing experience for book lovers.

**FPTBook** is a comprehensive e-commerce system designed to bridge the gap between customers and book store owners. It empowers customers with the freedom to browse a large selection of books, make simple and secure purchases, and manage their personal profiles and order histories. 

Simultaneously, FPTBook acts as a powerful operational tool for Store Owners, simplifying inventory management through intuitive product CRUD (Create, Read, Update, Delete) operations and automated category requests. The platform significantly increases sales productivity, eases customer administration, and enhances the overall interaction between store managers and their clientele.

---

## ✨ Key Features & User Roles

FPTBook operates with tailored experiences for three primary user roles, ensuring secure and efficient interactions across the platform.

| Role | Responsibilities & Features |
| :--- | :--- |
| **🛡️ Admin** | **System & Account Management:** Full control over user accounts (Create, Edit, Delete, Change Passwords) for both Customers and Store Owners.<br>**Content Moderation:** Review, approve, or reject new book category requests submitted by Store Owners. |
| **🏪 Store Owner** | **Inventory Management:** Add new books, update pricing/details, and remove outdated inventory.<br>**Category Requests:** Submit requests for new book categories to the Admin.<br>**Order Fulfillment:** Manage incoming customer orders and update order statuses (Accept/Reject). |
| **🛍️ Customer** | **Discovery & Shopping:** Browse, search, sort, and filter books by category. Manage shopping cart and proceed to secure checkout.<br>**Account Management:** Update personal profile, change passwords, and track detailed order history. |

---

## 🛠️ Technology Stack

- **Architecture:** ASP.NET MVC
- **Front-End:** HTML5, CSS3, Bootstrap (Responsive Design)
- **Interactivity:** jQuery & AJAX
- **Alerts & UI Components:** SweetAlert (for seamless user notifications)

---

## 🏗️ System Architecture

### 1. Entity-Relationship Diagram (ERD)
*Outlines the database schema, mapping the relationships between Users, Books, Categories, Orders, and Order Details.*
<p align="center">
  <img width="780" height="1135" alt="image" src="https://github.com/user-attachments/assets/aad865b1-b6e2-4861-97ed-31e4269188fb" />
</p>

### 2. Use Case Diagram
*Visualizes the functional interactions and permission boundaries between Admins, Store Owners, Customers, and Guests.*
<p align="center">
 <img width="924" height="1194" alt="image" src="https://github.com/user-attachments/assets/fec4231a-0e86-4c30-b330-584d14eb8922" />
</p>

---

## 📸 User Interface Showcase

*A visual tour of the FPTBook platform, highlighting key functionalities across different user roles.*

### 🌟 Core Experience & Navigation
<table align="center">
  <tr>
    <td align="center" width="50%">
       <img width="1044" height="494" alt="image" src="https://github.com/user-attachments/assets/37374394-f266-4b94-8fd8-cbc879c1e47c" />
      <br/><b>Home Page</b>
    </td>
    <td align="center" width="50%">
       <img width="716" height="388" alt="image" src="https://github.com/user-attachments/assets/7f0e5c05-5e5c-431f-8177-d5be45c5eb7d" />
      <br/><b>Help & FAQ Screen</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="1044" height="315" alt="image" src="https://github.com/user-attachments/assets/fca62a00-fd76-46fe-9455-d659e3cea8ed" />
      <br/><b>Desktop & Tablet Navigation</b>
    </td>
    <td align="center" width="50%">
      <img width="624" height="485" alt="image" src="https://github.com/user-attachments/assets/b5d5b391-1a9e-4f40-9ba5-e3e22ccfafd5" />
      <br/><b>Mobile Sidebar Navigation</b>
    </td>
  </tr>
</table>

### 🔍 Book Discovery
<table align="center">
  <tr>
    <td align="center" width="50%">
       <img width="958" height="495" alt="image" src="https://github.com/user-attachments/assets/334d9a98-bee2-4adc-bf1e-c7f2b2ef28f6" />
      <br/><b>Filter Books By Category</b>
    </td>
    <td align="center" width="50%">
      <img width="932" height="281" alt="image" src="https://github.com/user-attachments/assets/bf0e1ef8-ee6f-4996-b1dd-d3286b5184a4" />
      <br/><b>List Pagination</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="892" height="412" alt="image" src="https://github.com/user-attachments/assets/bfcfc10a-6836-426a-bf0c-2fdbfee0b8d7" />
      <br/><b>Sorting Functionality</b>
    </td>
    <td align="center" width="50%">
      <img width="675" height="478" alt="image" src="https://github.com/user-attachments/assets/c9c4b1ca-bb7a-456d-898b-6e674a718a17" />
      <br/><b>Global Book Search</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="100%" colspan="2">
      <img width="763" height="529" alt="image" src="https://github.com/user-attachments/assets/85e2f111-61c2-4949-9cd3-3e4d65ca855d" />
      <br/><b>Combined Advanced Filtering & Sorting</b>
    </td>
  </tr>
</table>

### 🛒 Shopping & Checkout (Customer)
<table align="center">
  <tr>
    <td align="center" width="50%">
    <img width="826" height="443" alt="image" src="https://github.com/user-attachments/assets/a4c48af5-fc8e-4d71-83f3-bfc75cf5a714" />
      <br/><b>Book Details Screen</b>
    </td>
    <td align="center" width="50%">
  <img width="1044" height="490" alt="image" src="https://github.com/user-attachments/assets/6b3c8434-a2f8-49d4-97ae-61f490a62ad0" />
      <br/><b>Shopping Cart Management</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
    <img width="1044" height="557" alt="image" src="https://github.com/user-attachments/assets/56ce9db9-88a2-497d-95fb-2817a45f08bc" />
      <br/><b>Cart Item Actions (Increase/Decrease/Remove)</b>
    </td>
    <td align="center" width="50%">
      <img width="1044" height="562" alt="image" src="https://github.com/user-attachments/assets/9c82ed66-d15d-44f1-b96a-efd042d347c2" />
      <br/><b>Secure Checkout Processing</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="1044" height="486" alt="image" src="https://github.com/user-attachments/assets/18f14559-febe-4cc9-8f20-5f4e431c1458" />
      <br/><b>Customer Order History</b>
    </td>
    <td align="center" width="50%">
   <img width="1044" height="450" alt="image" src="https://github.com/user-attachments/assets/d49e976b-6fbe-4f16-8a9a-b0350152b00b" />
      <br/><b>Detailed Order Invoice</b>
    </td>
  </tr>
</table>

### 🏪 Store Owner Dashboard
<table align="center">
  <tr>
    <td align="center" width="50%">
     <img width="481" height="678" alt="image" src="https://github.com/user-attachments/assets/761dd0a3-e9e3-4417-85d0-b2cdca99e9d0" />
      <br/><b>Add New Book Form</b>
    </td>
    <td align="center" width="50%">
     <img width="949" height="262" alt="image" src="https://github.com/user-attachments/assets/71336ce1-34f9-4bc0-999c-14a8a19e94a5" />
      <br/><b>Edit Existing Book Details</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="1019" height="322" alt="image" src="https://github.com/user-attachments/assets/1188a4af-b61c-40e2-9542-1e7699e135fe" />
      <br/><b>Delete Book & Confirmation Alert</b>
    </td>
    <td align="center" width="50%">
     <img width="381" height="425" alt="image" src="https://github.com/user-attachments/assets/abb95f68-d376-4a9a-ac3d-f2c55eb4da29" />
      <br/><b>Submit Category Request to Admin</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img width="1044" height="429" alt="image" src="https://github.com/user-attachments/assets/997fbe25-8d9c-4938-858f-44cc0fefee21" />
      <br/><b>Store Owner: Manage Customer Orders</b>
    </td>
    <td align="center" width="50%">
      <img width="1044" height="355" alt="image" src="https://github.com/user-attachments/assets/11c7471f-10e6-436e-9cc0-47ed1f3b7f88" />
      <br/><b>Update Status (Accept/Reject Order)</b>
    </td>
  </tr>
</table>

### 🛡️ Admin Control Panel
<table align="center">
  <tr>
    <td align="center" width="50%">
      <img width="819" height="365" alt="image" src="https://github.com/user-attachments/assets/80fde040-d343-4a96-8898-86e3fecafb7d" />
      <br/><b>User Management Dashboard</b>
    </td>
    <td align="center" width="50%">
   <img width="506" height="518" alt="image" src="https://github.com/user-attachments/assets/8afbeda4-e96d-4ad1-bad9-87275a5e7d9c" />
      <br/><b>Create User Form</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="671" height="204" alt="image" src="https://github.com/user-attachments/assets/8fdd6bef-1bde-4446-b0de-26286ae75143" />
      <br/><b>Edit User Info & Role</b>
    </td>
    <td align="center" width="50%">
 <img width="340" height="379" alt="image" src="https://github.com/user-attachments/assets/6104cb51-c779-4dcb-a38e-50c2df56defb" />
      <br/><b>Admin: Change User Password</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
     <img width="928" height="368" alt="image" src="https://github.com/user-attachments/assets/7dfa81a3-01da-40ad-9f44-6db8049ef6f4" />
      <br/><b>Manage Pending Category Requests</b>
    </td>
    <td align="center" width="50%">
    <img src="https://placehold.co/600x400/2A2A2A/FFFFFF/png?text=Approve%2FReject+Categories" alt="Approve/Reject Categories" width="100%"/>
      <img width="530" height="154" alt="image" src="https://github.com/user-attachments/assets/de7869f8-2aed-46a6-8605-588b0e0f4c45" />
    </td>
  </tr>
</table>

### 🔐 Authentication & Profile Management
<table align="center">
  <tr>
    <td align="center" width="50%">
        <img width="518" height="598" alt="image" src="https://github.com/user-attachments/assets/c01eb96e-d4ff-43e0-93e7-bde3cd7b9f23" />
      <br/><b>Register Account</b>
    </td>
    <td align="center" width="50%">
    <img width="565" height="456" alt="image" src="https://github.com/user-attachments/assets/f4c8e434-4d73-4b2c-88e5-893da9d3c3cf" />
      <br/><b>Login Screen</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
       <img width="598" height="385" alt="image" src="https://github.com/user-attachments/assets/cfa893c7-ee4c-4fda-b041-b5cd212e7a13" />
      <br/><b>Display Profile Information</b>
    </td>
    <td align="center" width="50%">
    <img width="505" height="443" alt="image" src="https://github.com/user-attachments/assets/a155c018-ab7d-4ff9-8773-d88f33ab9f83" />
      <br/><b>Change Password</b>
    </td>
  </tr>
</table>

---

## 🚀 Getting Started

To explore the codebase or run FPTBook locally, clone the repository:

```bash
git clone https://github.com/khangln2111/Greenwich-1670-ApplicationDevelopment-BookStoreMVC
