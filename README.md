# 🛍️ PudomStore – Web Checkout with Paddle

### 👨‍💻 Built by Sereyodam

---

## 📌 About This Project

**PudomStore** is a modern **Next.js e-commerce / payment integration project** using **Paddle Billing** as a merchant of record.

This project demonstrates how to implement a **web-based checkout system** that can be integrated with mobile apps (including iOS) while handling payments, subscriptions, and taxes through Paddle.

---

## 🚀 Key Features

* 💳 **Paddle Checkout Integration**
* 🌍 **Global tax & compliance handled by Paddle**
* 📱 **Supports mobile (iOS web checkout flow)**
* ⚡ Fast and modern UI with Next.js
* 🔐 Secure payment handling (merchant of record model)
* 💼 Subscription-ready architecture

---

## 🛠️ Tech Stack

* ⚛️ **Next.js 15**
* 💻 **TypeScript**
* 🎨 **Tailwind CSS**
* 💳 **Paddle JS SDK**

---

## 📂 Project Structure

```
/src        → Application source code
/public     → Static assets
/.github    → CI/CD workflows
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/pudomstore.git
cd pudomstore
```

### 2. Install dependencies

```bash
pnpm install
# or
npm install
```

### 3. Configure environment variables

Create `.env.local` from `.env.example`:

```env
APPLE_TEAM_ID=your_team_id
NEXT_PUBLIC_BUNDLE_IDENTIFIER=your.bundle.id
NEXT_PUBLIC_APP_REDIRECT_URL=your_redirect_url
NEXT_PUBLIC_PADDLE_CLIENT_TOKEN=your_paddle_token
NEXT_PUBLIC_PADDLE_ENV=sandbox
```

---

## ▶️ Run the Project

```bash
pnpm dev
```

Open:
👉 [http://localhost:3000](http://localhost:3000)

---

## 🧪 Use Case

* 🛒 Web-based checkout for mobile apps
* 💳 Subscription billing system
* 🌐 SaaS product payments

---

## 📈 Future Improvements

* 🧾 Order history system
* 👤 User authentication
* 📊 Admin dashboard
* 💰 Pricing plans UI improvements

---

## ⚠️ Notes

* Uses **Paddle as Merchant of Record** (handles tax & compliance)
* Designed for **web-to-mobile checkout flow**

---

## 📫 Contact

* GitHub: [https://github.com/YOUR_USERNAME](https://github.com/YOUR_USERNAME)
* Email: [sereyodamc011@gmail.com](mailto:sereyodamc011@gmail.com)

---

⭐ *Exploring modern payment systems and SaaS architecture.*
