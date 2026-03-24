# Virtual Try-On App

## Project Overview
**See how clothes look on you before you buy them.**  
This app uses AI to simulate a virtual try-on experience, helping users make better online shopping decisions.

---

## Features
- Upload or select a user photo  
- Browse a catalog of clothing items  
- Overlay clothes onto the user’s image  
- Simple and user-friendly interface  
- Helps reduce uncertainty in online purchases  

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **Mobile App** | React Native / Expo (TypeScript) |
| **Backend API** | Supabase Edge Functions / Node.js |
| **Database** | Supabase Postgres |
| **Object Storage** | Supabase Storage (temporary bucket, 1h TTL) |
| **AI Engine** | Google Vertex AI |
| **Queue** | Supabase-based job queue (Postgres + Worker) |
| **On-device Storage** | Expo FileSystem / AsyncStorage |

---

## Purpose
This project was developed as part of the **Fundamentals of Software Engineering** course.

---

## License
This project is for academic purposes. All rights reserved.
