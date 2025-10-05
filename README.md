# 🐾 DogMate — Academic Prototype (Year 1)

DogMate is a **first-year university project** simulating a two-sided marketplace that connects dog owners with DogWalkers and DogSitters.
The current codebase is a front-end prototype demonstrating **user flows, UI/UX, and information architecture**.
Some advanced business features (ratings, payments, real tracking) are conceptual only and not implemented yet.

## 🌟 Overview

**DogMate** provides a centralized marketplace where:

- 🐕 **Dog owners** can easily find, rate, and communicate with professional **DogWalkers** and DogSitters.

- 👩‍💼 **Service providers** can create detailed profiles, advertise their services, and receive reviews.

- 📡 **Smart collars or chips** (conceptually represented) allow real-time monitoring of dogs’ location and health data.

The platform focuses on security, reliability, and convenience, offering an end-to-end digital experience for dog care services.

## 💼 Business Model

**DogMate** operates as a **B2C** marketplace, connecting consumers directly with dog care professionals.
Planned revenue streams include:

- 💰 **Service commissions** — percentage from each completed booking

- 🌟 **Premium subscriptions** — advanced tracking tools and visibility boosts for workers

- 📢 **External advertising** — pet stores, clinics, and dog-care brands

## 🎯 Key Features

-🧑‍🤝‍🧑 **Personal profiles** for both owners and workers with photos, ratings, and verified info

-📍 **Search and matching** by location and service type (walking, sitting, or both)

-🦴 **Smart tracking concept** (collar/chip) for dog activity overview

-💬 **Integrated chat** between clients and workers

-⭐ **Transparent reviews and ratings**

-🧾 **Secure booking flow** with feedback options

## 🖥️ Website Pages
```bash
+--------------------------------------------------+---------------------------------------------------------------+
| Page                                             | Description                                                   |
+--------------------------------------------------+---------------------------------------------------------------+
| Home (index.html)                                | Overview of DogMate’s mission and services with intro video   |
| About (about.html)                               | Information about DogMate’s purpose, values, and goals        |
| Services (services.html)                         | List of all services offered: walking, sitting, recruitment   |
| DogWalking (dogwalking.html)                     | Service details and advantages of real-time tracking          |
| DogSitters (dogsitters.html)                     | Information about professional sitting and monitoring         |
| FurryMate (furrymate.html)                       | Section for workers to find pet care opportunities            |
| Login / SignUp (login.html, signup.html)         | Forms for account access or creation                          |
| Profile (profile.html)                           | Dashboard simulation for managing dog info, bookings, and chat|
| Contact (contact.html)                           | Static form for inquiries and customer support                |
+--------------------------------------------------+---------------------------------------------------------------+

```
## 🧩 Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript

- **Design**: Responsive layout, user-centered UX principles

## 🚀 Setup & Usage

Clone the repository:
```bash
git clone https://github.com/MariTurchyn/dogmate-web.git
```

Open the folder:
```bash
cd dogmate-web/Dogmate_Project
```

Run locally:
```bash
npx live-server
```

Or simply open index.html directly in your browser.
No installation required.

## 🧠 Future Improvements

- 🔐 **Firebase authentication** & real database

- 📡 **Real-time GPS tracking APIs**

- 💳 **Online payments** and booking system

- 🧾 **Worker verification (KYC)**

- 💬 **Persistent chat** with history
