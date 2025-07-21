# QR Generator Manager

A Blazor Server web app to generate, view, store, and manage QR codes for various data types including WiFi, email, phone numbers, and generic text.

## 🚀 Features

- Generate QR codes with custom payloads
- Search, filter, and view saved QR codes
- Download QR codes as PNG files
- Batch delete QR entries
- Light/Dark mode with persistent theme

## 🛠️ Tech Stack

- **Blazor Server (.NET 7)**
- **C#** with **Entity Framework Core**
- **SQL Server**
- **QRCoder** library for QR code generation
- **JavaScript Interop** for theming

## 📁 Structure

- `Models/` – Data classes & enums  
- `Services/` – QR logic & theme handling  
- `Data/` – EF DbContext & migrations  
- `Pages/` – Razor components (UI)  
- `wwwroot/` – Static files and scripts  

## ⚙️ Setup

- Configure DB in `appsettings.json`
- Run EF Core migrations
- Build & run the app with `dotnet run`


