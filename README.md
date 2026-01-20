# Letteram — Real-Time Messaging Application

A premium, full-stack communication platform featuring real-time messaging, intelligent image handling, and an extensive theme engine. Built with the MERN stack and Socket.io for a seamless, low-latency experience.

<img width="1919" height="910" alt="image" src="https://github.com/user-attachments/assets/01312486-3518-4af7-9ea6-c8d294c808ab" />

## Features

- **Real-Time Core**: Instant messaging and live online/offline status tracking powered by Socket.io.
- **Enhanced Media Suite (Custom)**: 
  - **Multi-Upload**: Support for up to 10 images per message.
  - **Smart Compression**: Client-side image optimization to reduce latency and bandwidth.
- **Advanced UX (Custom)**: 
  - **Contact Pinning**: Keep important conversations at the top of your list.
  - **Integrated Search**: Fast contact filtering to find users instantly.
- **Visual Identity**: 34 unique theme options, including custom color palettes added for a personalized aesthetic.
- **Secure Architecture**: JWT-based authentication with HTTP-only cookies and BCrypt password hashing.
- **Cloud Management**: Seamless profile and media storage integrated with Cloudinary.
- **Tech Stack**: React 18, Node.js, Express, MongoDB, Zustand, Tailwind CSS, DaisyUI.

## Credits & Contributions

This project was developed based on a tutorial by [Burak Orkmez](https://github.com/burakorkmez). 

**Key Custom Enhancements by Adilet Batyrov:**
* Implemented **Multi-image upload logic** (up to 10 files).
* Engineered **Client-side image compression** before Cloudinary upload.
* Developed the **Contact Pinning** system.
* Added **Search functionality** for the contact list.
* Expanded the theme library with **custom UI themes**.

## Developer

Built by **Adilet Batyrov**.

- [LinkedIn](https://www.linkedin.com/in/adilet-batyrov/)
- [GitHub](https://github.com/adiletbtrv)

## Getting Started

### 1. Environment Configuration
Create a `.env` file in the `backend` directory with your MongoDB, JWT, and Cloudinary credentials.

### 2. Install & Run
```bash
# Install dependencies
cd backend && npm install
cd ../frontend && npm install

# Start Backend (Port 5001)
cd backend && npm start

# Start Frontend
cd frontend && npm run dev
```
