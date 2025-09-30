# Clean Architecture in Flutter – Tutorial Project

This repository contains my completed project  on building a full-stack Flutter application using **Clean Architecture**.

The project demonstrates how to structure Flutter apps in a scalable and maintainable way by applying **SOLID principles**, **Blocstate management**, **dependency injection with get_it**, and integrating **Supabase** as the backend.

---

## 🛠️ Tech Stack

* **Flutter**
* **Bloc** (State Management)
* **Supabase** (Auth & Database)
* **get_it** (Dependency Injection)
* **Clean Architecture** (SOLID principles applied)

---

## 📂 Project Structure

```
lib/
│── core/              # Shared utilities & error handling
│── features/          # Feature-based modules
│    ├── auth/         # Authentication
│    ├── profile/      # Profile
│    └── posts/        # Example CRUD feature
│── injection.dart     # get_it setup
│── main.dart          # App entry point
```

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/adarshm/clean-architecture-flutter.git

# Install dependencies
flutter pub get

# Run the project
flutter run
```

---

## 📝 License

