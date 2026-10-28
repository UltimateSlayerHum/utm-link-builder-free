# Utm Link Builder Free

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1A2A6C,100:B21F3D&height=220&section=header&text=Utm%20Link%20Builder%20Free&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Track%20Every%20Click%20Optimize%20Every%20Campaign&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-2.0.0-B21F3D?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-93.4K-1A2A6C?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFB300?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20chrome-00E676?style=for-the-badge&logo=googlechrome&logoColor=black)

</div>

---

## 📈 The Marketer's Secret Weapon

In the world of digital marketing, data is everything. If you don't know where your traffic is coming from, you are essentially flying blind. UTM parameters are the industry standard for tracking campaign performance across Google Analytics, Mixpanel, and other analytics platforms. However, manually typing out `?utm_source=...&utm_medium=...` is not only tedious but also highly prone to typos that can ruin your data integrity.

**Utm Link Builder Free** is a beautiful, lightning-fast, open-source web application designed to eliminate this friction. It provides a sleek, intuitive interface where you can simply fill out a form, and the tool instantly generates a perfectly formatted, shortened, and trackable URL.

This repository is perfect for social media managers, SEO specialists, and indie hackers. It includes a comprehensive dashboard where you can save your favorite UTM presets (e.g., "Facebook Ad," "Email Newsletter") and reuse them with a single click. It also features a QR code generator for your UTM links, making it easy to bridge the gap between your offline and online marketing efforts. No subscriptions, no ads, just pure marketing utility.

---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🔗 **Instant Generation** | Create perfectly formatted UTM links in milliseconds |
| 💾 **Custom Presets** | Save your most used campaign parameters for quick reuse |
| 📱 **QR Code Export** | Generate high-resolution QR codes for any UTM link |
| 🔍 **Bulk Builder** | Paste a list of URLs and apply the same UTM parameters to all of them |
| 🔒 **Privacy First** | All data is stored locally in your browser (LocalStorage) |
| 📋 **One-Click Copy** | Copy the generated link directly to your clipboard |
| 🌓 **Dark Mode** | A stunning, eye-friendly dark theme for late-night campaigns |
| 📊 **Analytics Preview** | See how your link will look in Google Analytics |

<img width="1200" height="630" alt="tools-utm-builder (1)" src="https://github.com/user-attachments/assets/e68f731d-6c54-44ef-bbca-748bbc060d95" />

---

## 💡 Why Use UTM Parameters?

Before diving into the technical setup, it is crucial to understand why UTMs are the backbone of digital marketing. 

### 1. Granular Attribution
Without UTMs, Google Analytics will group all your social media traffic under a single "Social" bucket. You won't know if that traffic came from a paid LinkedIn ad, an organic tweet, or a viral Instagram Reel. UTMs allow you to slice your data with surgical precision.

### 2. Cross-Platform Tracking
If you run a campaign across multiple platforms (e.g., a newsletter, a blog post, and a YouTube video), UTMs allow you to see exactly which platform drove the most conversions.

### 3. Team Collaboration
By using a standardized UTM builder, you ensure that your entire marketing team uses the exact same naming conventions (e.g., always lowercase, hyphens instead of spaces). This prevents fragmented data in your analytics dashboard.

---

<div align="center">

### 🔗 Ready to track your campaigns?

[![Get Builder](https://img.shields.io/badge/📈_GET_BUILDER-1A2A6C?style=for-the-badge&logoColor=white)](https://share.google/cXcXBZzP5YENPZ7pM)

</div>

---

## 🧠 How The URL Parsing Works

A UTM link is essentially a standard URL with a query string attached to it. The magic of this tool lies in its robust URL parsing and encoding logic.

When you enter your destination URL, the app uses the native `URL` API in JavaScript to parse it. It separates the base URL from any existing query parameters. This ensures that if your destination URL already has parameters (like `?id=123`), the UTM parameters are appended correctly with an `&` instead of a `?`.

The tool then encodes all your UTM values using `encodeURIComponent`. This is crucial because if your campaign name has a space or a special character (like "Summer Sale 2026!"), it will break the URL if not encoded properly. The result is a clean, reliable, and clickable link that analytics platforms can read perfectly.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-B21F3D?style=for-the-badge&logoColor=white)](https://share.google/cXcXBZzP5YENPZ7pM)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![QRCode.js](https://img.shields.io/badge/QRCode.js-000000?style=flat-square&logo=javascript&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

We believe that marketing tools should be accessible to everyone, not locked behind expensive SaaS paywalls. If you have ideas for new features, found a bug, or want to improve the UI, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-preset`).
3. **Commit** your changes (`git commit -m 'Add new preset'`).
4. **Push** to the branch (`git push origin feature/new-preset`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your campaign strategies, ask for help with analytics, and discuss the latest trends in digital marketing.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@utm-builder.dev.

---

<div align="center">

### ⭐ If this tool boosts your marketing, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFB300?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/utm-link-builder-free)

---

### 🚀 Start building your links today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-00E676?style=for-the-badge&logoColor=black)](https://share.google/cXcXBZzP5YENPZ7pM)

<sub>Crafted with precision and ❤️ by the Utm Link Builder Free community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:B21F3D,100:1A2A6C&height=120&section=footer)

</div>
