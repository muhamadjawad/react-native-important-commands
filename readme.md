# 🛠️ Essential JS Developer Commands

A handy collection of frequently-used commands for JavaScript developers. Feel free to contribute and share your own tips!

---

## 📦 Package Management

### 1. Install Dependencies with Legacy Peer Deps
For older projects with incompatible dependencies:
```bash
npm install --save --legacy-peer-deps
```

### 2. Increase Yarn Network Timeout

```bash
yarn --network-timeout 100000
```

### 3. Clear NPM Cache

```bash
npm cache clean --force
```

### 📲 Creating a Release APK (React Native)

```bash
./gradlew assembleRelease
```

## 👤 Updating Git Username and Email

### 1. Update Username
```bash
git config --global user.name "Your Name"
```

### 2. Update Email
```bash
git config --global user.email "your-email@example.com"
```


## 🔄 Other Useful Commands

### Start a Development Server

Quickly start your project in development mode:
```bash
npm start
```

### Revert Last Commit (Without Losing Changes)
Undo the last commit but keep your changes:
```bash
git reset --soft HEAD~1
```

## 📢 Contribute
Feel free to add more commands! Open a PR to share your favorite commands and help other developers.

