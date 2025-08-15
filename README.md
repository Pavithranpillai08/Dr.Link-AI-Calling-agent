# Dr.Link AI Calling Agent - 11.ai

## What is Dr.Link?

**Dr. Link** is a health-tech platform designed to help patients quickly discover and connect with specialist doctors across India, especially in critical health situations where time is crucial.  
It goes beyond generic hospital directories by providing verified doctor profiles, comparative insights, and secure video consultations — all within one unified platform.

### Core Features:
- **Specialist Discovery:** Find top doctors for critical conditions.  
- **Verified Profiles:** Only verified specialists are onboarded.  
- **Video Consultations:** Encrypted, optional recordings for transparency & fraud prevention.  
- **Transparent Wallet System:** Fair refunds & dispute resolution for missed appointments.  

> The calling agent is an integral module of Dr. Link, designed to facilitate timely communication between patients and verified specialists.

---

## AI Calling Agent

An AI-powered healthcare calling agent that:
- Automatically reminds patients about their appointments.  
- Notifies them when lab reports are ready.  
- Allows patients to call doctors and interact with the agent.  
- Provides lab report details on request.  
- Handles rescheduling requests and offers the next available dates.  

> *(Currently, the `.txt` file is static, so the agent reads from it and returns output based on the data.)*

This project uses **[ElevenLabs](https://elevenlabs.io/)** for natural-sounding voice calls, with structured data for:
- Patient details  
- Doctor schedules  
- Lab report statuses  

**LLM Used:** *Gemini 2.0 Flash*

---
### Dr. Link also includes
The agent was made by our team using n8n:
This module forms the automation backbone of Dr. Link, enabling users to search for doctors using natural language queries and instantly get relevant matches from a verified database, [Check it out here](https://github.com/Riniii09/drlink-n8n?tab=readme-ov-file)


## Future Scope

1. Make it dynamic by integrating a real-world database and adding Google Docs API, so that the script is read from a doc and updates in real-time (e.g., new appointment schedules).  
2. Enhance the agent to act as a **personal assistant**, giving reminders and helping doctors manage patients.  
3. Integrate **WhatsApp notifications** for a smoother process.  
4. Add **multilingual support** so that every Indian can access it easily. *(Currently, the agent understands only English.)*

---

> The agent is smart enough to assist with basic queries. If it cannot answer a question, it will redirect the user to the Dr.Link page.
