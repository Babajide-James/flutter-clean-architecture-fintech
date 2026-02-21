# 🚀 Engineering Showcase: Confidential FinTech Project

> **Role:** Lead Mobile Engineer  
> **Status:** Proprietary / Stealth Mode  
> **Core Stack:** Flutter (Dart) | Firebase | SQLite | Clean Architecture

---

### 📌 Executive Summary
I am currently architecting a high-performance financial application tailored for the Nigerian market. Due to the proprietary nature of the financial algorithms involved, the **source code is private**. 

This repository serves as a technical overview of the **engineering decisions**, **architectural patterns**, and **complex challenges** solved during development.

---

### 🛠️ Technical Competencies Demonstrated

#### 1. Advanced State Management (Hybrid Approach)
* **Bloc (Business Logic Component):** Implemented for complex, event-driven features like Authentication and Data Synchronization. This ensures a strictly predictable state flow (`Loading` → `Success` → `Failure`) that is isolated and testable.
* **Provider:** Utilized for lightweight **Dependency Injection (DI)**, efficiently supplying repositories and services across the widget tree without boilerplate.

#### 2. Robust Authentication Systems
* **OAuth 2.0 Integration:** Engineered a secure authentication flow handling edge cases such as user cancellation, network failure, and token refresh.
* **Legacy Migration:** Successfully migrated authentication modules to the latest **Google Sign-In SDK (v7+)**, resolving breaking changes and enforcing strict type safety across the auth layer.

#### 3. Responsive & Adaptive UI Engine
* **Beyond Media Queries:** Implemented a **`LayoutBuilder` architecture** to handle diverse screen sizes.
* **Foldable Support:** The application dynamically rebuilds its structural layout based on device constraints, offering a native "Split-View" experience on tablets/foldables while maintaining a focused "List View" on mobile devices.

#### 4. "Offline-First" Data Persistence
* **Local-First Strategy:** Engineered a custom **Repository Pattern** that prioritizes local **SQLite** storage for immediate UI responsiveness (0ms latency).
* **Background Sync:** Implemented a background synchronization service that batches and uploads encrypted data to **Cloud Firestore** only when network conditions allow. This ensures the app remains fully functional in low-connectivity environments common in the target market.

---

### 🔒 Why is the code private?
This application contains **proprietary algorithms** for financial compliance and automated computation. As these are trade secrets, the source code cannot be shared publicly.

**I am available to discuss the specific architectural patterns (Clean Architecture, Repository Pattern) and coding standards used in this project during a technical interview.**

---

### 📬 Contact
* **Email:** Teestartaiwo121@gmail.com 
* **LinkedIn:** https://www.linkedin.com/in/james-babajide
