# Lab3Web
## Praktikum 3: CSS Dasar

Laporan praktikum ini dibuat untuk memenuhi tugas mata kuliah **Pemrograman Web** di Universitas Pelita Bangsa. Modul ini membahas mengenai pengenalan Cascading Style Sheet (CSS), aturan penulisan, selector, serta cara pengaplikasiannya pada dokumen HTML.

---

## Langkah-Langkah

### 1. Membuat Dokumen HTML (`lab2_css_dasar.html`)
Langkah awal adalah membuat struktur dasar dokumen HTML yang berisi elemen header, navigasi, dan konten utama dengan ID dan Class.

<img width="1516" height="808" alt="image" src="https://github.com/user-attachments/assets/349e9dd8-2fca-4337-b164-e7de9b001247" />


### 2. Mendeklarasikan CSS Internal
Menambahkan tag `<style>` di bagian `<head>` dokumen HTML untuk mengatur *styling* dasar seperti jenis font, *header*, dan tag `h1`.

<img width="1081" height="539" alt="internal CSS" src="https://github.com/user-attachments/assets/3ba7699e-d1a1-4f6e-b45f-648eb9d5c6b2" />


### 3. Menambahkan Inline CSS
Menambahkan atribut `style` secara langsung pada tag `<p>` paragraf untuk mengubah perataan teks dan warna secara spesifik pada baris tersebut.

<img width="1433" height="220" alt="image" src="https://github.com/user-attachments/assets/fab7e483-ba22-4c98-989a-2f13e3b30b47" />


### 4. Membuat CSS Eksternal (`style_eksternal.css`)
Membuat file CSS terpisah dengan cara menambahkan <link rel="stylesheet" href="style_eksternal.css" type="text/css">, untuk mengatur bagian navigasi menu (`<nav>`) agar lebih rapi serta memberikan efek interaktif saat kursor diarahkan (*hover*).

<img width="1752" height="639" alt="eksternal fie dan nav" src="https://github.com/user-attachments/assets/b6df79de-4992-452c-b47f-8de743cde557" />

<img width="898" height="403" alt="nav dan eksternal file" src="https://github.com/user-attachments/assets/360a295d-3f1e-497b-974b-b540fd862475" />



### 5. Menambahkan CSS Selector (ID & Class Selector)
Menambahkan aturan penataan menggunakan **ID Selector** (`#intro`) untuk membungkus kotak konten utama dan **Class Selector** (`.button`, `.btn-primary`) untuk mempercantik tampilan tombol.

<img width="862" height="322" alt="CSS selector" src="https://github.com/user-attachments/assets/326df41f-0b5c-45b3-b395-ff3d5e517792" />
