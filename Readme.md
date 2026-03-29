# CYA-01: Career Development Experience

## Chosen Adventure

Participation in **CrimsonCode 2026**, a 24-hour hackathon hosted at Washington State University, as a co-developer of **HealthCam** — a contactless, real-time health monitoring iOS prototype powered by smartphone camera biometrics and a conversational AI voice interface.

The project repository is available here: [github.com/1paramveer/crimson-code-26](https://github.com/1paramveer/crimson-code-26.git)

---

## Career Goals

**Short-term:** Build practical experience applying machine learning and signal processing concepts to real-world systems, while developing the software engineering skills needed to work in applied AI/data science roles.

**Long-term:** Work as a data scientist or ML engineer, ideally at the intersection of human-centered AI and healthcare or physiological computing — building systems that extract meaningful insights from sensor data and translate them into actionable, intelligent interfaces.

---

## Deliverable Summary

**HealthCam** is an experimental iOS prototype that explores using a smartphone's front-facing camera to perform remote photoplethysmography (rPPG) — estimating heart activity and breathing patterns from subtle skin-color changes captured on video. The system pairs this biometric sensing layer with an ElevenLabs-powered conversational voice agent that responds to the user's physiological state in real time, providing spoken de-escalation guidance without requiring any wearables or external hardware.

The app was built in 6 hours during CrimsonCode 2026 as a 3-person team project.

My individual contributions centered on the **system integration layer**:

- Coordinating the biometric data pipeline with the core application logic
- Implementing lifecycle safeguards so that downstream features (including the voice agent) only activate once the rPPG signal reaches a reliable, calibrated state
- Supporting the integration of the ElevenLabs conversational component with the physiological monitoring flow
- Stabilizing the demo under time-pressure hackathon conditions through testing and rapid debugging

---

## Deliverable Assets

- **Project repo:** [github.com/1paramveer/crimson-code-26](https://github.com/1paramveer/crimson-code-26)
- **Devpost submission:** [devpost.com/software/health-cam](https://devpost.com/software/health-cam)
- **Reflection:** See [REFLECTION.md](./REFLECTION.md)
