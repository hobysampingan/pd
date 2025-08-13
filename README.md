# PHubish - Video Platform

Aplikasi web untuk menampilkan dan mengelola koleksi video dengan dukungan optimal untuk video vertical.

## Fitur Utama

### 🎥 View Mode Toggle
- **Auto Mode**: Mendeteksi otomatis orientasi video (horizontal/vertical)
- **Horizontal Mode**: Layout optimal untuk video landscape (16:9)
- **Vertical Mode**: Layout optimal untuk video portrait (9:16)

### 🔍 Pencarian & Pengurutan
- Pencarian berdasarkan judul video
- Pengurutan berdasarkan:
  - Relevansi
  - Judul (A-Z / Z-A)
  - Durasi (terlama/terpendek)
  - Ukuran file (terbesar/terkecil)

### 📱 Responsive Design
- Layout yang dioptimalkan untuk mobile
- Grid yang menyesuaikan dengan orientasi video
- Lazy loading untuk performa optimal

## Upgrade untuk Video Vertical

### Layout Vertical Mode
- Grid dengan kolom lebih banyak (140px - 120px)
- Aspect ratio 9:16 untuk thumbnail
- Font size yang dioptimalkan untuk tampilan compact
- Spacing yang efisien untuk video vertical

### Layout Horizontal Mode
- Grid dengan kolom lebih sedikit (280px - 240px)
- Aspect ratio 16:9 untuk thumbnail
- Layout yang nyaman untuk video landscape

### Auto Detection
- Mendeteksi otomatis orientasi video berdasarkan dimensi
- Menyesuaikan layout secara dinamis
- Memberikan pengalaman yang optimal tanpa perlu setting manual

## Cara Penggunaan

1. **Pilih View Mode**:
   - Klik tombol "Auto" untuk deteksi otomatis
   - Klik tombol "Horizontal" untuk video landscape
   - Klik tombol "Vertical" untuk video portrait

2. **Cari Video**:
   - Gunakan search box untuk mencari judul video

3. **Urutkan Video**:
   - Pilih kriteria pengurutan dari dropdown

4. **Responsive Layout**:
   - Layout akan menyesuaikan otomatis di mobile
   - Grid akan berubah sesuai dengan view mode yang dipilih

## Struktur File

```
pd/
├── index.html          # Halaman utama dengan view toggle
├── player.html         # Halaman pemutar video
├── assets/
│   ├── app.js         # Logic utama dengan view mode
│   ├── styles.css     # CSS dengan layout vertical/horizontal
│   ├── player.js      # Video player
│   └── utils.js       # Utility functions
├── thumbnail/          # Thumbnail video (1000+ files)
└── video_info.json    # Data informasi video
```

## Browser Support

- Chrome/Edge (modern)
- Firefox (modern)
- Safari 12+ (dengan beberapa fitur CSS modern)
- Mobile browsers

## Performance

- Lazy loading untuk thumbnail
- Infinite scroll untuk video list
- Debounced search untuk performa optimal
- CSS Grid untuk layout yang efisien
