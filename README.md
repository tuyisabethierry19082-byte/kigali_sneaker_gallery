# 👟 KGL SNEAKER GALLERY

> Modern, responsive shoe & sneaker e-commerce website built with **HTML5, Vanilla CSS, Bootstrap 5.3, and JavaScript**.

---

## 🚀 How to Run the Website

### Option 1: Double-Click (Immediate)
Simply double-click **`index.html`** in this folder, and it will open directly in Google Chrome, Microsoft Edge, Brave, or any modern web browser.

### Option 2: Live Server / VS Code
If using Visual Studio Code:
1. Right-click `index.html`
2. Select **"Open with Live Server"**

---

## 📁 Project Structure

```
kgl sneaker gallery/
├── index.html            # Main website with all sections, modals & drawers
├── css/
│   └── style.css         # Modern styling, glassmorphism, dark/light themes, animations
├── js/
│   ├── products.js       # Sneaker catalog database, prices (RWF/USD), sizes & specs
│   └── app.js            # Cart, wishlist, WhatsApp direct order, checkout & filters
├── assets/               # High-res photography of shoes and brand logo
│   ├── brand_banner.jpg
│   ├── shoe_airmax_tn.jpg
│   ├── shoe_jordan_retro.jpg
│   ├── shoe_runner_volt.jpg
│   ├── shoe_street_retro.jpg
│   └── shoe_chunky_velocity.jpg
├── shoes.html            # Original starter project (preserved with link to new site)
└── README.md             # Project documentation & guide
```

---

## ⚡ Features Included

- **Curated Sneaker Vault**: Filter by category (*Streetwear*, *Basketball*, *Running*, *Luxury*, *Lifestyle*) and brand (*Nike*, *Jordan*, *Adidas*, *New Balance*).
- **Dual Currency Switcher**: Toggle between **RWF (Rwandan Franc)** and **USD ($)** with instant price updates across the site.
- **WhatsApp Direct Ordering**:
  - One-click order for any shoe card directly into WhatsApp chat (+250 790 329 458).
  - One-click cart checkout via WhatsApp with full itemized summary.
- **Shopping Cart Drawer**:
  - Quantity controls (`+` / `-`), remove items, and promo codes.
  - Test Promo Code: **`KGL10`** (gives 10% discount!).
- **Quick View Modal**: Preview details, sizes (EU 36–46), and specs.
- **Size Guide Modal**: European (EU) to US, UK, and CM conversion table.
- **Express Kigali Checkout**:
  - Payment methods: MTN MoMo (*182#), Airtel Money, Cash on Delivery, or Card.
  - District selection (Nyarugenge, Gasabo, Kicukiro).
  - Simulated instant order receipt with reference code.
- **Dark / Light Theme Toggle**: Seamless obsidian dark and clean light modes saved to `localStorage`.
- **Deal of the Day**: Live countdown timer with remaining inventory bar.

---

## 🛠️ How to Add or Edit Shoes

Open `js/products.js` to modify or add new sneakers:

```javascript
{
  id: "kgl-09",
  name: "Your New Shoe Name",
  brand: "Nike",
  category: "streetwear",
  categoryLabel: "Streetwear & Lifestyle",
  priceRWF: 35000,
  priceUSD: 27,
  originalPriceRWF: 45000,
  originalPriceUSD: 35,
  rating: 5.0,
  reviewsCount: 42,
  badge: "New Release",
  badgeType: "fire",
  image: "assets/your_image.jpg",
  sizes: [38, 39, 40, 41, 42, 43, 44, 45, 46],
  description: "Your custom description...",
  inStock: true,
  stockCount: 10
}
```

---

## 🌐 Deploying to the Web (Free)

You can publish this store live on the internet for free using:
- **Netlify**: Drag and drop the `kgl sneaker gallery` folder into [netlify.com/drop](https://app.netlify.com/drop).
- **Vercel**: Run `npx vercel` or import from GitHub.
- **GitHub Pages**: Push this directory to a GitHub repository and turn on Pages in repository settings.
