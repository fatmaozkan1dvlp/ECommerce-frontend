# 🛍️ E-Commerce Frontend

React ve Tailwind CSS ile geliştirilmiş modern e-ticaret arayüzü.
[E-Commerce API](https://github.com/fatmaozkan1dvlp/ecommerce-api) ile çalışır.

## 🚀 Teknolojiler

- **React 18** — UI framework
- **Vite** — Build tool
- **Tailwind CSS** — Styling
- **Axios** — HTTP client
- **React Router v6** — Routing
- **React Hot Toast** — Bildirimler
- **React Helmet Async** — SEO
- **Lucide React** — İkonlar

## 📌 Özellikler

### 🛒 Kullanıcı Tarafı
- Ürün listeleme, filtreleme ve arama
- Slug tabanlı SEO dostu URL'ler
- Ürün detay sayfası
- Sepet yönetimi
- Sipariş oluşturma (adres formu)
- Sipariş takibi ve iptal
- Favori listesi
- Profil yönetimi
- Giriş / Kayıt

### 🔧 Admin Paneli
- Dashboard (istatistikler, son siparişler)
- Ürün yönetimi (ekle, düzenle, arşivle)
- Kategori yönetimi
- Sipariş yönetimi (durum güncelleme)
- Müşteri listesi
- Arşiv yönetimi

### 🔐 Güvenlik
- JWT tabanlı authentication
- Admin/Kullanıcı token ayrımı (sessionStorage/localStorage)
- Route koruması (AuthRoute, AdminRoute)
- Token expire kontrolü

## ⚙️ Kurulum

### Gereksinimler
- Node.js 18+
- [E-Commerce API](https://github.com/fatmaozkan1dvlp/ecommerce-api) çalışıyor olmalı

### 1. Repoyu klonla
```bash
git clone https://github.com/fatmaozkan1dvlp/ecommerce-frontend.git
cd ecommerce-frontend
```

### 2. Bağımlılıkları yükle
```bash
npm install
```

### 3. `.env` dosyası oluştur
```env
VITE_API_URL=APIURL
```

### 4. Çalıştır
```bash
npm run dev
```

Uygulama `http://localhost:5173` adresinde çalışır.

## 🖥️ Ekran Görüntüleri

> Admin Panel, Ana Sayfa, Ürün Detay, Sepet ekran görüntüleri eklenecek.

## 🔗 İlgili Repo

- **Backend:** [ecommerce-api](https://github.com/fatmaozkan1dvlp/ecommerce-api)

## 👩‍💻 Geliştirici

Bu proje fullstack geliştirme pratiği amacıyla yapılmıştır.
