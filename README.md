# -PerancanganWeb-DesainGrafis-BisDig

file:///C:/xampp/htdocs/xampp/citra%201.html


# PerancanganWeb-DesainGrafis-BisDig

Repositori ini berisi berbagai proyek terkait perancangan web dan desain grafis.

---

## Proyek 1: Halaman Profil Fotografer Profesional

**Deskripsi:**
Proyek ini mendemonstrasikan pembuatan halaman profil web yang sederhana namun fungsional untuk seorang fotografer profesional. Halaman ini memuat informasi dasar seperti deskripsi diri, galeri karya, dan tautan media sosial.

**Struktur:**
* `index.html`: Berkas utama yang berisi struktur HTML halaman profil.
* `style.css`: Berkas untuk styling (tampilan) halaman menggunakan CSS.

---

## Proyek 2: Komentar Dinamis dengan JavaScript (Tombol "Tampilkan Komentar")

**Deskripsi:**
Proyek ini menunjukkan bagaimana JavaScript dapat digunakan untuk menambahkan interaktivitas sederhana pada halaman web, khususnya fitur "Tampilkan Komentar" pada sebuah blog post. Komentar tidak akan langsung terlihat saat halaman dimuat, melainkan muncul dan bisa disembunyikan kembali dengan mengklik sebuah tombol.

**Teknologi yang Digunakan:**
* HTML5 untuk struktur dasar.
* CSS untuk styling tampilan.
* JavaScript untuk interaktivitas dinamis (menyembunyikan/menampilkan elemen).

**Cara Kerja:**
1.  Secara default, kontainer komentar disembunyikan menggunakan properti CSS `display: none;`.
2.  Sebuah tombol "Tampilkan Komentar" disediakan.
3.  Ketika tombol diklik, JavaScript akan:
    * Mendeteksi status tampilan komentar (tersembunyi atau terlihat).
    * Mengubah properti `display` dari kontainer komentar antara `none` dan `block` (atau `flex`/`grid` tergantung tata letak) secara bergantian.
    * Mengubah teks tombol antara "Tampilkan Komentar" dan "Sembunyikan Komentar" agar sesuai dengan aksi yang tersedia.

**Struktur File:**
* `index.html`: Berkas HTML utama yang mengandung artikel blog, komentar, tombol, dan kode JavaScript inline untuk fungsionalitas ini.
* *(Opsional: Anda bisa memisahkan JavaScript ke file `.js` terpisah dan CSS ke file `.css` terpisah untuk proyek yang lebih besar)*

## Cara Menggunakan

1.  **Clone repositori ini:**
    ```bash
    git clone [https://github.com/USERNAME/PerancanganWeb-DesainGrafis-BisDig.git](https://github.com/USERNAME/PerancanganWeb-DesainGrafis-BisDig.git)
    ```
    (Ganti `USERNAME` dengan nama pengguna GitHub Anda)
2.  **Buka `index.html`:** Anda dapat membuka berkas `index.html` langsung di browser web favorit Anda untuk melihat hasilnya.

## Kustomisasi

Anda dapat dengan mudah mengkustomisasi proyek-proyek ini:

* **Halaman Profil Fotografer:**
    * Ganti teks dan gambar dengan informasi fotografer yang sebenarnya.
    * Sesuaikan styling di `style.css`.
* **Komentar Dinamis:**
    * Ubah konten artikel dan komentar.
    * Sesuaikan styling CSS untuk tombol dan komentar.
    * (Untuk proyek lebih lanjut) Pindahkan kode JavaScript ke file terpisah (`script.js`) dan tautkan di HTML menggunakan `<script src="script.js"></script>`.

## Lisensi

Proyek ini bersifat open source dan tersedia di bawah Lisensi MIT.
