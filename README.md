# 📁 File Metadata Microservice

## 🌟 Project Overview
This is a simple **File Metadata Microservice** that allows users to upload a file and retrieve metadata about the file, including:
- 📄 **File Name**
- 📌 **MIME Type**
- 📏 **File Size (in bytes)**

This project is built using **Node.js**, **Express**, and **Multer** for handling file uploads.

## 🚀 Live Demo
🔗 [Live Project URL](#) *(Replace with your deployed link if available)*

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js
- **File Upload Handling:** Multer
- **Environment Variables:** dotenv

## 🎯 Features
- Upload a file via a POST request.
- Receive a JSON response with file metadata.
- Handles errors gracefully.

## 📥 API Endpoint
### **Upload File**
**POST** `/api/fileanalyse`

#### 📌 Request
- Send a file using the `multipart/form-data` format.
- Key: `upfile`

#### 📤 Response (JSON)
```json
{
  "name": "example.txt",
  "type": "text/plain",
  "size": 12345
}
```

## 🏗️ Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/file-metadata-microservice.git
cd file-metadata-microservice
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file and add:
```env
PORT=3000
```

### 4️⃣ Run the Server
```bash
npm start
```
Server will be running on **http://localhost:3000**

## 🛠️ Dependencies
- express
- multer
- dotenv
- cors

## 📜 License
This project is open-source and available under the **MIT License**.

---
💡 *Happy coding! 🚀*

