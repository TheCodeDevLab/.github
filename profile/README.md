# TheCode — Deterministic Password Generator

> 🔐 **One secret key. Unique, long, and secure passwords for every website.**
> 
> 🌐 Official website: **[thecode.julsql.fr](thecode.julsql.fr)**

## 🎯 Overview
**TheCode** is a deterministic — yet highly secure — password generator.

It creates a unique and complex password for each website using:

- the **website name** (e.g., `facebook.com`)
- a **secret key** chosen by the user

➡️ With the same website name and the same secret key, TheCode always generates **the same secure password**.

➡️ Users only need to remember **one single key**, not dozens of passwords.

## 🔧 How It Works
1. The user inputs:
- the **website or service name**
- their **secret key**
2. TheCode concatenates both values and generates a SHA-256 hash.
3. The hexadecimal hash is converted into a password using a customizable character set:
- lowercase letters
- uppercase letters
- digits
- special characters
4. The result is:
- **deterministic**
- **unique for each website**
- **long and secure** (20 characters by default)

## 🛡️ Security
- SHA-256 is **non-reversible**: no one can recover your secret key from your generated password.
- Your key is **neither transmitted nor stored** — the generation happens locally.
- Even if a password leaks, your **key and other accounts remain safe.**

## ⚠️ Important:
If your secret key is leaked, anyone could reproduce your passwords.
Make sure to choose a safe key and keep it private.

## 📱 Availability
- TheCode is available on a wide variety of platforms:

### 🔗 Web App
- [thecode.julsql.fr](https://thecode.julsql.fr)

### 📱 Mobile Apps
- **Android**: [Google Play Store](https://play.google.com/store/apps/details?id=fr.juliette.thecode)
- **iOS**: [Apple App Store](https://apps.apple.com/app/thecode-password-manager/id6753169043)

### 🖥️ Desktop
- **macOS app** (includes the Safari extension): [Apple App Store](https://apps.apple.com/app/thecode-password-manager/id6753169043)

### 🧩 Browser Extensions
Compatible with:
- [Chrome](https://chromewebstore.google.com/detail/thecode/jeknefpalcipdlnbeboefonmnlejepen)
- [Edge](https://chromewebstore.google.com/detail/thecode/jeknefpalcipdlnbeboefonmnlejepen)
- [Firefox](https://addons.mozilla.org/fr/firefox/addon/thecode/)
- [Safari](https://apps.apple.com/app/thecode-password-manager/id6753169043)
- [Brave](https://chromewebstore.google.com/detail/thecode/jeknefpalcipdlnbeboefonmnlejepen)
- and other Chromium-based browsers (see Chrome link)

## 🧱 GitHub Organization Structure
This organization contains all components of TheCode ecosystem, such as:
- <a href="https://github.com/TheCodeDevLab/thecode-website">
    <img src="images/github_white.png" alt="logo github" width="15" height="15"/>
    <strong>thecode-website</strong>
  </a>— landing page and online generator
- <a href="https://github.com/TheCodeDevLab/thecode-extension">
    <img src="images/github_white.png" alt="logo github" width="15" height="15"/>
    <strong>thecode-extension</strong>
  </a>— multi-browser extension
- <a href="https://github.com/TheCodeDevLab/thecode-apple">
    <img src="images/github_white.png" alt="logo github" width="15" height="15"/>
    <strong>thecode-apple</strong>
  </a>— iOS/macOS app
- <a href="https://github.com/TheCodeDevLab/TheCode_Android">
    <img src="images/github_white.png" alt="logo github" width="15" height="15"/>
    <strong>thecode-android</strong>
  </a>— Android native app

Each repository provides its own **dedicated README** with setup and development instructions.

<!--
- **thecode-core** (in coming) — password generation logic & doc
-->

## 🤝 Contributing
Contributions are welcome!
You can help by:
- reporting bugs
- submitting improvements
- proposing new features
- adding translations

Feel free to open an Issue or create a **Pull Request**.

## 📄 License
TheCode is distributed under the **MIT License**.
