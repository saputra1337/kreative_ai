# Affiliate Go - Foto Studio Management System

Aplikasi manajemen studio foto berbasis web dengan fitur lengkap untuk operasional harian studio fotografi.

## 🎯 Tujuan Proyek

Membangun sistem manajemen studio foto yang mencakup:
- **Customer Management**: Data pelanggan, riwayat transaksi
- **Order Management**: Booking, tracking order, status pesanan
- **Payment & Invoice**: Pembayaran, invoice, laporan keuangan
- **Inventory**: Stock produk, frame, aksesoris
- **User Management**: Multi-role (admin, kasir, fotografer, editor)
- **Analytics & Reporting**: Dashboard, laporan harian/bulanan

## 📦 Tech Stack

- **Frontend**: HTML5, Tailwind CSS, JavaScript (ES6 modules)
- **Backend**: Firebase (Firestore, Auth, Storage)
- **Hosting**: GitHub Pages / jsDelivr CDN
- **Build**: Node.js scripts untuk split/bundle

## 🗂️ Struktur Repo

```
affiliate-go/
├── src/
│   ├── index.html          # Entry point utama
│   ├── body.html           # UI components & layouts
│   ├── scripts/
│   │   ├── app.js          # Core app logic
│   │   ├── firebase.js     # Firebase integration
│   │   ├── utils.js        # Helper functions
│   │   └── modules/        # Feature modules
│   ├── styles/
│   │   ├── main.css        # Custom styles
│   │   └── tailwind.css    # Tailwind imports
│   └── assets/             # Images, icons, fonts
├── dist/                   # Build output (untuk CDN)
├── scripts/
│   └── build.js            # Build script
├── PLAN.md                 # Rencana pengembangan
├── STATUS.md               # Status progres saat ini
└── README.md               # File ini
```

## 🚀 Quick Start

### Development

```bash
# Clone repo
git clone <repo-url>
cd affiliate-go

# Install dependencies (jika ada)
npm install

# Start local server
npm run dev
# atau manual:
python3 -m http.server 8787
```

Buka browser: `http://localhost:8787`

### Build untuk Production

```bash
npm run build
```

Output ada di folder `dist/` siap deploy ke CDN.

## 📋 Status Proyek

Lihat [STATUS.md](STATUS.md) untuk progres terkini.

## 🗺️ Roadmap

Lihat [PLAN.md](PLAN.md) untuk rencana detail pengembangan.

## 🔑 Configuration

Firebase config perlu diisi di `src/scripts/firebase.js`:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

## 📝 License

Private / Proprietary

## 👤 Author

Development: 2026

---

**Last Updated**: 2026-08-11
