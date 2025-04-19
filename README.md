
# 👗 Fashion E-commerce Website

An intelligent and user-friendly online shopping platform for fashion products. Built with Spring MVC and SQL Server, the system supports multiple user roles and integrates advanced features like image-based product search and collaborative filtering recommendations.

---

<!--## 🌐 Live Demo

_Deploying soon..._

--->

## 📌 Features

### 👤 Role-Based System
- **Guest**: View and filter products, register for an account.
- **Customer**: Full shopping functionality — manage profile, wishlist, shopping cart, place orders, review products.
- **Staff**: Manage products, categories, brands, orders, and customer accounts.
- **Admin**: All staff privileges + manage employee accounts.

### 🧠 Smart Functionalities
- **🖼️ Image-Based Search**  
  Upload an image to search for similar products using VGG16 (CNN-based visual similarity).

- **📊 Collaborative Filtering Recommendations**  
  Suggests products based on customer purchase history using item-item similarity metrics.

- **🛒 Cart & Wishlist Management**  
  Add/remove/update items with real-time feedback.

- **🔐 Secure Authentication**  
  OTP-based email verification for signup and password recovery.

---

## 🏗️ System Architecture

- **3-tier architecture**:  
  - **Presentation Layer**: JSP + HTML/CSS/JavaScript  
  - **Business Logic Layer**: Spring MVC  
  - **Data Layer**: SQL Server

---

## 🛠️ Tech Stack

| Layer              | Technology                              |
|-------------------|------------------------------------------|
| Backend            | Java, Spring MVC                        |
| Frontend           | JSP, HTML, CSS, JavaScript, Bootstrap   |
| Database           | Microsoft SQL Server                    |
| Machine Learning   | Python, TensorFlow (VGG16)              |
| Tools              | Eclipse             |

---

## 🚀 Getting Started

### Prerequisites
- Java JDK 11+
- Apache Tomcat 9+
- SQL Server
- Maven
- Python 3.8+ (for ML module)


