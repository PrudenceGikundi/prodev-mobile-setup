# prodev-mobile
# Expo Router Mobile App Setup

## 📌 Project Overview
This project sets up a React Native mobile application using the Expo Router template. The goal is to understand the scaffolding process, modify the home screen, run the app, and document the effects of resetting the project.

---

## 🚀 Getting Started

### 1️⃣ Navigate to Your Project Directory
Open your terminal and move into your project directory:
```sh
cd prodev-mobile-setup
```

### 2️⃣ Initialize a New Expo Project
Run the following command to create an Expo project using the latest Expo Router template:
```sh
npx create-expo-app@latest .
```
This sets up a React Native project with Expo Router pre-configured.

---

## 📂 Project Structure
After initialization, the directory structure will be:
```
/prodev-mobile-setup
│── app/               # Stores all screen components
│   ├── (tabs)/        # Contains tab-based navigation screens
│   │   ├── index.tsx  # Default home screen (to modify)
│── constants/
│   ├── Colors.tsx     # Contains color theme settings
│── package.json       # Project dependencies and scripts
│── README.md          # Documentation
│── app.config.ts      # Expo app configuration
```

---

## 📝 Modifying the Home Screen
Navigate to `app/(tabs)/index.tsx` and update the default text:

**Before:**
```tsx
<Text>Welcome!</Text>
```
**After:**
```tsx
<Text>** First App Created **</Text>
```

---

## ▶ Running the Application
Start the Expo development server:
```sh
npx expo start
```
- **iOS Users:** Scan the QR code in your terminal with your Camera app.
- **Android Users:** Open the Expo Go app and scan the QR code.

---

## 🔄 Resetting the Project
To reset the project, run:
```sh
npm run reset-project
```
### Observations:
- This removes all dependencies installed via `npm install`.
- Clears the cache and resets configurations.
- Deletes `node_modules` and `.expo` directories.
- Running `npx expo start` again prompts you to reinstall dependencies.

---

## ✅ Summary
### Steps Followed:
1. Initialized a new Expo project using `npx create-expo-app@latest .`.
2. Modified the `index.tsx` file to update the home screen text.
3. Started the Expo development server and tested the app.
4. Reset the project and documented the changes.

This completes the setup process! 🚀

