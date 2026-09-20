## Aaron Zheng

I am a fourth-year undergraduate student at The Ohio State University pursuing a B.S. in Computer & Information Science with a specialization in Database Systems & Data Analytics. Lately most of my time goes into native Apple apps in Swift, alongside a cross-platform React Native product I ship for a nonprofit.

Contact: zheng.2274@osu.edu  
LinkedIn: https://linkedin.com/in/aaronzzheng

---

### Currently building

**Sanctuary Connect – Cross-Platform Sponsorship App** *(private repo)*  
A two-sided mobile app connecting animal sanctuaries with sponsors, built with React Native + Expo and running on both iOS and Android from a single codebase. Sponsors subscribe to sponsor individual animals and receive a private feed of updates, while sanctuary staff post updates, manage animals, and run donation campaigns. I built the full stack: a TypeScript app following a strict Screen → Hook → Service architecture, a Firebase backend (Firestore, Auth, Storage, Cloud Messaging), 25+ Cloud Functions on Node.js, role-based access control via custom claims, and recurring payments through Stripe (Payment Sheet with Apple Pay and Google Pay). Shipped as v1.0 with CI and handover docs.

**Lumen – Local Adjustments for Apple Photos** *(private repo)*  
A macOS photo editor that adds the thing Apple Photos lacks: masked, local adjustments. Click a subject, get a mask, edit only that. Eight combinable mask types (subject, people, box, brush, colour range, linear and radial gradients, luminance range) driven by the Vision framework, plus a content-aware heal tool. One Swift engine powers two front ends: a standalone app and a Photos editing extension so the tools appear inside Photos itself.

**[Matcha](https://github.com/aaronzzheng/matcharonju) – Track, Rate and Rank Every Matcha You Try**  
A SwiftUI app for iOS 17+ with a seed catalog of 612 matcha from 91 Japanese houses. Rate what you drink through Beli-style pairwise comparisons, and a 12-dimension taste profile learns your preferences and predicts a Match % for anything you haven't tried. Includes natural-language search, shelves, friend compatibility over CloudKit, and shareable image cards. Runs in the Simulator with nothing but Xcode.

---

### macOS menu bar utilities

Small, single-purpose Swift apps. No Dock icon, no dependencies, ad-hoc signed, and each builds and installs with one script.

| App | What it does |
|---|---|
| [VolBoost](https://github.com/aaronzzheng/VolBoost) | Per-app output volume and boost, using Core Audio process taps |
| [ClipStack](https://github.com/aaronzzheng/ClipStack) | Your last 10 clippings, one click away |
| [Vigil](https://github.com/aaronzzheng/Vigil) | Keep your Mac awake on your terms, and see what else is keeping it awake |
| [Shelf](https://github.com/aaronzzheng/Shelf) | A place to put files down: drag onto the menu bar, drag off wherever you need them |
| [Tidy](https://github.com/aaronzzheng/Tidy) | Two small rules that keep Downloads and screenshots in order |

---

### Hackathons

**[HackOHIO 2025 – SmartParking](https://github.com/JunhoHwoang/HackOHIO-2025)** · 🥈 2nd place, Honda Challenge  
HackOHIO is Ohio State's largest 24-hour hackathon. My team built SmartParking, a full-stack web application that visualizes real-time campus parking availability. We worked on the Node.js APIs, the React + Leaflet frontend, and a Python + OpenCV MobileNetV3 model that detects open parking stalls with 98% accuracy. We placed 2nd out of 190 teams. [Demo](https://youtu.be/uGOvJDlFeZ0) · [Write-up](https://medium.com/99p-labs/hack-ohi-o-2025-14330ac1931e)

**[Data I/O 2026 – Campus Energy Analytics](https://github.com/dlwogk7939/DataIO-2026)**  
Data I/O is OSU's annual data-focused hackathon. We built a campus energy analytics dashboard with weather-driven ML prediction: a React + TypeScript frontend for CSV uploads and visualization, and a Python (pandas, scikit-learn) prediction API that forecasts electricity usage from temperature, precipitation, and wind speed.

---

### Earlier work

**[Sleep Tamagotchi](https://github.com/aaronzzheng/SleepTamagotchi) – Wear OS Internship Project**  
Built during my Mobile Software Engineer internship at Kyoto University of Advanced Sciences (Kyoto, Japan, summer 2025). A Wear OS virtual pet in Godot that encourages healthier sleep routines. I integrated biometric sensors (steps, light, heart rate) through custom Java + Android SDK plugins and designed modular systems for quests, moods, and JSON save/load.

**[meli](https://github.com/aaronzzheng/meli) – Music Rating App**  
An Android app in Kotlin for ranking and comparing music you've listened to, integrated with the Spotify API.

---

### Tools I reach for

Swift (SwiftUI, AppKit, Vision, Core Audio) · TypeScript (React, React Native + Expo, Node.js) · Python (pandas, scikit-learn, OpenCV) · Java · Kotlin · GDScript · Firebase · Stripe · SQL
