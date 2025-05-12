# 📸 Flare Frame

Flare Frame is an Android-based social media app built using Jetpack Compose, with a modern architecture and developer-friendly tech stack. It’s currently in its early development stages and is a work in progress.

---

## 🚀 Project Status

🛠️ In Development  
Currently, only the registration logic and user authentication are implemented. The upload post feature has CameraX integration completed, but the backend connection for image uploads is not yet implemented.

---

## 📱 Features (Planned & Current)

| Feature              | Status         | Notes                                                                 |
|----------------------|----------------|-----------------------------------------------------------------------|
| User Registration    | ✅ Complete     | Firebase Auth used for authentication (subject to change).           |
| Camera Integration   | ✅ Complete     | CameraX is integrated to capture photos for posts.                   |
| Image Upload to DB   | ⏳ Incomplete   | Supabase buckets planned for storing captured post images.           |
| Post Feed / Timeline | ⏳ Planned      | Will retrieve and show posts stored in Supabase.                     |
| Like/Comment System  | ⏳ Planned      | Basic engagement features under consideration.                       |

---

## 🛠️ Tech Stack

### Frontend

- Jetpack Compose for UI  
- CameraX for image capture  
- MutableStateFlow from Kotlin Coroutines for reactive UI state management  
- Android ViewModel for lifecycle-aware architecture  

### Backend / Services

- Supabase for Postgres-based table storage and eventual image bucket storage  
- Firebase Authentication for user management (may change in future)  

---

## 🔒 Authentication

Firebase Auth is currently used to handle registration and login.  
We may consider migrating to a unified backend solution like Supabase Auth later for tighter integration with the rest of the data layer.

---

## 📸 Camera Uploads

- CameraX is fully integrated and working  
- Currently captures photos using the device camera  
- Upload functionality to Supabase storage buckets is not yet implemented but is part of the roadmap  

---

## 📝 TODO

- [ ] Hook up image uploads to Supabase storage buckets  
- [ ] Implement user profile and settings  
- [ ] Build the post feed screen  
- [ ] Add comment and like functionalities  
- [ ] Explore potential Firebase → Supabase Auth migration  

---
---

## 📣 Disclaimer

This app is still in its early phases and not yet ready for production or public release.  
