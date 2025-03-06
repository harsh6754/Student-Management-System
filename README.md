# 🎓 Student Management System (SMS)

The **Student Management System (SMS)** is an enterprise-level application designed to streamline student-related operations in educational institutions. It provides a robust solution for managing student records, academic performance, and communication between students, faculty, and administration.

## 🚀 Features

✅ **Student Enrollment & Management** – Register students, store personal and academic details, and manage course assignments.  
✅ **Course & Class Scheduling** – Create, update, and manage course schedules and timetables.  
✅ **Attendance Tracking** – Automate attendance records with real-time updates and absence notifications.  
✅ **Grade & Performance Monitoring** – Calculate grades, generate report cards, and provide academic performance analytics.  
✅ **Fee & Payment Management** – Track tuition payments, generate invoices, and manage financial transactions.  
✅ **Teacher & Staff Management** – Maintain faculty records, assign courses, and monitor staff performance.  
✅ **Communication System** – Integrated messaging and notifications via **RabbitMQ**.  
✅ **Reports & Analytics** – **Kibana & ElasticSearch** for student performance, attendance, and financial data visualization.  
✅ **Real-Time Data Processing** – Uses **Redis** for caching and **RabbitMQ** for asynchronous message processing.  
✅ **Scalability & Security** – **PostgreSQL** as the database with secure authentication mechanisms.  

---

## 🛠️ Tech Stack

| Component  | Technology Used |
|------------|----------------|
| **Frontend** | ASP.NET Core MVC, Kendo UI |
| **Backend** | ASP.NET Web API (RESTful architecture) |
| **Database** | PostgreSQL |
| **Caching** | Redis |
| **Search & Analytics** | ElasticSearch + Kibana |
| **Messaging Queue** | RabbitMQ |
| **Deployment** | Docker, Kubernetes |

---

## 🏗️ System Architecture


+----------------------+ +----------------------+ | ASP.NET Core MVC | ----> | ASP.NET Web API | | (Frontend) | | (Backend) | +----------------------+ +----------------------+ | | | | v v +----------------------+ +----------------------+ | PostgreSQL Database | | Redis Cache | +----------------------+ +----------------------+ | | v v +----------------------+ +----------------------+ | ElasticSearch | ----> | Kibana Dashboard | +----------------------+ +----------------------+ | v +----------------------+ | RabbitMQ Messaging | +----------------------+



---

## 📦 Installation & Setup

### **1️⃣ Prerequisites**
Make sure you have the following installed:

- [.NET SDK 8.0+](https://dotnet.microsoft.com/en-us/download)
- [Docker](https://www.docker.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [Redis](https://redis.io/)
- [ElasticSearch](https://www.elastic.co/)
- [RabbitMQ](https://www.rabbitmq.com/)

---

### **2️⃣ Clone the Repository**
```sh
git clone https://github.com/harsh6754/Student-Management-System.git
cd Student-Management-System

