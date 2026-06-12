# 🎬 Media Streaming Platform — IBM Cloud

![IBM Cloud](https://img.shields.io/badge/IBM%20Cloud-Hosted-blue?style=for-the-badge&logo=ibm)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)
![HTML5](https://img.shields.io/badge/HTML5-Responsive-orange?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-Styled-blue?style=for-the-badge&logo=css3)

A cloud-hosted media streaming platform prototype built on IBM Cloud supporting live and on-demand video streaming, file uploads, and role-based user access control.

---

## 🚀 Features

- ✅ Live and recorded video streaming support
- ✅ Media file upload and management
- ✅ Role-based user access control (Admin / Viewer)
- ✅ IBM Cloud Object Storage integration for media assets
- ✅ Responsive UI — works on desktop and mobile
- ✅ User session management and authentication

---

## 🏗️ Architecture

```
User Browser
    ↓
Frontend (HTML5 + CSS3 + JavaScript)
    ↓
IBM Cloud App Server
    ↓
IBM Cloud Object Storage (Media Files)
    ↓
User Access Control Layer
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 | Frontend structure and styling |
| JavaScript (ES6+) | Client-side interactivity |
| IBM Cloud | Cloud hosting and deployment |
| IBM Cloud Object Storage | Media file storage and retrieval |
| IBM Cloud APIs | Storage management and access |

---

## ⚙️ Setup & Deployment

```bash
# Clone the repository
git clone https://github.com/DhanushMasanam/media-streaming-platform.git
cd media-streaming-platform

# Configure IBM Cloud credentials
cp config.example.js config.js
# Add your IBM Cloud API key and bucket details in config.js

# Open in browser
open index.html
```

---

## 🔑 IBM Cloud Configuration

```javascript
// config.js
const IBM_CONFIG = {
  apiKey: "YOUR_IBM_API_KEY",
  bucketName: "YOUR_BUCKET_NAME",
  region: "YOUR_REGION"
};
```

---

## 📱 Pages & Features

| Page | Description |
|---|---|
| Home | Platform landing page with featured content |
| Upload | Media file upload with progress indicator |
| Player | Video playback with controls |
| Dashboard | Admin panel for content management |
| Login | User authentication and role assignment |

---

## 🔮 Future Improvements

- [ ] Add real-time live streaming using WebRTC
- [ ] Implement video compression before upload
- [ ] Add search and filter functionality
- [ ] Build recommendation engine for content

---

## 👨‍💻 Developer

**Dhanush M**
- 📧 dhanushmasanam@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/dhanush-masanam-69a745277)
- 🐙 [GitHub](https://github.com/DhanushMasanam)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
