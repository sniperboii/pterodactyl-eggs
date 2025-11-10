# Pterodactyl Eggs

A collection of ready-to-use Pterodactyl eggs for hosting web apps and tools.

---

## 🧩 Overview

These eggs let you deploy and manage different applications inside your Pterodactyl panel with minimal setup.  
Each egg is optimized for fast deployment and stable performance.

---

## 📦 Available Eggs

| Egg Name | Description | Status |
|-----------|--------------|---------|
| [**React Website**](./react-website/egg.json) | Host any React app easily inside your Pterodactyl panel. | ✅ Released |
| **PHP** | Simple Apache + PHP hosting environment. | 🔧 Coming Soon |
| **WordPress** | Full WordPress setup with database support. | 🔧 Coming Soon |

---

## ⚙️ React Website Egg

**Description**  
Host your React app directly in Pterodactyl.  
It builds automatically and serves compiled static files.

**Features**
- Auto `npm install` and `npm run build`  
- Static files served from `/var/www/html`  
- Lightweight Node environment  

---

## 📂 Directory Structure
```
pterodactyl-eggs/
│
├── react-website/
│ └── egg.json
└── README.md
```

---

## 🧠 How to Import an Egg

1. Go to your **Pterodactyl Admin Panel**
2. Open **Nests → Import Egg**
3. Upload the egg JSON file from this repository
4. Create your server using the imported egg

---

## 💬 Community & Support

[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?logo=discord&logoColor=white)](https://gg.snexon.studio)

Join our Discord community for support, updates, and discussions.
---

## ⚖️ License

This project is licensed under the **MIT License**.  
You are free to use, modify, and share it with credit.


