# 🚀 Habit Tracker App


## ✨ Features

- 📅 Track daily, weekly, and monthly habits
- 🔥 Streak counter for each habit
- 🏆 Best streaks leaderboard
- ✅ Swipe to complete or delete habits
- 👤 User authentication (Appwrite)
- ☁️ Cloud database (Appwrite)
- 📲 Responsive, mobile-first UI
- 🎨 Modern, clean design

![ReactNAtive HabitTracker_App](https://github.com/yasin-erkan/Mobile_Habit_Tracker_app/blob/main/habittracker.gif)


## 🛠️ Tech Stack

- **React Native** (Expo)
- **Appwrite** (Database, Auth, Realtime)
- **TypeScript**
- **React Native Paper** (UI Kit)
- **Expo Router**

---

## ⚙️ Appwrite Setup

1. **Create a Project** on [Appwrite Cloud](https://cloud.appwrite.io/) or your own server.
2. **Create Collections:**
   - `habits`
   - `completions`
3. **Set Security Rules** for authenticated users.
4. **Update your Appwrite endpoint & project ID** in `/lib/appwrite.ts`.

---

## 🧑‍💻 Development

- Edit screens in `app/(tabs)/`
- UI components use [React Native Paper](https://callstack.github.io/react-native-paper/)
- Types in `/types/`
- Auth context in `/lib/auth-context.ts`

---

## 💡 Customization

- 🎨 Change theme colors in `app/_layout.tsx`
- 🏷️ Add new features or screens in `app/(tabs)/`
- 🔔 Add push notifications with Expo if you want!
