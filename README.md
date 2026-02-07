# E-Store iOS App

E-Store is an iOS e-commerce application built using **UIKit (Storyboard)** that allows users to browse product categories, view products, authenticate using JWT, and manage product-related actions.  
The app implements **VIPER architecture** to ensure clean separation of concerns and scalable code structure.

---

## ✨ Features

- 🛍 Browse product categories
- 📦 View products by category
- 🔐 User authentication (Login) using JWT
- 👤 View user profile
- 🖼 Upload product images
- ➕ Create new products
- 🌐 REST API integration
- ⚡ Clean & scalable architecture (VIPER)

---

## 🛠 Tech Stack

- **Swift**
- **UIKit**
- **Storyboard**
- **VIPER Architecture**
- **Moya** – Networking layer
- **Kingfisher** – Image loading & caching
- **JWT (JSON Web Token)** – Authentication
- **CocoaPods** – Dependency management

---

## 🧱 Architecture Overview

The app uses **VIPER** architecture to maintain a clean, testable, and modular codebase.
View → UI layer (Storyboard + UIViewController)
Interactor → Business logic & API calls
Presenter → Data formatting & UI state
Entity → Models
Router → Navigation


Each feature (Home, Product, Auth, Profile) is implemented as a separate VIPER module.

---

## 🌐 Networking

Networking is handled using **Moya**, which provides a clean abstraction over URLSession and simplifies API management.

- Centralized endpoint definition
- Type-safe requests
- Easy request configuration
- Supports multipart upload and JWT authorization

API requests are triggered inside the **Interactor layer**.

---

## 🔐 Authentication

- User authentication uses **JWT**
- Token is retrieved during login
- Token is attached to authenticated requests
- User profile is accessible after successful login

---

## 🖼 Image Handling

The app uses **Kingfisher** to handle remote images efficiently.

Benefits:
- Asynchronous image loading
- Automatic caching
- Smooth scrolling experience

## 📦 Dependency Management

Dependencies are managed using CocoaPods.
pod 'Moya'
pod 'Kingfisher'

## 📱 UI Implementation
- Built using UIKit
- Layouts designed with Storyboard
- Navigation handled via VIPER Router
- Supports clean transitions between modules

## 🚀 Getting Started

- Clone this repository
- Run pod install
- Open E-Store.xcworkspace
- Build and run the app using Xcode

## 👩‍💻 Author
Naela Fauzul Muna
iOS Engineer
