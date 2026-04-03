# SMP - School Management Portal

![SMP Banner](docs/banner.png)

## 🚀 Overview
**SMP** is a premium, mobile-first School Management Portal designed to streamline administrative tasks and provide a seamless experience for students. Built with Flutter, it features a modern **Glassmorphic UI** with a professional light blue theme, ensuring both high performance and a stunning visual aesthetic.

> [!TIP]
> This application follows a dual-theme system (optimized for a branded "Light Blue" experience) using the `ThemeProvider` for dynamic UI updates across all components.

---

## ✨ Key Features

### 🏢 Administration Hub
- **Interactive Dashboard**: Real-time overview of school metrics with smooth animations and intuitive navigation.
- **Analytics Engine**: High-fidelity charts (using `fl_chart`) for performance tracking and data analysis.
- **Student Management**: Simplified student directory, detailed profiles, and a streamlined "Add Student" process.
- **Scholarship Management**: Comprehensive module to manage scholarship lists, track application status, and view details.

### 👥 User & Role Control
- **Role-based Access**: Custom role management and user assignment modules.
- **Secure Authentication**: Robust login systems with modern security patterns.

### 📱 Premium UX/UI
- **Glassmorphism**: Consistent glass-like effects across all cards, buttons, and navigation elements.
- **Micro-animations**: Subtle transitions and hover effects to enhance user engagement.
- **Multi-platform**: Designed for mobile but compatible across multiple Flutter platforms.

---

## 📸 Screenshots

| Dashboard | Analytics |
|:---:|:---:|
| ![Dashboard](docs/dashboard.png) | ![Analytics](docs/analytics.png) |

---

## 🛠️ Tech Stack

- **Core**: [Flutter](https://flutter.dev/) & [Dart](https://dart.dev/)
- **State Management**: [Provider](https://pub.dev/packages/provider)
- **Charts**: [FL Chart](https://pub.dev/packages/fl_chart)
- **Calendar**: [Table Calendar](https://pub.dev/packages/table_calendar)
- **Icons**: [Cupertino Icons](https://pub.dev/packages/cupertino_icons)

---

## 📥 Getting Started

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (latest stable)
- Android Studio / VS Code with Flutter extension

### Installation
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/smp2.git
    cd smp2
    ```
2.  **Install dependencies:**
    ```bash
    flutter pub get
    ```
3.  **Run the application:**
    ```bash
    flutter run
    ```

---

## 📂 Project Structure
```text
lib/
├── models/         # Data models and entities
├── providers/      # State management and ThemeProvider
├── screens/        # All UI screens (Admin, Student, Auth)
├── services/       # API and backend logic (FastAPI integration)
├── theme/          # Custom Glassmorphic design system
└── widgets/        # Reusable UI components
```

---

## 🛡️ License
Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Built with ❤️ for Educational Excellence
</p>
