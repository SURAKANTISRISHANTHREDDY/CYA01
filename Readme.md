# CYA-01: Career Development Experience

## Deliverable Summary
This repository documents my contribution to the HealthCam project, including system integration improvements, refactoring of signal processing logic, and enhancements to system reliability beyond the initial hackathon prototype.

---
## Chosen Adventure

Participation in **CrimsonCode 2026**, a 24 hour hackathon hosted at Washington State University, as a co-developer of **HealthCam** — a contactless, real-time health monitoring iOS prototype powered by smartphone camera biometrics and a conversational AI voice interface.

The project repository is available here: [github.com/1paramveer/crimson-code-26](https://github.com/1paramveer/crimson-code-26.git)

---
## Career Goals
 
**Short-term:** Develop practical experience applying machine learning and signal processing to real world systems, while building the software engineering foundations needed for applied AI and data science roles.
 
**Long-term:** Work as a data scientist or ML engineer on systems that process real world sensor data and connect it to intelligent, human facing outputs, particularly at the intersection of health technology and AI.
 
---
 
## Adventure Description
 
While HealthCam demonstrated a working concept at the hackathon — using the iPhone's frontfacing camera to estimate pulse and breathing rate via rPPG, paired with an ElevenLabs conversational voice agent the codebase built under a 6-hour time constraint was tightly coupled, undocumented, and difficult to extend.
 
For this CYA adventure, I spent time outside the original hackathon window individually refining the project with the goal of closing the gap between a rough prototype and something closer to a professional, reproducible system. Work included:
 
- **Refactoring the signal processing logic** — decoupling the biometric data processing layer from the application lifecycle management layer for improved modularity and maintainability
- **Improving camera feed error handling** — implementing resilient input validation so that poor lighting or obstruction produces a clean error state rather than garbage data reaching the AI inference layer
- **Writing technical documentation** — adding inline documentation and a structured README so the project can realistically be understood and built upon by other contributors
 
---

## My Contributions (Explicit)

- Implemented validation checks for camera input reliability
- Improved system stability under real-time constraints
- Added documentation for maintainability

---
## Evidence of Work

### Demo Screenshots
<img width="522" height="1126" alt="image" src="https://github.com/user-attachments/assets/41f51b9f-de1d-4fd8-8caa-e5ed3ce817db" />
<img width="526" height="1130" alt="image" src="https://github.com/user-attachments/assets/724676f4-f3f1-4402-bf6d-3c8d1305045e" />

---
## Deliverable Assets

- **Project repo:** [github.com/1paramveer/crimson-code-26](https://github.com/1paramveer/crimson-code-26)
- **Reflection:** See [Reflection.md](./Reflection.md)
