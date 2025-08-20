# 📊 Receipt Tracker – Personal CPI Index

Track your personal spending and inflation by uploading receipts, extracting data via OCR, and analyzing changes against your own Consumer Price Index (CPI).

---

## 🚀 Project Overview
This project aims to:
- Allow users to **upload receipts** (images or PDFs).
- Use **OCR (Optical Character Recognition)** to extract text such as dates, items, and prices.
- Store data securely with **user authentication**.
- Provide **dashboards and analytics** to track inflation trends over time.
- Deploy on a **public cloud** using infrastructure as code.

---

## 🏗️ Tech Stack (Planned)
- **Frontend (UI):** React + Tailwind CSS  
- **Backend:** Node.js (Express) / Java (Spring Boot) *(TBD)*  
- **Database:** PostgreSQL or MongoDB  
- **Authentication:** JWT or Firebase Auth  
- **File Storage:** AWS S3 / Cloud Storage  
- **OCR:** Tesseract.js or Google Vision API  
- **Deployment:** Docker + AWS/GCP + Terraform  

---

## 📂 Project Structure (Planned)
```

receipt-tracker/
├── frontend/          # React UI
│   ├── src/
│   └── package.json
├── backend/           # API server (Express or Spring Boot)
│   ├── src/
│   └── package.json or pom.xml
├── infra/             # Infrastructure as code (Terraform, Docker)
├── docs/              # Documentation, diagrams
└── README.md

````

---

## 🎯 Features (Work in Progress)
- [ ] User registration & login  
- [ ] Upload receipts (image/pdf)  
- [ ] OCR to extract data  
- [ ] Store receipts & metadata in database  
- [ ] Dashboard with analytics (spending trends, CPI)  
- [ ] Cloud deployment with Infrastructure as Code  

---

## ⚡ Getting Started (Frontend – WIP)
1. Clone the repo:  
   ```bash
   git clone https://github.com/YOUR-USERNAME/receipt-tracker.git
   cd receipt-tracker/frontend
   ````

2. Install dependencies:

   ```bash
   npm install
   ```
3. Run the development server:

   ```bash
   npm run dev
   ```

---

## 📌 Roadmap

* **Phase 1**: Basic React UI (upload + list receipts)
* **Phase 2**: Backend API + database integration
* **Phase 3**: Authentication system
* **Phase 4**: OCR integration
* **Phase 5**: Analytics dashboard
* **Phase 6**: Cloud deployment (Docker + Terraform)

---

## 🤝 Contributing

This is a personal learning project, but contributions are welcome.
Please fork the repo and open a pull request with your changes.

---

## 👤 Author

Developed by **Aqilla** ✨

---
