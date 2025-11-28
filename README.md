# Personal Portfolio Website - Fariz Husain Albar

Proyek ini adalah website portofolio pribadi yang responsif, dibangun dari nol menggunakan **HTML, CSS, dan JavaScript**. Website ini dibuat untuk menampilkan profil saya sebagai mahasiswa Informatika UIN Sunan Kalijaga yang berfokus pada **Data Analyst** dan **UI/UX Design**, serta untuk melihat sertifikat dan proyek yang telah saya kerjakan.

## Demo
Anda dapat melihat tampilan website ini dengan mengunjungi tautan demo di sini: https://portofoliofarizhusainalbar.netlify.app/

## Teknologi yang Digunakan
Proyek ini dibangun menggunakan teknologi web dasar tanpa framework CSS/JS yang berat, untuk memperdalam pemahaman mengenai struktur website:

* **HTML5** - Untuk struktur semantik halaman web.
* **CSS3** - Untuk styling, layout responsif (Flexbox & Grid), dan variabel CSS (`var(--main-color)`).
* **JavaScript (Vanilla)** - Untuk interaktivitas elemen, navigasi, dan logika tampilan.

### Library Eksternal
Saya juga menggunakan beberapa library pendukung untuk mempercantik tampilan:
1.  **[ScrollReveal](https://scrollrevealjs.org/)** - Untuk memberikan efek animasi *fade-in* saat halaman di-scroll ke bawah.
2.  **[Typed.js](https://github.com/mattboldt/typed.js/)** - Untuk efek mengetik otomatis pada teks "Data Analyst" dan "UI/UX Designer".
3.  **[Boxicons](https://boxicons.com/)** - Sebagai penyedia ikon vektor (sosial media, menu, panah).

## Fitur Utama

* **Responsive Design:** Tampilan menyesuaikan dengan sempurna di berbagai perangkat (Desktop, Tablet, dan Mobile) menggunakan *Media Queries*.
* **Sticky Navbar:** Menu navigasi yang tetap terlihat di bagian atas saat pengguna melakukan scroll, dengan deteksi bagian aktif (Active Link Highlighting).
* **Smooth Scrolling:** Transisi halus saat berpindah antar bagian halaman.
* **Back to Top Button:** Tombol interaktif yang muncul saat scroll ke bawah untuk kembali ke bagian teratas halaman dengan cepat.
* **Dynamic Typing Effect:** Animasi teks dinamis pada bagian Home dan About.
* **Hover Effects:** Efek interaktif pada tombol, kartu sertifikat, dan proyek saat kursor diarahkan.

## 📂 Struktur Folder

Pastikan struktur folder Anda terlihat seperti ini agar gambar dapat dimuat dengan benar:

```text
/
├── index.html          # File utama HTML
├── style.css           # File styling CSS
├── main.js             # File logika JavaScript
├── blog.png            # Gambar profil/hero
├── sertifikat/         # Folder berisi gambar sertifikat & proyek
│   ├── sql.png
│   ├── data_science.png
│   ├── figma.png
│   └── ... (gambar lainnya)
└── README.md           # Dokumentasi proyek
