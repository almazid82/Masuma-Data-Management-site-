# 🏪 Masuma Tiles Agency — Management System

![Version](https://img.shields.io/badge/Version-11.0-C8A040?style=flat-square)
![HTML](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Backend](https://img.shields.io/badge/Backend-None-3dd68c?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-9b7ff4?style=flat-square)

> "টাইলসের হিসাব, রসিদ, আর কাস্টমারের তথ্য — সব এক জায়গায়, এক ক্লিকে।"

**Masuma Tiles Agency Management System** হলো একটি সম্পূর্ণ **single-page** টাইলস ব্যবসা ব্যবস্থাপনা অ্যাপ। কোনো backend, database বা installation ছাড়াই টাইলসের পরিমাণ হিসাব, কাস্টমার রসিদ তৈরি, এবং সমস্ত calculation history সংরক্ষণ করা যায়।

🔗 **Live Site:** [https://almazid82.github.io/Masuma-Data-Management-site-/](https://almazid82.github.io/Masuma-Data-Management-site-/)

---

## 📸 Preview

> Ultra-dark Tesla Cybertruck-inspired UI — Space Grotesk ফন্ট, gradient gold accent, এবং smooth 3D card effects।

---

## ✨ Features

- ✅ **৫ ধরনের টাইলস** — Wall, Floor, Rustic, Matching Floor, Stair
- ✅ **১৩+ টাইল সাইজ** সাপোর্ট — 8×12 থেকে 24×24 পর্যন্ত
- ✅ **Deco / Deep / Light** split — Wall tile-এর তিনটি অংশে আলাদা carton হিসাব
- ✅ **Step / Riser** split — Stair tile-এর দুই অংশের আলাদা হিসাব
- ✅ **Company-wise** carton পরিমাণ — প্রতিটি কোম্পানির pcs/carton আলাদা
- ✅ **Purpose** selection — Bathroom, Kitchen, Drawing Room, Bedroom সহ ১১টি option
- ✅ **A4 PDF Invoice** — professional invoice তৈরি ও print
- ✅ **Other Products** — Grout, accessories সহ যেকোনো item add করা যায়
- ✅ **Analytics Dashboard** — Revenue, Top Products, Top Customers, Monthly Chart
- ✅ **CSV Export** — সব history এক ক্লিকে Excel-এ download
- ✅ **History System** — সর্বোচ্চ ২০০টি calculation সংরক্ষণ
- ✅ **Duplicate Order** — পুরনো order থেকে নতুন order তৈরি
- ✅ **Light / Dark Mode** toggle
- ✅ **Mobile Responsive** design
- ✅ কোনো internet ছাড়াও কাজ করে (offline capable)

---

## 🧱 Supported Tile Types

### Wall Tiles
| Size | Type | Deco/Deep/Light |
|------|------|----------------|
| 8×12 | Wall | ✅ |
| 10×16 | Wall | ✅ |
| 12×18 | Wall | ✅ |
| 12×20 | Wall | ✅ |
| 12×24 | Wall | ✅ |

### Floor Tiles
| Size | Type |
|------|------|
| 16×16 | Floor |
| 12×12 | Floor |
| 24×24 | Floor |
| 12×24 | Matching Floor |

### Rustic Tiles (Exterior)
| Size | Type |
|------|------|
| 8×12 | Rustic |
| 10×16 | Rustic |
| 12×20 | Rustic |
| 12×24 | Rustic |

### Stair Tiles
| Size | Type | Split |
|------|------|-------|
| 12×24 | Stair | Step + Riser |

---

## 📊 Analytics Dashboard

Analytics tab-এ পাবেন:

- 💰 **Total Revenue** — নির্বাচিত সময়ের মোট আয়
- 📦 **Total Orders** — মোট order সংখ্যা
- 👥 **Unique Customers** — আলাদা কাস্টমার সংখ্যা
- 📐 **Total Sqft Sold** — মোট বিক্রিত sqft
- 📊 **Avg Order Value** — গড় order মূল্য
- 📈 **Monthly Revenue Chart** — শেষ ১২ মাসের বার চার্ট
- 🏆 **Top Products** — সবচেয়ে বেশি বিক্রিত tile
- 👤 **Top Customers** — সবচেয়ে বেশি কেনা কাস্টমার
- 📋 **All Transactions** — সব order এর বিস্তারিত তালিকা
- 📥 **CSV Export** — Google Sheets / Excel-এ import করা যায়

**Period Filter:** All Time / This Year / This Month / This Week

---

## 🧾 Invoice System

প্রতিটি invoice-এ থাকে:

- Shop header (Masuma Tiles Agency)
- Customer name, address, phone
- Invoice number ও date
- Tile product table — Carton/Piece, Category, Sqft, Rate, Sub Total
- Other accessories table
- Total & Payable amount
- Paid ও Due (যদি partial payment থাকে)
- In Word (amount বাংলায়)
- Carton Packing Breakdown table
- Customer ও Authorized signature

---

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)

- **Pure Vanilla JS** — কোনো framework বা library নেই
- **Single HTML File** — সব CSS ও JS একটাই ফাইলে (~2.3 MB)
- **localStorage** — browser-এই সব data সংরক্ষিত থাকে
- **Google Fonts** — Space Grotesk, Inter, Space Mono
- **CSS Custom Properties** — Light/Dark theme system
- **Canvas API** — Analytics chart rendering

---

## 🚀 Getting Started

### Option 1: সরাসরি ব্যবহার করুন
লিংকে ক্লিক করুন এবং সাথে সাথে ব্যবহার শুরু করুন:

👉 **[https://almazid82.github.io/Masuma-Data-Management-site-/](https://almazid82.github.io/Masuma-Data-Management-site-/)**

### Option 2: Locally চালান
```bash
# Repository clone করুন
git clone https://github.com/almazid82/Masuma-Data-Management-site-.git

# index.html ফাইলটি browser-এ open করুন
```

---

## 📋 ব্যবহারের নিয়ম

### ধাপ ১ — Customer Information
- Customer-এর নাম, ঠিকানা, মোবাইল নম্বর লিখুন
- Sold By এবং Paid Amount (optional) দিন

### ধাপ ২ — Tile Product যোগ করুন
1. **"＋ Add Another Product"** চাপুন
2. Area (Sqft) লিখুন
3. Wall height দিন (wall tile-এর জন্য)
4. Tile size নির্বাচন করুন
5. Company নির্বাচন করুন
6. Purpose নির্বাচন করুন (optional)
7. Rate দিন (optional)

### ধাপ ৩ — Calculate করুন
- **"✦ Calculate All Products"** চাপুন
- প্রতিটি product-এর Deco/Deep/Light বা Step/Riser breakdown দেখুন
- Carton সংখ্যা ও loose pieces দেখুন

### ধাপ ৪ — Other Products (Optional)
- Grout, accessories বা যেকোনো item check করুন
- Qty ও rate দিন
- **"Add Checked Items to PDF Receipt"** চাপুন

### ধাপ ৫ — PDF Download
- **"Download A4 Receipt as PDF"** চাপুন
- Print dialogue থেকে PDF হিসেবে save করুন

---

## 📁 Project Structure

```
Masuma-Data-Management-site-/
│
├── index.html        # সম্পূর্ণ অ্যাপ (HTML + CSS + JS)
└── README.md
```

---

## 🎨 Design System

| Color | Hex | Use |
|-------|-----|-----|
| Gold | `#C8A040` | Primary accent, buttons |
| Gold Light | `#EEC85A` | Gradient highlight |
| Navy | `#03060D` | Background (dark mode) |
| Chrome | `#E8EDF8` | Text color |
| Silver | `#8A9ABE` | Secondary text |

---

## 🔮 Future Scope

- [ ] Cloud sync — একাধিক device-এ data access
- [ ] WhatsApp-এ সরাসরি invoice শেয়ার
- [ ] PWA (Progressive Web App) — মোবাইলে install করার সুবিধা
- [ ] Supplier management module
- [ ] Stock inventory tracking
- [ ] Multi-branch support

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/shamsul-al-mazid-073a87286)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/sondartara.tara.777)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:482robikhan@gmail.com)

---

**Developed by:** Al Mazid & Fojla Rabby
**Owner:** Mahmudul Hasan Sumon
**Shop:** Masuma Tiles Agency, College Road, Amishapara, Sonaimuri, Noakhali

---

## © License

This project is open-sourced under the **MIT License**.
Feel free to use, modify, and share with credit.

---

> _"টাইলসের হিসাবে আর ভুল নয়, আর ঝামেলা নয় — Masuma Tiles Management System দিয়ে প্রতিটি order হোক নির্ভুল ও পেশাদার।"_
