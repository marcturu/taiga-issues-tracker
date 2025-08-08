# ⚠️ ASW-Project — Taiga Issues-like Tracker Web  

<sub>🗓️ Developed in April 2023</sup>  

This project aims to replicate the main functionalities of the **[Taiga Issues Page](https://tree.taiga.io/project/taiga/issues)** in a Rails 7 web application.

---

## ✅ Features

- Basic Rails 7 app with user login and Google OAuth authentication.
- REST API documented and testable with OpenAPI/Swagger.
- Local development with rails s or rails server -b 0.0.0.0.
- Issue creation with search flters.
- Comments and watchers addition to issues.

---

## 🛠 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/marcturu/ASW-Project.git
cd ASW-Project
```

### 2. Install dependencies  
```bash
bundle install
```

### 3. Setup environment variables  
Create a .env file in the project root with:  
```ini
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```
 > **Note:**  
 > Get your Google OAuth credentials from your [Google Cloud Console](https://console.cloud.google.com/).

### 4. Setup the database  
```bash
rails db:create
rails db:migrate
rails db:seed # optional if seed data is included
```

### 5. Run the Rails server  
Visually:
```bash
rails s
```
Via API endpoints in the **[Swagger Editor](https://editor.swagger.io/)** with the OpenAPI specification from `/api/api.yaml` and the API key generated from the profile page (if applicable):
```bash
rails server -b 0.0.0.0
```
Access the app at http://localhost:3000.  

---

## 📷 Screenshots  

### Main Page:
![9e47892e-32a3-4137-a22f-e85f946a01db (1) copia](https://github.com/marcturu/ASW-Project/assets/90869159/573a6c85-9f28-47bc-a164-4dd2bf9cdcba)  
![9e47892e-32a3-4137-a22f-e85f946a01db (1)](https://github.com/marcturu/ASW-Project/assets/90869159/bc3decbd-9922-4d18-9cd5-fbfc8d84d91c)    
-
### Profile Page:
![Captura de pantalla 2025-08-07 180259](https://github.com/user-attachments/assets/fac37a49-3cd8-4c6f-bc11-663df987dc20)
-
### Create Issue Page:
![Captura de pantalla 2025-08-07 175614](https://github.com/user-attachments/assets/98d347dc-f079-43e7-84e8-c79288f1dd51)
-
![Captura de pantalla 2025-08-07 184422](https://github.com/user-attachments/assets/73301200-9cdb-4445-97cd-4a8705d23256)
-
![Captura de pantalla 2025-08-07 175752](https://github.com/user-attachments/assets/2eb6ead1-0c2b-42d5-b6a5-2fe83757ced7)
-
![Captura de pantalla 2025-08-07 180205](https://github.com/user-attachments/assets/c2ccb663-bc38-433e-aefb-2f20c870e154)
-
### API calls (Swagger):  
![Captura de pantalla 2025-08-07 174604](https://github.com/user-attachments/assets/f3746377-4e1b-4887-95f3-b5195b0d0ae4)
-
### Taiga Project Timeline:
![Captura de pantalla 2025-08-07 174846](https://github.com/user-attachments/assets/0d60efe3-59d0-4862-8d53-cc284dced361)

---

## 👥 Authors

- SERGIO GUERRERO   
- JOEL RIVERA  
- ALBA MARIA SERVER  
- MARC TURU ROCA
