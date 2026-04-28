# 🚀 PIWA – Platform for Integrated Workflow Automation

PIWA is an AI-powered, WhatsApp-first customer engagement platform that enables businesses to automate conversations, capture leads, and streamline workflows using AI.

---

## 📌 Problem

Businesses struggle to manage customer conversations across platforms like WhatsApp.  
Most interactions are manual, slow, and unstructured, leading to:
- Missed leads  
- Delayed responses  
- Poor customer experience  

At the same time, implementing AI-driven automation is complex and expensive.

---

## 💡 Solution

PIWA provides a unified platform to:
- Automate customer conversations using AI  
- Manage WhatsApp interactions in real time  
- Build intelligent workflows for lead capture and support  

---

## 🧩 Key Features

- 📲 WhatsApp Cloud API Integration  
- 🤖 AI-powered automated responses  
- 🔄 Workflow automation (lead capture, support flows)  
- 📊 Centralized dashboard for conversation tracking  
- ⚡ Real-time messaging and processing  

---

## 🛠️ Tech Stack

- **Backend:** Laravel (PHP)  
- **Frontend:** Blade + JavaScript  
- **Database:** MySQL  
- **Server:** AWS EC2 (Ubuntu 24.04)  
- **Web Server:** Nginx + PHP-FPM  
- **Integrations:** WhatsApp Cloud API  
- **AI Layer:** LLM-based automation  

---

## 🏗️ Architecture Overview

PIWA follows a modular, API-driven architecture:

- Webhooks handle incoming WhatsApp messages  
- AI engine processes user intent and triggers workflows  
- Queue system ensures asynchronous processing  
- Dashboard provides real-time visibility  

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/Sumeet391/piwa.git
cd piwa

# Install dependencies
composer install

# Setup environment
cp .env.example .env
php artisan key:generate

# Configure database in .env
php artisan migrate

# Start server
php artisan serve
