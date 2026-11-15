# Mahmoud Hassan

Android Developer based in Giza, Egypt. Open to Android roles.

[Portfolio](https://www.hekal.tech) | [LinkedIn](https://www.linkedin.com/in/mahmoud-hassan-5b4882253) | [Email](mailto:mahhassan8k@gmail.com) | [Resume](https://www.hekal.tech/Mahmoud_Hassan_Android_Developer_CV.pdf)

---

## About

I build native Android applications with Kotlin and Jetpack Compose, using MVVM and Clean Architecture. I graduated with a B.Sc. in Computer Science from Thebes Academy in 2026 and currently work as a freelance Android engineer.

My recent work includes an offline-first navigation app published on Google Play, and a graduation project that runs a custom license plate recognition model on-device. I'm also exploring Kotlin Multiplatform.

## Experience

**Android Engineer, Freelance (Mostaqel)** | Remote | Jul 2026 - Present

- Develop and maintain native Android apps for clients, mainly Al-Dalilah, an offline desert navigation app.
- Redesigned location tracking and offline map features, and built responsive subscription screens with ConstraintLayout.
- Implemented a dual-key trial verification system (Android ID and App Set ID) with timeout guards to prevent splash screen freezes on weak networks.

**Mobile Developer Trainee, Digital Egypt Pioneers Initiative (DEPI)** | Maadi, Egypt | Nov 2024 - May 2025

- Completed a 7-month Android program and built 3 native apps with Kotlin, Jetpack Compose, and Navigation Compose.
- Practiced Activity and Fragment lifecycle management, OOP principles, and UI/UX fundamentals.

## Technical Skills

| Area | Technologies |
|:--|:--|
| Languages | Kotlin, Java, Dart, C++, XML |
| UI | Jetpack Compose, Material Design 3, Navigation Compose, Flutter |
| Architecture | MVVM, MVP, Clean Architecture, Hilt, SOLID, Design Patterns |
| Async and State | Coroutines, Kotlin Flow, StateFlow, LiveData |
| Data and Networking | Retrofit, OkHttp, Room, DataStore, SQLite, REST APIs, Firebase (Auth, Firestore, Storage) |
| Libraries | Coil, Glide, DiffUtil, Google Maps, osmdroid, Mapsforge |
| Tools | Android Studio, IntelliJ IDEA, VS Code, Git, GitHub |

## Projects

### Al-Dalilah (Desert Compass)

Offline desert navigation app and subscription platform, published on Google Play. Freelance project.

Kotlin, Jetpack Compose, osmdroid, Mapsforge, BRouter, Room, Firebase, Google Play Billing, React, Node.js

- Rebuilt the app to work fully offline using local vector maps, with disk-backed tile caching to avoid out-of-memory crashes on low-end devices.
- Embedded BRouter for on-device routing without a server, within a strict 32 MB RAM limit.
- Added a background service for GPS track recording on Android 14, saving coordinates in batches.
- Migrated from a one-time purchase to subscriptions with Google Play Billing. The free trial is bound to hardware IDs and validated server-side.
- Synced VIP status through Firestore listeners and cached it locally with EncryptedSharedPreferences.
- Built a React and Node.js admin dashboard, plus a daily GitHub Actions pipeline that syncs Google Play Console, GA4, and Crashlytics data into Firestore.

[Google Play](https://play.google.com/store/apps/details?id=com.navigationgps.desert) | [Offline GIS details](https://www.hekal.tech/projects/al-dalilah-offline-gis) | [SaaS platform details](https://www.hekal.tech/projects/al-dalilah)

### Omni Parking (EALPR PlateSlotTransformer)

Graduation project, 2025-2026. Smart parking system with on-device Egyptian license plate recognition.

PyTorch, TensorFlow Lite, YOLO, Transformer, Flutter, SQLite

- Designed a PlateSlotTransformer OCR model that predicts the plate as 7 parallel slots over a CNN and Transformer backbone, replacing CTC sequence decoding.
- Reached 93.27% exact-match accuracy on a locked test set of 1,574 real plates, 18.27 points above the CRNN-CTC baseline (75.00%).
- Trained on 8,093 real plates and 50k synthetic images in two phases with AdamW and OneCycleLR.
- Exported to an INT8-quantized TFLite model of 7.78 MB and integrated it into a Flutter app with YOLO plate localization, offline SQLite storage, and QR ticketing.

[Case study](https://www.hekal.tech/projects/omni-parking) | [Source code](https://github.com/hekal-4e/egyptian-license-plate-detector)

### JobVerse

Job search app built with Kotlin, Jetpack Compose, Firebase (Firestore, Auth, Storage), MVVM, and Coroutines. I led the user profile module (creation, editing, settings) and implemented state management with StateFlow across 8 screens following Material Design 3.

[Source code](https://github.com/hekal-4e/Job-Search)

### Veris

News app with an offline-first design: Room for local caching, Retrofit for remote data, debounced search, swipe-to-delete with undo, and loading states. Built with MVVM, Coroutines, and LiveData.

[Source code](https://github.com/hekal-4e/Veris-App)

### Task Manager

Native Android task manager in Kotlin and Java with full CRUD, local notifications through BroadcastReceiver and NotificationCompat, DiffUtil for list updates, and PendingIntent handling for older Android versions.

[Source code](https://github.com/hekal-4e/Task-Manager-App)

### Book Store

Flutter bookstore app with search, shopping cart, categorized listings, and navigation. Built during the Flutter training program at Thebes Academy and MASA.

[Source code](https://github.com/hekal-4e/Books-Store-App)

## Education

**B.Sc. in Computer Science**, Thebes Academy, Giza, Egypt | 2022 - 2026

## Certifications

- Mobile Developer Trainee, Digital Egypt Pioneers Initiative (DEPI) | Nov 2024 - May 2025
- Flutter App Development, Thebes Academy and MASA | Jul - Sep 2023

## Contact

Email: [mahhassan8k@gmail.com](mailto:mahhassan8k@gmail.com)
