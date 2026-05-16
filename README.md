# 🏠 GiveNest

### _Bridging donors with orphanages — one kind act at a time._

<br/>

> GiveNest is an open-source mobile app that connects **donors** with **orphanages** to facilitate donations of clothes, toys, books, food, and other essentials — making giving simple, transparent, and meaningful.

---

## 💡 The Problem

Millions of children in orphanages lack basic necessities — yet many donors willing to help don't know _who_ to reach, _what_ is needed, or _how_ to get items there. GiveNest solves this with a simple, trusted platform.

---

## ✨ Features

### For Donors

- 🔍 **Browse orphanages** by city, category of need, or urgency
- 📦 **Pledge donations** — clothes, toys, books, food & more
- 💬 **Contact directly** with orphanage coordinators
- 📊 **Track your impact** — history of donations made
- 🔔 **Get notified** when your donation is confirmed or received

### For Orphanages

- 🏠 **Create a verified profile** with photos, location & about section
- 📋 **Post needs** with category, quantity, and urgency level
- ✅ **Manage incoming pledges** — accept, schedule, and confirm
- 📈 **Dashboard** to track all donations at a glance

### General

- 🔐 Role-based auth (Donor / Orphanage)
- 🗺️ Map view to discover nearby orphanages
- 📱 Works on Android ( iOS work in progress)

---

## 📸 Screenshots

> Coming soon — UI is actively being designed.

---

## 🛠️ Tech Stack

| Layer              | Technology                        |
| ------------------ | --------------------------------- |
| Framework          | React Native + Expo (Expo Router) |
| Language           | TypeScript                        |
| State Management   | Zustand                           |
| Backend & Auth     | Node.js                           |
| Database           | MongoDb                           |
| Storage            | Cloudinary                        |
| Maps               | `react-native-maps`               |
| Push Notifications | Expo Notifications                |
| UI Components      | Custom + NativeWind (TailwindCSS) |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or higher)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- [Git](https://git-scm.com/)

### 1. Clone the Repository

```bash
git clone https://github.com/tanmayR18/givenest.git
cd givenest
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root directory:

```env
EXPO_PUBLIC_CLOUDINARY_URL=your_cloudinary_project_url
```

> You can find these in your cloudinary project under **Settings → API**.

### 4. Build the android folder

```bash
npx expo run:android
```

### 5. Start the App

> Once built completely, from the next time direct using this command to start the project

```bash
npm run android
```

---

## 🗺️ Roadmap

- [x] Project setup & architecture planning
- [ ] Authentication (donor & orphanage roles)
- [ ] Orphanage profile creation & verification flow
- [ ] Needs posting & browsing
- [ ] Donation pledge & tracking
- [ ] Seamless contact between orphanage owner and donor
- [ ] Map view
- [ ] Push notifications
- [ ] Admin panel for orphanage verification
- [ ] Analytics dashboard

---

## 🤝 Contributing

Contributions are warmly welcome! This is a community-driven project with a real social impact.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'feat: add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our code of conduct and development guidelines. Incase the CONTRIBUTING.md is not created contact the repo owner, thank you.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

---

## 🙏 Acknowledgements

- Inspired by the countless children who deserve a warmer world
- Built with love using [Expo](https://expo.dev/) and [Supabase](https://supabase.com/)

---

<div align="center">

Made with ❤️ for the kids who deserve it most.

**If you find this project meaningful, please give it a ⭐ on GitHub!**

</div>
