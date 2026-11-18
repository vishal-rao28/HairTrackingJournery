<div align="center">
  <img src="https://raw.githubusercontent.com/vishal-rao28/Vishal-s-portfolio/main/src/assets/hairjourney/app_icon.jpg" width="96" height="96" alt="HairJourneyTracker Icon" />

  <h1>HairJourneyTracker</h1>

  <p><b>Native iOS photographic milestone & dermatology consultation platform with AVFoundation capture, PhotosUI comparison galleries, Core Data offline persistence, multi-language localization, and clinician scheduling.</b></p>

  <a href="https://apps.apple.com/in/app/hairjourneytracker/id6760697820">
    <img src="https://img.shields.io/badge/Apple_App_Store-Live-EA580C?style=for-the-badge&logo=apple&logoColor=white" alt="App Store Live" />
  </a>
  <img src="https://img.shields.io/badge/Swift-SwiftUI_%2B_CoreData-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftUI + CoreData" />
  <img src="https://img.shields.io/badge/Capture-AVFoundation_%2B_PhotosUI-38BDF8?style=for-the-badge" alt="AVFoundation" />
  <img src="https://img.shields.io/badge/Platform-iOS-0A84FF?style=for-the-badge&logo=ios&logoColor=white" alt="iOS" />
</div>

---

## 📱 App Preview

<div align="center">
  <table>
    <tr>
      <td><img src="https://raw.githubusercontent.com/vishal-rao28/Vishal-s-portfolio/main/src/assets/hairjourney/screen1.webp" width="190" alt="Screen 1" /></td>
      <td><img src="https://raw.githubusercontent.com/vishal-rao28/Vishal-s-portfolio/main/src/assets/hairjourney/screen2.webp" width="190" alt="Screen 2" /></td>
      <td><img src="https://raw.githubusercontent.com/vishal-rao28/Vishal-s-portfolio/main/src/assets/hairjourney/screen3.webp" width="190" alt="Screen 3" /></td>
      <td><img src="https://raw.githubusercontent.com/vishal-rao28/Vishal-s-portfolio/main/src/assets/hairjourney/screen4.webp" width="190" alt="Screen 4" /></td>
    </tr>
  </table>
</div>

---

## ✨ Key Capabilities

- **📸 Guided Photographic Time-Lapse**: Custom `CameraManager.swift` (`AVFoundation`) + `PhotosUI` asset ingestion for consistent multi-angle progress tracking.
- **👨‍⚕️ Doctor & Patient Portals**: Complete specialist workflow across 58 Swift files (`DoctorDashboardView`, `DoctorPatientListView`, `DoctorHairImagesView`, `DoctorHairImageDetailView`, `CreateSlotView`, `BookAppointmentView`).
- **💾 Offline-First Core Data Engine**: Local structured storage managed via `CoreDataExpertManager.swift`.
- **🌍 Dynamic Multi-Language Support**: Runtime localization switching powered by `AppLanguageManager.swift`.
- **🔔 Milestone Reminders**: Scheduled `UserNotifications` keeping patients consistent with weekly captures and appointments.

---

## 🏗️ Architecture

```mermaid
flowchart LR
    A["AVFoundation CameraManager / PhotosUI"] --> B["CoreDataExpertManager (Local Store)"]
    B --> C["Patient Milestone Timeline"]
    B --> D["Doctor Dashboard & Image Review"]
    C & D --> E["Appointment Slots & UserNotifications"]
    C & D --> F["APIService & AppLanguageManager"]
```

---

## 🛠️ Frameworks & Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **UI & Theming** | `SwiftUI`, `UIKit`, `AppTheme.swift`, `ButtonStyles.swift` |
| **Camera & Media** | `AVFoundation`, `PhotosUI`, `WebKit` |
| **Persistence & i18n** | `CoreData`, `AppLanguageManager.swift` |
| **Auth & Scheduling** | `AuthViewModel.swift`, `UserNotifications`, `APIService.swift` |

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/vishal-rao28/HairTrackingJournery.git
   cd HairTrackingJournery
   ```
2. Open the Xcode project:
   ```bash
   open HairJourney.xcodeproj
   ```
3. Select an iOS Simulator or physical iPhone and press **`Cmd + R`**.

---

## 👤 Author

**Vishal Rao M** — Native iOS & On-Device AI Architect  
[Live Portfolio](https://vishal-rao28.github.io/Vishal-s-portfolio/) · [GitHub](https://github.com/vishal-rao28) · [Vishal iOS Labs](https://github.com/Vishal-iOS-Labs)
