#  Full-Stack Shopping App (React + .NET + NestJS + AWS)

##  Overview
This repository contains a full-stack shopping application built as part of a cloud-based architecture assignment.  
It includes a product catalog, shopping cart functionality, and order submission with cloud deployment design.

---

##  Tech Stack

### Frontend
- React (JavaScript)
- Redux Toolkit
- React Router
- Bootstrap

### Backend 1 – Product & Category Management
- ASP.NET Core 8 Web API
- SQL Server via Entity Framework Core
- Clean Architecture

### Backend 2 – Order Submission
- NestJS (Node.js)
- Elasticsearch (via AWS OpenSearch)

### DevOps & Cloud
- AWS S3 & CloudFront (Frontend hosting)
- AWS EC2 or ECS (Backend deployment)
- RDS (SQL Server)
- AWS OpenSearch (Order storage)
- CloudWatch, IAM, Secrets Manager

---

## Features

- Browse categories and products
- Add products to cart
- Submit an order with form data
- Save order to Elasticsearch
- Optimized cloud-ready architecture
- DevOps strategy with security, monitoring, and scalability

---

## Project Structure
/client/ → React frontend (Screen 1)
/order-backend/ → NestJS backend for orders (Screen 2)
/... → .NET solution with Clean Architecture for product/category API
AWS_Architecture.docx → Word document with cloud design and DevOps explanation and AWS system diagram

## Getting Started

1. **Download the ZIP** file from this repository
2. **Extract** it on your machine
3. Open `/client/` in VS Code or browser to explore the frontend  
4. Open `/order-backend/` for the NestJS API  
5. Open the `.NET solution` folder (contains multiple projects) in Visual Studio

---

##  Cloud & DevOps (Part 2)

All required documentation is included in:
- `Cloud Architecture For ShoppingApi.docx`: Cloud architecture, component roles, DevOps practices
- `mapping.json`: Mapping file for the elasticsearch

---

## Requirements Checklist

-  React + Redux Toolkit frontend
-  .NET 8 Web API backend
-  NestJS + Elasticsearch order backend
-  AWS DevOps design document including an architecture diagram
-  Project packaged in downloadable zip

---



