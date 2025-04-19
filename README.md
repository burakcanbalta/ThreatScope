# 🛡️ Risk Dashboard

**Risk Dashboard**, ağ ve web sistemlerinde potansiyel tehlikeleri tespit etmek, filtrelemek, özetlemek ve raporlamak için geliştirilmiş profesyonel bir React tabanlı izleme panelidir.

## 🚀 Özellikler

- 🔍 Gerçek zamanlı log analizi
- 📊 RiskChart görselleştirme
- ⭐ Favori log sistemi + ayrı sekme
- 🤖 AI özet & öneri analizi (demo)
- ⬇️ PDF/HTML dışa aktarma + SHA256 veri imzası
- 🌐 Discord Webhook bildirimi (Critical loglar için)
- 🧪 Test modu (örnek loglarla offline çalıştırma)
- 🌗 Otomatik tema (gündüz/gece)
- ⚙️ Ayarlar paneli (özellik aç/kapa)

## 📦 Kurulum

```bash
npm install
npm install jspdf crypto-js
npm start
```

## 📁 Dosyalar

- `src/components/LogList.jsx` — Tüm log görüntüleme ve işlem mantığı
- `src/components/LogCard.jsx` — Tekil log kartı
- `src/components/RiskChart.jsx` — Risk dağılımı grafiği (Pie Chart)

## 📜 Lisans

MIT License

---

> Geliştirici: [@burakcanbalta](https://github.com/burakcanbalta) | Build secure. Watch smart.
