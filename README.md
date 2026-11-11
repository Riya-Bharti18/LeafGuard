# 🌿 LeafGuard – AI-Powered Plant Health Intelligence Platform

LeafGuard is an AI-powered crop health intelligence and early-screening platform designed for farmers, agricultural extension workers, and researchers.

## 🚀 Features

- **🌾 Responsive Landing Page**: Clean, modern introductory page with product overview, disease detection stats, and agricultural guidance.
- **🔐 Authentication System**: Seamless Sign In / Sign Up interface with real-time password strength evaluation, role selection (Farmer, Researcher, Extension Officer), and validation.
- **📊 Solid Dashboard Experience**:
  - **Left Sidebar Navigation**: Instant vertical access to all app capabilities.
  - **KPI Metrics**: Real-time tracking of total scans, disease detections, healthy checks, and model confidence.
  - **Weekly Analytics**: Visual stacked activity bar charts.
- **🔬 Detect Disease Workflow**:
  - Upload JPG/PNG leaf images (or test with 4 realistic built-in presets).
  - Simulated multi-step AI inference pipeline.
  - Grad-CAM attention heatmap visualization for explainability.
  - Non-chemical, practical step-by-step guidance sourced from agricultural institutions.
  - Built-in uncertainty & abstention handling for low-confidence scans.
- **📋 Prediction Logs**: Searchable and filterable history by crop, disease status, confidence threshold, or custom keywords.
- **🧠 Model Transparency**: Complete documentation of the model architecture (EfficientNet fine-tuned on PlantVillage), validation metrics (Accuracy, Precision, Recall, Macro F1), loss/accuracy curves, and known limitations.
- **⚙️ Settings & Localization**: Profile management, multilingual interface support (English, हिन्दी, বাংলা), and privacy data controls.

## 💻 Tech Stack

- **Frontend**: Pure HTML5, Modern CSS (Custom Properties, Flexbox, Grid), Vanilla JavaScript (Zero external dependencies).
- **Target Backend (Architecture)**: FastAPI, PyTorch / TensorFlow (EfficientNet-B0), Supabase (Auth & PostgreSQL).

## 🏃 Getting Started

Simply open `index.html` in any modern web browser — no dependencies or build steps required!
