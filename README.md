# Web Portofolio

Portofolio web yang modern, responsif, dan interaktif yang dibuat dengan HTML, CSS, dan JavaScript.

## 🚀 Fitur

- **Desain Modern**: Menggunakan gradien warna dan efek glassmorphism
- **Responsif**: Optimal di semua ukuran layar (desktop, tablet, mobile)
- **Animasi**: Transisi dan animasi yang halus
- **Navigasi Smooth**: Scroll halus antar section
- **Form Kontak**: Formulir kontak yang fungsional
- **Mobile Menu**: Menu hamburger untuk perangkat mobile
- **Loading Animation**: Animasi loading saat halaman dimuat

## 📁 Struktur File

```
web-portofolio/
├── index.html          # File HTML utama
├── style.css           # File CSS untuk styling
├── script.js           # File JavaScript untuk interaktivitas
└── README.md           # Dokumentasi proyek
```

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur semantik dan aksesibilitas
- **CSS3**: 
  - Flexbox dan Grid untuk layout
  - CSS Variables untuk konsistensi warna
  - Media queries untuk responsivitas
  - Animasi dan transisi CSS
- **JavaScript (ES6+)**:
  - Intersection Observer API
  - Event handling
  - DOM manipulation
  - Form validation

## 🎨 Komponen

### 1. Navigation Bar
- Fixed navigation dengan efek blur
- Menu hamburger untuk mobile
- Active link highlighting

### 2. Hero Section
- Gradient background
- Typing animation
- Call-to-action buttons
- Profile card dengan efek glassmorphism

### 3. About Section
- Informasi personal
- Statistik pengalaman
- Animasi fade-in

### 4. Skills Section
- Grid layout untuk skill cards
- Hover effects
- Icon FontAwesome

### 5. Projects Section
- Project cards dengan gambar
- Technology tags
- Demo dan kode links

### 6. Contact Section
- Contact information
- Contact form dengan validasi
- Social media links

### 7. Footer
- Social media icons
- Copyright information

## 📱 Responsivitas

Website ini responsif di semua ukuran layar:

- **Desktop**: Layout 2 kolom untuk hero dan contact sections
- **Tablet**: Layout menyesuaikan dengan grid yang fleksibel
- **Mobile**: Single column layout dengan mobile menu

## 🎯 Cara Menggunakan

1. **Clone atau download** repository ini
2. **Buka file** `index.html` di browser
3. **Kustomisasi** konten sesuai kebutuhan:
   - Ganti nama dan informasi personal
   - Update project details
   - Sesuaikan warna dan styling
   - Tambahkan gambar dan media

## 🎨 Kustomisasi

### Mengubah Warna
Warna utama dapat diubah di file `style.css`:

```css
:root {
    --primary-color: #3498db;
    --secondary-color: #f39c12;
    --text-color: #2c3e50;
    --bg-color: #f8f9fa;
}
```

### Menambah Section Baru
1. Tambahkan section di `index.html`
2. Tambahkan styling di `style.css`
3. Tambahkan navigasi link jika diperlukan

### Mengubah Animasi
Animasi dapat dikustomisasi di `script.js` dan `style.css`:

```css
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```

## 📧 Form Kontak

Form kontak sudah dilengkapi dengan:
- Validasi input
- Email format validation
- Loading state
- Success message

Untuk mengintegrasikan dengan backend, edit bagian form submission di `script.js`.

## 🌐 Deployment

Website ini dapat di-deploy ke berbagai platform:

- **GitHub Pages**: Upload ke repository GitHub
- **Netlify**: Drag and drop folder ke Netlify
- **Vercel**: Connect repository ke Vercel
- **Firebase Hosting**: Deploy menggunakan Firebase CLI

## 📄 Lisensi

Proyek ini open source dan dapat digunakan untuk keperluan personal maupun komersial.

## 🤝 Kontribusi

Kontribusi selalu diterima! Silakan:
1. Fork repository
2. Buat branch fitur baru
3. Commit perubahan
4. Push ke branch
5. Buat Pull Request

## 📞 Kontak

Jika ada pertanyaan atau saran, silakan hubungi:
- Email: hafidrazin73@gmail.com
- GitHub: Razin907
- LinkedIn: [profile]

---


**Dibuat dengan ❤️ untuk showcase skill dan pengalaman** 
