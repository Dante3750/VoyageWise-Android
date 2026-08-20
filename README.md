# VoyageWise: Advanced Travel Planning & Weather Analytics

[![Platform](https://img.shields.io/badge/Platform-Android-brightgreen.svg)](https://developer.android.com/android)
[![Architecture](https://img.shields.io/badge/Architecture-Clean--Arch-blue.svg)](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
[![Tech](https://img.shields.io/badge/UI-Jetpack--Compose-orange.svg)](https://developer.android.com/jetpack/compose)

A high-performance Travel Planning application built to demonstrate **Clean Architecture**, **Dependency Injection**, and **Offline-First** synchronization. VoyageWise allows users to build complex, multi-day itineraries with real-time weather integration and intelligent destination search.

---

## �/Modular Architecture
- **Domain Layer**: 100% Pure Kotlin. No dependencies on Android libraries.
- **Data Layer**: Handles data persistence (Room) and network communication (Retrofit).
- **Presentation Layer**: Built with **Jetpack Compose** following the MVVM pattern.

## 🚀 Technical Features
- **Offline-First Synchronization**: SSOT strategy via Room.
- **Background Processing**: WorkManager for weather forecast updates.
- **API Optimization**: Google Autocomplete Session Tokens for cost reduction.


## 🛞 Tech Stack
- Kotlin, Jetpack Compose (M3), Room, Retrofit, Hilt, Coroutines, WorkManager.

---
*Developed by Dante*
