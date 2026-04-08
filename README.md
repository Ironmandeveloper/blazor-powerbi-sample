# Blazor + Power BI Embedded Sample

This repository contains a working example of embedding Power BI reports inside a Blazor application using the app-owns-data approach.

## 📁 Contents
- docs/ → Project documentation (DOCX)
- source/ → Full Blazor sample project (ZIP)

## 🚀 Features
- Secure embed token generation (server-side)
- Power BI REST API integration
- Blazor + JavaScript interop for report rendering
- Scalable architecture for SaaS / multi-tenant apps

## ⚙️ Setup Instructions
1. Download the ZIP file from the `source/` folder
2. Extract and open in Visual Studio
3. Update `appsettings.json` with your Power BI credentials:
   - TenantId
   - ClientId
   - ClientSecret
   - WorkspaceId
   - ReportId
4. Run the application

## 🔐 Security Note
Credentials are not included in this repository. Please use your own Power BI service principal configuration.

## 📌 Use Case
This project demonstrates how to embed Power BI dashboards into custom web applications for internal tools or client-facing SaaS platforms.
