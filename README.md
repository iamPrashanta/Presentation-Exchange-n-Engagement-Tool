---

# **PEET: Presentation Exchange & Engagement Tool**

PEET is a high-performance, open-source screen-sharing and video-conferencing platform designed for **ultra-low-latency collaboration**. Built on the modern WebRTC standard and powered by **NexusRTC**, it provides a robust and scalable foundation for real-time engagement.

---

## 🚀 **Key Features**

* **Real-Time Screen Sharing**
  Broadcast windows, browser tabs, or entire screens in high definition.

* **Crystal-Clear Video & Audio**
  Pure peer-to-peer (P2P) communication backed by NexusRTC.

* **Advanced Media Processing**
  Integrated with **FFmpeg** for recording, transcoding, and adaptive streaming.

* **Reliable Data Management**
  **PostgreSQL** stores users, meeting logs, and session metadata.

* **Cross-Platform Compatibility**
  Works seamlessly across all modern browsers without plugins.

## 🛠️ **Tech Stack**

| Component        | Technology                            |
| ---------------- | ------------------------------------- |
| Real-Time Engine | NexusRTC (WebRTC Framework)           |
| Database         | PostgreSQL                            |
| Media Handling   | FFmpeg                                |
| Frontend         | Modern JavaScript (HTML5/WebRTC APIs) |
| License          | MIT License                           |

---

## 📦 **Getting Started**

### **Prerequisites**

* **Node.js** v16+
* **PostgreSQL** v13+
* **FFmpeg** installed and available in system PATH

### **Installation**

**Clone the Repository**

```bash
git clone https://github.com
cd peet
```

**Install Dependencies**

```bash
npm install
```

### **Setup Database**

Create a PostgreSQL database and configure your `.env` file:

```env
DATABASE_URL=postgres://user:password@localhost:5432/peet_db
```

### **Run the Application**

```bash
npm start
```

---

## 📄 **License**

Distributed under the **MIT License**.
See the `LICENSE` file for complete details.

---

## ✨ **PEET — Because every presentation deserves perfect engagement.**
