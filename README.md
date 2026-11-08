# HappyGram

### A modern messenger built for simple, fast and connected communication.

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)](#)
[![Backend](https://img.shields.io/badge/Backend-PHP-777BB4?logo=php&logoColor=white)](#)
[![Database](https://img.shields.io/badge/Database-MySQL%2FMariaDB-4479A1?logo=mysql&logoColor=white)](#)
[![Status](https://img.shields.io/badge/Project-In%20Development-orange)](#)
[![License](https://img.shields.io/badge/License-To%20be%20announced-lightgrey)](#)

**HappyGram** is an Android messaging project with a PHP API and a MySQL-compatible database. The project aims to bring messaging, media sharing and communication features together in one convenient application.

> Project status: actively in development. Features and setup instructions may change.

---

## 🌍 Documentation

Choose your language:

- 🇬🇧 [English](README.md)
- 🇷🇺 [Русский](docs/README_RU.md)
- 🇪🇸 [Español](docs/README_ES.md)
- 🇩🇪 [Deutsch](docs/README_DE.md)
- 🇫🇷 [Français](docs/README_FR.md)
- 🇨🇳 [中文](docs/README_ZH.md)
- 🇸🇦 [العربية](docs/README_AR.md)

---

## ✨ Project overview

HappyGram is being developed around these core areas:

- **Messaging** — conversations and message exchange.
- **Media sharing** — support for sharing media in conversations.
- **Voice and video calls** — real-time communication capabilities under development.
- **User profiles** — account and profile information.
- **Backend API** — PHP endpoints connected to a MySQL-compatible database.
- **Android app** — mobile client built for Android.

Feature availability may depend on the current application and server version.

## 🧱 Technology

| Component | Technology |
|---|---|
| Mobile client | Android |
| Backend | PHP |
| Database | MySQL / MariaDB |
| Web server | Nginx |
| API format | JSON over HTTP |

## 📸 Screenshots

Screenshots will be added here as the interface is finalized.

| Chats | Conversation | Profile |
|---|---|---|
| `docs/screenshots/chats.png` | `docs/screenshots/conversation.png` | `docs/screenshots/profile.png` |

## 🚀 Getting started

### Requirements

- Android Studio
- Android SDK
- JDK compatible with the project's Gradle configuration
- PHP and MySQL/MariaDB for a self-hosted backend
- A configured API endpoint

### Android build

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/happygram-messenger.git
cd happygram-messenger
```

Open the Android project directory in Android Studio.

Build a debug APK from the Android project root:

```bash
./gradlew assembleDebug
```

The APK is normally generated at:

```text
app/build/outputs/apk/debug/app-debug.apk
```

The exact project directory and Gradle configuration may differ between releases.

### Backend

The backend requires a PHP environment with PDO MySQL support and a configured MySQL-compatible database.

Do not commit production credentials or private configuration files. Use a local configuration file and keep it out of Git.

See [Installation](docs/INSTALLATION.md) for setup notes.

## 📚 Documentation

- [Installation guide](docs/INSTALLATION.md)
- [API documentation](docs/API.md)
- [Security notes](docs/SECURITY.md)

## 🔐 Security

Please do not publish:

- Database passwords
- API secrets or private tokens
- Signing keys and keystores
- Production configuration files
- Personal user data or database backups

If you discover a security issue, please do not publish sensitive exploit details in a public issue. Contact the project maintainers privately.

## 🤝 Contributing

Contributions, suggestions and bug reports are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test your changes.
5. Open a Pull Request with a clear description.

Please keep contributions focused and avoid including secrets or personal data.

## 🗺️ Roadmap

- [ ] Complete and verify core messaging workflows
- [ ] Verify media sharing
- [ ] Complete voice and video call integration
- [ ] Expand API documentation
- [ ] Publish screenshots and installation guides
- [ ] Improve translations
- [ ] Prepare stable releases

## 📄 License

The project license has not yet been selected. Until a license is added, do not assume that the source code is available for unrestricted reuse or redistribution.

---

<p align="center">
  **HappyGram — bringing people closer.**
</p>
