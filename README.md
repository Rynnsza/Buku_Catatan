📚 Buku Catatan
* "Buku Catatan" adalah aplikasi catatan pribadi sederhana yang memungkinkan Anda membuat, menyimpan, mencari, dan mengelola catatan secara digital. 
* Aplikasi ini dikembangkan menggunakan React dan memanfaatkanLocal Storage browser untuk penyimpanan data yang persisten.

✨ Fitur Utama
* Tambah Catatan Baru: Membuat catatan baru dengan judul dan isi. 
* Terdapat batasan maksimal 50 karakter untuk judul catatan.
* Pencarian Cepat: Fitur pencarian memungkinkan Anda memfilter daftar catatan berdasarkan judul secara real-time.
* Arsip Catatan: Pisahkan catatan aktif dari catatan yang sudah selesai atau jarang digunakan dengan fitur Arsipkan/Unarsipkan.
* Persistensi Data: Catatan Anda secara otomatis disimpan dan dimuat ulang menggunakan Local Storage browser.
* Tampilan Terpisah: Daftar catatan aktif dan catatan terarsipkan ditampilkan dalam bagian yang berbeda.
* Format Tanggal Lokal: Tanggal pembuatan dicetak dalam format bahasa Indonesia (id-ID).

💻 Teknologi yang Digunakan
* TeknologiVersiPeranReact^18.0.0
* Pustaka JavaScript untuk membangun antarmuka pengguna.Vite^4.3.9
* Alat bundling dan dev server yang cepat.
* Local Storage APIN/AMekanisme penyimpanan data persisten di sisi klien.
* HTML, CSS, JavaScript (JSX)N/ABahasa dasar pengembangan web.

🔧 Prasyarat InstalasiUntuk menjalankan proyek ini secara lokal, 
* Anda harus memiliki:Node.js (Disarankan versi LTS)
* npm atau Yarn (Aplikasi ini menggunakan npm untuk lockfile)

📂 Susunan Proyek rynnsza/
* buku_catatan/
* ├── dist/                 
* ├── public/               
* ├── src/
* │   ├── components/       
* │   ├── styles/           
* │   ├── utils/            
* │   ├── App.jsx           
* │   └── index.jsx         
* ├── .gitignore
* ├── index.html            
* ├── package.json
* └── README.md             

🚀 Contoh Penggunaan
Ikuti langkah-langkah di bawah ini untuk menjalankan aplikasi pada mesin lokal Anda:
* Kloning Repositori:Bashgit clone [URL_REPOSITORI_ANDA]
* cd buku_catatan

Instalasi Dependensi:
* Bashnpm install
  atau
* yarn install
Menjalankan Aplikasi dalam Mode Pengembangan (Development):Aplikasi akan berjalan pada http://localhost:5173 (port default Vite).
* Bashnpm run dev
 atau
* yarn dev
Membangun Proyek untuk Produksi (Production):Hasil build akan disimpan di folder dist/.
* Bashnpm run build
 atau
* yarn build

