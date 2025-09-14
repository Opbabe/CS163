# AR-readmission-
# 🩺 AR-Enabled Clinical Decision Support (Apple Vision Pro)

> **Mixed Reality for Smarter, Safer Discharge Planning**  
> A Vision Pro app that helps clinicians identify 30-day readmission risk at the bedside, with intuitive AR overlays and hands-free interaction.

---

## ✨ Features
- 📊 **Patient Card UI** — World-anchored overlay showing readmission risk (Low / Med / High)  
- 🧪 **Top Risk Drivers** — Examples: uncontrolled HbA1c, polypharmacy, long hospital stay  
- 🗣️ **Hands-Only Interaction** — Pinch, tap, and gaze using Vision Pro native gestures  
- 📄 **AI Note Taking (Optional)** — Voice-to-text using OpenAI speech models  
- 🔒 **On-Device Privacy** — Core ML or JSON-based predictions, no PHI leaves the device  

---

## 🧠 How It Works
1. **Data Modeling**
   - Train on clinical datasets (e.g., **MIMIC-IV**) using **R/Python**
   - Models: Logistic Regression → **XGBoost** with SHAP interpretability
   - Export predictions to **Core ML (.mlmodel)** or precomputed JSON

2. **visionOS Development**
   - Built in **Xcode** with **SwiftUI + RealityKit + ARKit**
   - Assets authored in **Reality Composer Pro** (USD/USDZ format)
   - Anchored **Patient Card** positioned at bedside or clinic desk

3. **Clinician Workflow**
   - **Glance:** See color-coded readmission risk chip
   - **Tap:** Expand a bilingual, 2-minute “teach-back” discharge plan
   - **Dictate:** Optional voice notes automatically converted into text

---

## 📈 Benefits
- 🏥 **Hospitals** → Reduce billions lost to 30-day readmission penalties  
- 👩‍⚕️ **Clinicians** → Smarter discharge planning with actionable drivers  
- 👨‍👩‍👧 **Patients** → Clearer instructions, better follow-up, lower readmission risk  

---

## 🛠️ Tech Stack
- **Languages:** Swift, SwiftUI, R, Python  
- **Frameworks:** RealityKit, ARKit, Core ML, SHAP  
- **Tools:** Xcode, Reality Composer Pro, Jupyter, RStudio  
- **Hardware:** Apple Vision Pro  

---

## 🚀 Getting Started

### Prerequisites
- macOS with **Xcode 15+** and **visionOS SDK** installed  
- Apple Developer account (for signing & testing on Vision Pro)  
- R/Python environment (for model training)

### Installation
```bash
# Clone this repo
git clone https://github.com/YourUserName/your-repo.git
cd your-repo

# Open in Xcode
open ClinicalAR.xcodeproj

