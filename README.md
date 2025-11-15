# GrandTourXR — Spatial Storytelling Platform

## 📝 Short Description
GrandTourXR is a WebXR platform that transforms real-world spaces into shared immersive experiences using Gaussian Splatting, multiplayer tour rooms, and AI-guided storytelling.

---

## 🚀 Features

### 1. Photorealistic 3D Spaces (Gaussian Splatting)
- Automatic reconstruction into lightweight, high-fidelity splats  
- 6DoF exploration in browser or VR  
- Smooth host-controlled scene transitions  

### 2. Multiplayer “Tour Rooms”
- Up to 20 users via a simple browser link  
- Real-time spatial voice chat (Photon)  
- Hierarchical roles:  
  - **Guide:** full avatar (head/hand tracking)  
  - **Participants:** abstract markers (low visual noise)  
- Synchronized navigation  
- Guide pointer + annotation tools  

### 3. AI Companion (One-on-One Mode)
- AI guide follows user movement  
- Answers context-aware questions  
- Ideal for tourism, education, real estate, and 24/7 tours  

### 4. 2D → 3D “Holographic Memories”
- Upload photos → get generated pseudo-3D scenes  
- Low-barrier content creation for cultural orgs and small businesses  

---

## 🌍 Inspiration
Virtual travel often feels lonely and inaccessible, while cultural institutions struggle with complex digitization pipelines. GrandTourXR aims to democratize immersive spatial storytelling and enable shared experiences inside real 3D places—guided by humans or AI.

---

## 💡 What It Does
GrandTourXR combines:

- **Gaussian Splatting** for photorealistic digital twins  
- **WebXR multiplayer** for social exploration  
- **AI companions** for narrative guidance  
- **Creator tools** for easy content generation  

Think of it as:

> **“Airbnb Meets Zoom Meets AI Tour Guide — inside real 3D spaces.”**

Users can:
1. Walk through a neighborhood with a live guide  
2. Revisit a childhood street reconstructed in 3D splats  
3. Explore heritage sites with an AI historian  
4. Teach architecture inside a scanned building  

All from a browser link.

---

## 🛠️ How We Built It

### Multiplayer Layer (Photon)
- Photon Pun / Fusion  
- Up to 20 users  
- Spatial audio + host-priority logic  
- Synced avatars + abstract participant markers  

### WebXR Controls
- VR + PC hybrid input  
- Gravity-enabled PC locomotion  
- Shared guide pointer  
- Minimal avatar rig (head + hands)  

### Gaussian Splatting Engine
- WebXR-splat loading pipeline  
- LOD optimizations for fast streaming  
- Scene boundaries  
- Host-driven scene switching  

### AI Layer
- OpenAI-powered guide  
- Parses metadata + user questions  
- Vision-powered gaze → commentary mapping  

### Frontend / Backend
- WebXR with Three.js + React  
- Firebase + Node  
- Hosted on Vercel + Cloud Storage  

---

## 🏆 Accomplishments
- Combined **Gaussian Splatting + Multiplayer WebXR** in-browser  
- Built a coordinated, guided tour system  
- Designed asymmetric roles to maintain clarity  
- Implemented AI follow-along narration  
- Achieved cross-device support (PC, VR headsets, browsers)  

---

## ⚙️ Challenges We Overcame
Network sync was tough—keeping state consistent across all players needed custom interpolation. Hand tracking issues during overlapping interactions were solved with a grab prediction system that interprets user intent.

---

## 📚 Lessons Learned
Early playtesting is essential. Mechanics that sounded good on paper didn’t feel comfortable in VR. Prioritizing comfort and accessibility made the experience significantly better.

---

## 🔮 What We’d Do Differently
We’d build a modular layout system earlier to support custom environments. More time would also go into audio design—sound cues are crucial in VR but were under-prioritized.

---
