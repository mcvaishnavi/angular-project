# Device Management Dashboard

A complete web-based dashboard designed to manage and track multiple categories of devices including **BYOD**, **Mobile**, **Servers**, and **Developer Devices**.  
This project provides a clean interface, admin controls, audit logs, and dynamic tables powered by DataTables, making it suitable for enterprise, organizational, or academic use.

---

## 🎯 Overview

The Device Management Dashboard allows administrators and developers to:

- Add, update, and delete devices  
- View categorized device inventories  
- Manage user access and admin operations  
- Track activities through audit logs  
- Use API-based JavaScript modules for all data operations  
- Leverage DataTables for sorting, searching, and pagination  

All pages are built using **HTML**, **CSS**, and **JavaScript**, making the project fully browser-ready without any build steps.

---

## 🧩 Key Features

### **Device Management**
- Add BYOD, Server, Mobile, or Developer devices  
- View detailed inventory tables  
- Edit or remove device entries  

### **Admin Panel**
- Separate admin dashboard for managing all device categories  
- Pages include:
  - `adminByod.html`
  - `adminMobile.html`
  - `adminServer.html`

### **Developer Panels**
- Developer-level views for:
  - BYOD (`devByod.html`)
  - Mobile (`devMobile.html`)
  - Servers (`devServer.html`)

### **Integrated Audit Logging**
- `audit.html` provides record tracking for administrative actions.

### **Authentication**
- Basic login and signup pages included (`login.html`, `signup.html`).

### **API-Driven JavaScript Modules**
Located in `/js`:
- `apibyod.js`
- `apimobile.js`
- `apiserver.js`
- `apidev.js`

These handle CRUD operations and backend communication.

### **DataTables Integration**
- Full DataTables 1.12.1 library included  
- Supports sorting, filtering, pagination, and multiple UI themes  
