# FlickNest 🎬

FlickNest is a modern movie platform inspired by Netflix, built with [Expo](https://expo.dev), [React Native](https://reactnative.dev/), and [NativeWind](https://www.nativewind.dev/).
It aims to provide a simple, beautiful, and fast movie browsing experience for mobile and web.

---

## 🚀 Features

- Browse and search for movies
- Responsive UI with Tailwind CSS (NativeWind)
- Built with Expo Router for file-based navigation
- Ready for Android, iOS, and Web

---

## 🛠️ Installation

### 1. **Clone the repository**

```bash
git clone https://github.com/Zahed-Hossen/FlickNest.git
cd FlickNest
```

### 2. **Install dependencies**

```bash
npm install
```

### 3. **Set up Node.js version**

FlickNest requires **Node.js 20.x**.
If you use [nvm](https://github.com/coreybutler/nvm-windows):

```bash
nvm use 20
```

### 4. **Start the development server**

```bash
npx expo start
```

- Press `a` to open Android emulator
- Press `i` to open iOS simulator
- Press `w` to open in web browser

---

## 📁 Project Structure

```
FlickNest/
├── app/                # App entry and screens (file-based routing)
│   ├── _layout.tsx
│   └── index.tsx
├── components/         # Reusable UI components
├── metro.config.js     # Metro bundler config (NativeWind)
├── tailwind.config.js  # Tailwind/NativeWind config
├── package.json
└── ...
```

---

## 📝 Usage

- Edit files in the `app/` directory to add screens and features.
- Use [NativeWind](https://www.nativewind.dev/) for styling with Tailwind classes.
- Navigation is handled by [Expo Router](https://docs.expo.dev/router/introduction/).

---

## 🧑‍💻 Development Scripts

| Command            | Description                      |
|--------------------|----------------------------------|
| `npm start`        | Start Expo development server    |
| `npm run android`  | Run on Android emulator/device   |
| `npm run ios`      | Run on iOS simulator/device      |
| `npm run web`      | Run in web browser               |
| `npm run lint`     | Lint the project                 |

---

## 📚 Documentation & Resources

- [Expo Documentation](https://docs.expo.dev/)
- [React Native Docs](https://reactnative.dev/docs/getting-started)
- [NativeWind Docs](https://www.nativewind.dev/)
- [Expo Router Docs](https://docs.expo.dev/router/introduction/)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

[MIT](LICENSE)

---

## 👤 Author

- [Zahed Hossen](https://github.com/Zahed-Hossen)
