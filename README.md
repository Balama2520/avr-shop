# Agri-Link | Farmer's All-in-One Platform 🚜

A production-ready, cloud-native E-commerce + AI Assistant platform for farmers to explore fertilizers, pesticides, and get expert advice.

## 📁 Project Structure
- **/frontend**: Next.js 16 (React) application. Styled with TailwindCSS 4.
- **/backend**: FastAPI (Python) backend with AI & Product API routes.

## ✨ Core Features
- **Product Catalog**: Fetch fertilizers and pesticides from the backend.
- **Dosage Calculator**: Smart calculations based on land area (Acres/Hectares).
- **AI Advisor**: Real-time agricultural support powered by Mistral/HuggingFace.
- **Premium UI**: Mobile-first, high-visibility design for field use.

## 🚀 Quick Start (Local)

1. **Prerequisites**:
   - Node.js installed.
   - Python installed.

2. **Run Everything**:
   From the project root:
   ```bash
   npm run dev
   ```
   *This starts the Frontend at http://localhost:3000 and Backend at http://localhost:8000.*

## 🔑 Environment Variables
Create a `.env` file in the `/backend` folder:
```env
HF_API_KEY=your_huggingface_api_key_here
MONGODB_URL=your_mongodb_atlas_url
```

## 🛠 Tech Stack
- **Frontend**: Next.js, TailwindCSS, Lucide React.
- **Backend**: FastAPI, Motor (Async MongoDB), Uvicorn.
- **AI**: HuggingFace Inference API.