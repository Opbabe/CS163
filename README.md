# CS163 Project Repo
# 🩺 AR Readmission Coach (Apple Vision Pro)

**Mixed Reality for Smarter, Safer Discharge Planning**  
A visionOS app that helps clinicians spot 30-day readmission risks at the bedside using AR overlays and hand-only interaction.

---

## ✨ Highlights
- 📊 **Patient Card** — risk level (Low / Med / High) with key drivers like HbA1c, polypharmacy, and LOS  
- 🧠 **Smart Modeling** — Logistic Regression → XGBoost with SHAP, exported to Core ML / JSON  
- 🖐️ **Native Gestures** — pinch, tap, gaze to expand a bilingual 2-min teach-back plan  
- 📄 **Optional AI Notes** — speech-to-text for quick discharge documentation  
- 🔒 **On-Device First** — all predictions run locally; no PHI leaves the headset  

---

## 🚀 How It Works
1. **Model Training** → R/Python on clinical datasets (e.g., MIMIC-IV)  
2. **Export** → Core ML model (`.mlmodel`) or JSON with risk & drivers  
3. **visionOS Build** → SwiftUI + RealityKit + ARKit, assets from Reality Composer Pro  
4. **At Bedside** → Clinician sees risk chip, taps to expand plan, dictates notes if needed  

---

## 📈 Impact
- 🏥 Hospitals → fewer penalties from avoidable readmissions  
- 👩‍⚕️ Clinicians → faster, smarter discharge planning  
- 👨‍👩‍👧 Patients → clear instructions they can actually follow  

---

## 🛠️ Tech Stack
Swift • SwiftUI • RealityKit • ARKit • Core ML • R/Python • SHAP • Xcode • Vision Pro  

---

👨‍💻 **Author:** Nick Tran — Dept. of Computer Science, SJSU



