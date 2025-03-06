 # 🚀 Flutter E-Commerce App 
## 📖 Overview
A fully functional Flutter e-commerce app with features like user authentication, product listing, cart management,
onboarding screens, and splash screens. The app uses modern Flutter technologies like Dio for networking, 
Retrofit is for API abstraction, Cubit & Bloc is for state management, and Git is for version control.

## 🎯 **Features**
✅ Fetch and display product lists  
✅ Enable user Search using name of product  
✅ User authentication (Login/Register)  
✅ Manage shopping cart  
✅ API integration with Retrofit (Dio)  
✅ State management (Provider/Bloc/Riverpod)  
✅ Responsive UI with Jetpack Compose-style widgets  

## 📷 **Screenshots**
 onboarding frist  |onBoarding Next  | Onboarding final |  
|-------------|--------------|---------------|
|  <img src= "https://github.com/user-attachments/assets/32c0dd0d-f012-49b1-ae60-37d65bcda880" width="200" height="400" alt="Image 1"> | <img src= "https://github.com/user-attachments/assets/2167d756-27aa-4db8-9485-cc9cca3bb7ef" width="200" height="400" alt="Image 2"> | <img src="https://github.com/user-attachments/assets/442bd94f-bbce-4b41-912e-fad130d546b6" width="200" height="400" alt="Image 3">  |
---
  Login | Registration |
  |-----------|----------|
<img src= "https://github.com/user-attachments/assets/1aa18c81-b344-47b8-b8d1-d56b96abd9b0" width="200" height="400" alt="Image 1"> | <img src= "https://github.com/user-attachments/assets/546b3fec-6b49-4a16-80d7-19dfe1bd0fd4" width="200" height="400" alt="Image 1"> |
---

 product | detalise   | Cart🛒  |
 |---------------|-------------|--------------|
 | ![Screenshot_20250306_044654](https://github.com/user-attachments/assets/1ff8a345-49df-4e69-9940-14c5c0cb0b45) |   ![Screenshot_20250306_044722](https://github.com/user-attachments/assets/8bbf890b-0792-49e1-a02c-7ce121da40f1)  |     ![Screenshot_20250306_044746](https://github.com/user-attachments/assets/310a2f37-67de-4143-8eb9-81d91cd12971) |

---

## 🏗️  App Structure
           
      lib/
      │
      ├── core/                  # Core Layer (Framework-independent utilities)
      │   ├── constants/         # App-wide constants (e.g., colors, strings, API keys)
      │   ├── errors/            # Custom error handling and exceptions
      │   ├── network/           # Network-related utilities (e.g., Dio client, interceptors)
      │   ├── utils/             # Helper functions, extensions, and utilities
      │   ├── widgets/           # Reusable widgets used across the app
      │   └── di/                # Dependency Injection (DI) setup
      │       └── injector.dart  # Dependency injection configuration
      │
      ├── data/                  # Data Layer (Data sources and repositories)
      │   ├── datasources/       # Data sources (local and remote)
      │   │   ├── local/         # Local data sources (e.g., SQLite, SharedPreferences)
      │   │   └── remote/        # Remote data sources (e.g., API calls)
      │   ├── models/            # Data models (e.g., API response models)
      │   ├── repositories/      # Repository implementations
      │   └── data_providers/    # Data providers (optional, for complex data flows)
      │
      ├── domain/                # Domain Layer (Business logic and use cases)
      │   ├── entities/          # Business entities (e.g., User, Product)
      │   ├── repositories/      # Repository interfaces (abstract classes)
      │   ├── use_cases/         # Use cases (business logic)
      │   └── exceptions/        # Domain-specific exceptions
      │
      ├── presentation/          # Presentation Layer (UI and state management)
      │   ├── auth/              # Authentication module
      │   │   ├── bloc/          # BLoC for auth (events, states, bloc)
      │   │   ├── pages/         # Auth-related screens (e.g., login, signup)
      │   │   └── widgets/       # Auth-related UI components
      │   ├── product/           # Product module
      │   │   ├── bloc/          # BLoC for product (events, states, bloc)
      │   │   ├── pages/         # Product-related screens (e.g., product list, details)
      │   │   └── widgets/       # Product-related UI components
      │   ├── cart/              # Cart module
      │   │   ├── bloc/          # BLoC for cart (events, states, bloc)
      │   │   ├── pages/         # Cart-related screens (e.g., cart page, checkout)
      │   │   └── widgets/       # Cart-related UI components
      │   ├── theme/             # App theme (colors, text styles, etc.)
      │   └── app.dart           # Main app widget (e.g., MaterialApp setup)
      │
      └── main.dart              # App entry point
              
   
    
## 🧑‍💻Technologies Used


 🌐Networking
 
   Dio: A powerful and versatile HTTP client for Dart, used for making API requests.
   Retrofit: A type-safe API client generator that simplifies API integration and reduces boilerplate code.

 🔧State Management
 
  Cubit: A lightweight and easy-to-use state management solution for managing app state.
  Bloc: A more advanced state management library for handling complex state logic and side effects.

  🗡️ Dependency Injection
  
  GetIt: A simple and efficient service locator for dependency injection, making it easy to manage and inject dependencies.

  building_construction  Routing
  
   GoRouter or AutoRout e: For declarative and type-safe navigation and routing within the app.

 🎨  UI Components



API
FakeStoreAPI: A free and open-source API that provides mock data for products, users, and carts, used for testing and development.
