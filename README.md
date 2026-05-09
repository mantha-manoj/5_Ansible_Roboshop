# 🛒 Roboshop Automation using Ansible

This repository contains Ansible playbooks and roles to automate the deployment of the **Roboshop E-commerce Microservices Application**.

The project helps in provisioning and configuring multiple services automatically using **Ansible**, reducing manual server setup effort and ensuring repeatable deployments.

---

## 🚀 Project Overview

Roboshop is a microservices-based e-commerce application with 12+ services.

Using this project, you can automate:

- Server configuration
- Package installation
- Application deployment
- Database setup
- Service configuration
- Systemd service management

---

## 🧰 Tech Stack

- **Ansible**
- **Linux**
- **YAML**
- **AWS EC2**
- **MongoDB**
- **MySQL**
- **Redis**
- **RabbitMQ**
- **NodeJS**
- **Python**
- **Maven**
- **Nginx**

---

## 📂 Repository Structure

```bash
5_Ansible_Roboshop/
│
├── roles/
│   ├── cart/
│   ├── catalogue/
│   ├── user/
│   ├── payment/
│   ├── shipping/
│   ├── frontend/
│   ├── mongodb/
│   ├── mysql/
│   ├── redis/
│   ├── rabbitmq/
│   └── dispatch/
│
├── group_vars/
├── host_vars/
├── inventory.ini
├── roboshop.yml
└── README.md
```

---

## ⚙️ Features

✅ Modular role-based Ansible structure  
✅ Reusable playbooks  
✅ Inventory-based server management  
✅ Variable management with group_vars and host_vars  
✅ Automated microservices deployment  
✅ Easy scaling and maintenance  

---

## 📌 Services Automated

- Frontend
- Catalogue
- User
- Cart
- Shipping
- Payment
- Dispatch
- MongoDB
- MySQL
- Redis
- RabbitMQ

---

## ▶️ How to Run

### 1. Clone Repository

```bash
git clone https://github.com/mantha-manoj/5_Ansible_Roboshop.git
cd 5_Ansible_Roboshop
```

### 2. Configure Inventory

Update `inventory.ini` with your server IP addresses.

Example:

```ini
[frontend]
frontend.example.com

[mongodb]
mongodb.example.com
```

### 3. Run Playbook

```bash
ansible-playbook -i inventory.ini roboshop.yml
```

---

## 📚 What I Learned

Through this project, I learned:

- Ansible Playbooks
- Roles
- Inventory Management
- Variables
- Templates
- Handlers
- Service automation
- Infrastructure configuration management

---

## 🎯 Use Case

This project is useful for:

- DevOps Engineers
- Automation Engineers
- Infrastructure Automation Learning
- Ansible Beginners to Advanced Practice

---

## 👨‍💻 Author

**Manoj Mantha**

- GitHub: https://github.com/mantha-manoj
- LinkedIn: https://www.linkedin.com/in/manoj-mantha/

---

## ⭐ Support

If you found this project useful, give it a **star ⭐** on GitHub.