# suprize.me 🎁😹

Halaman web statis kejutan interaktif dari **Anak TI** yang memutar efek suara lucu saat dibuka.

### ✨ Fitur Utama

* **Kejutan Audio Langsung:** Dilengkapi pemutar audio bawaan yang langsung memutar file `kucing-ketawa.mp3` di halaman yang sama tanpa membuka tab baru.
* **Animasi Interaktif:** Ikon kado otomatis bergoyang lucu saat suara sedang diputar.
* **Desain Bersih & Responsif:** Tampilan minimalis yang nyaman dibuka melalui *smartphone* maupun desktop menggunakan Tailwind CSS CDN.

### 📁 Struktur Repository

Pastikan struktur folder di dalam *root* repository Anda terlihat seperti berikut agar halaman dan audio berjalan lancar:

~~~text
suprize.me/
├── index.html          # Halaman utama beserta logika pemutar audio
├── kucing-ketawa.mp3   # File audio kejutan yang akan diputar saat tombol diklik
└── README.md           # Dokumentasi repository
~~~

### 🚀 Cara Deploy di GitHub Pages

1. Pastikan file `index.html` dan `kucing-ketawa.mp3` sudah terunggah ke dalam *root* repository ini.
2. Buka tab **Settings** pada repository GitHub Anda.
3. Pilih menu **Pages** di bilah navigasi sebelah kiri.
4. Pada bagian **Build and deployment** > **Branch**, pilih branch `main` (atau `master`) dengan folder `/ (root)`, lalu klik **Save**.
5. Tunggu beberapa saat hingga GitHub selesai memproses, dan tautan kejutan Anda siap dibagikan!

### 🛠️ Kustomisasi

Jika ingin mengganti efek suara atau teks di kemudian hari, cukup sesuaikan bagian berikut di dalam `index.html`:

**1. Ganti File Suara**
Ubah nama file pada atribut `src` di dalam elemen audio:
~~~html
<audio id="catAudio" src="kucing-ketawa.mp3" preload="auto"></audio>
~~~

**2. Ubah Teks & Pengirim**
Sesuaikan teks judul atau *badge* pengirim sesuai kebutuhan:
~~~html
<h1 class="text-2xl font-bold text-gray-900 tracking-tight mb-3">
    Hihu!
</h1>
~~~

---
Dibuat iseng-iseng berhadiah oleh **Anak TI** untuk **Suprize.me**. Hihu!