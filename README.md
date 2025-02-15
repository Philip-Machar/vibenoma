# 🎵 Music Recognition Web App

## 📌 Overview
This web application allows users to recognize songs through both direct audio input and humming/mumbling/whistling/singing etc. It leverages the ACRCloud API for melody detection and Africa's Talking SMS service for song sharing. The app functions similarly to Shazam but includes melody recognition through humming/mumbling/whistling/singing.

![Vibenoma Screenshot](./images/vibenoma-screenshot.png)  

## 🌍 Live Demo
[Live Demo](https://vibenoma-frontend.vercel.app/) 

## 🚀 Features
- 🎤 **Song Recognition**: Identify songs from recorded or live audio.
- 🎶 **Melody Recognition**: Recognize songs by humming/mumbling/whistling/singing.
- 📡 **API Integration**: Utilizes ACRCloud API for accurate song detection.
- 📲 **SMS Notifications**: Sends song details to users via Africa's Talking SMS service.
- 🎨 **Visually Impressive UI**: Futuristic animations enhance user experience.

## 🛠️ Tech Stack
- **Frontend**: Vite, React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **APIs**:
  - ACRCloud API (Melody & Song Recognition)
  - Africa's Talking SMS API (Song Details Sharing)

## 📖 Setup & Installation
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/music-web-app.git
   cd music-web-app
   ```
2. **Install dependencies**:
   ```sh
   npm install
   ```
3. **Set up environment variables**:
   Create a `.env` file and add the following:
   ```env
   VITE_ACRCLOUD_API_KEY=your_api_key
   VITE_AFRICASTALKING_API_KEY=your_api_key
   ```
4. **Run the development server**:
   ```sh
   npm run dev
   ```
5. **Open in browser**:
   - Visit `http://localhost:5173/` (or the specified port in your setup)

## 🏆 Credits
- **Developer**: Philip Machar
- **APIs Used**: ACRCloud, Africa's Talking

## 📜 License
This project is licensed under the [MIT License](LICENSE).

## 📬 Contact
- Email: philipmachar788@gmail.com
- LinkedIn: [My Profile](https://www.linkedin.com/in/philip-machar-06029230a/)


