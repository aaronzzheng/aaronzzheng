## hey, I'm Aaron

CS student at Ohio State (Database Systems & Data Analytics). I mostly build things I want to exist, usually iOS and macOS apps in Swift. For my master's project I work on VisImageNavigator with Dr. Jian Chen.

[aaronzzheng.github.io](https://aaronzzheng.github.io) · zheng.2274@osu.edu · [LinkedIn](https://linkedin.com/in/aaronzzheng)

---

### what I'm working on

**[Aurora Home](https://github.com/aaronzzheng/aurora-home)**
A home screen I made for my own Android TV. Nine looks that each redo the whole screen, not just the colours: one like Apple TV, a Windows 95 desktop drawn pixel for pixel, a 1960s Japanese TV, a green hacker terminal, and more, each with its own sounds. Nine built-in games drawn to match, and your phone becomes a remote from the browser. Kotlin and Java, with a small ADB client so the phone's arrows work in YouTube and Netflix.

<a href="https://github.com/aaronzzheng/aurora-home"><img src="https://raw.githubusercontent.com/aaronzzheng/aurora-home/main/docs/screenshots/looks.jpg" width="640" alt="All nine Aurora Home looks"></a>

**[VisImageNavigator](https://visimagenavigator.github.io)** · OSU master's project with Dr. Jian Chen
A searchable collection of every figure from IEEE VIS papers. I extended it through 2025: scraped and cropped about 5,300 figures from full papers, 1,000+ from short papers, and 3,300 tables, equations and algorithms, and now I'm labeling chart types with a fine-tuned CLIP model. Python scraping and image pipeline, Google Sheets/Drive for the metadata.

**Lumen** *(private)*
Apple Photos has no way to edit just part of a picture, so I made one. Click a subject, get a mask, adjust only that. Eight kinds of masks that stack, plus a heal tool. Swift, runs as a standalone app and as an editing extension inside Photos.

---

### little mac apps

Things that bugged me about macOS, fixed in the menu bar. All Swift, no dependencies, one script to build and install.

- [VolBoost](https://github.com/aaronzzheng/VolBoost) – volume per app, and louder than 100% when you need it
- [ClipStack](https://github.com/aaronzzheng/ClipStack) – the last 10 things you copied
- [Vigil](https://github.com/aaronzzheng/Vigil) – keep the Mac awake, and see what else is
- [Shelf](https://github.com/aaronzzheng/Shelf) – somewhere to put files down while you go find where they belong
- [Tidy](https://github.com/aaronzzheng/Tidy) – renames screenshots, sorts Downloads

---

### hackathons

**[HackOHI/O 2026 – CPR Coach](https://github.com/aaronzzheng/cpr-coach)** · Most Social Impact award
A real-time CPR coach on the iPhone and Apple Watch you already own. The watch feels every compression at 100 Hz, the phone's camera checks your form with 3D body pose, and a Kalman filter fuses them into real depth in centimetres. Hands-free voice coaching in 7 languages, fatigue prediction, an AED guide and a report for paramedics. Swift 6, Apple Vision, Core Motion, on-device AI; React web version. Out of 129 teams. [Demo](https://youtu.be/oubjYkOBK_0)

**[HackOHI/O 2025 – SmartParking](https://github.com/JunhoHwoang/HackOHIO-2025)** · 2nd place, Honda Challenge
Live campus parking availability. Node APIs, React + Leaflet frontend, and an OpenCV MobileNetV3 model that spots open stalls with 98% accuracy. 2nd out of 190 teams. [Demo](https://youtu.be/uGOvJDlFeZ0) · [Write-up](https://medium.com/99p-labs/hack-ohi-o-2025-14330ac1931e)

**[Data I/O 2026 – Campus Energy Analytics](https://github.com/dlwogk7939/DataIO-2026)**
Dashboard that predicts building electricity usage from the weather. React + TypeScript frontend, Python (pandas, scikit-learn) prediction API.

---

### older

**[Sleep Tamagotchi](https://github.com/aaronzzheng/SleepTamagotchi)** – a Wear OS virtual pet that wants you to sleep better. Built in Godot during my internship at Kyoto University of Advanced Sciences, summer 2025. Custom Java plugins for the watch's step, light, and heart rate sensors.

**[meli](https://github.com/aaronzzheng/meli)** – rank the music you've listened to. Kotlin, Spotify API.
