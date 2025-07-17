# UAS Keamanan Komputer

## Identitas
- Nama: Firman Febrian Jaya Rustan
- NIM: 221080200064
- Kelas: Pengamanan Sistem Komputer 6/B4
- Repo GitHub: [https://github.com/firmanj03/project-uas-pengamanan/edit/main/template_jawaban.md]

---

## Bagian A – Bug Fixing JWT REST API

### Bug 1: Token tetap aktif setelah logout
**Penjelasan:**  
.Karena JWT tidak ada mekanisme  validasi

**Solusi:**  
.Hapus Refresh token dari server
- masukkan acces token ke dalam daftar blacklist


## Bagian B – Simulasi Serangan dan Solusi

### Jenis Serangan: Broken Access Control  
**Simulasi Postman:**  
...

**Solusi Implementasi:**  
...

---

## Bagian C – Refleksi Teori & Etika

### 1. CIA Triad dalam Keamanan Informasi  
- Confidentiality  Memastikan informasi hanya dapat diakses oleh pihak yang berwenang. Contoh: enkripsi data.
- Integrity , Menjamin bahwa data tidak dimodifikasi atau diubah secara tidak sah. Contoh: hash, checksums.
- Avaibility , Memastikan bahwa informasi dan sistem dapat diakses oleh pengguna yang berwenang saat dibutuhkan. Contoh: backup.

### 2. UU ITE yang relevan  
-Pasal 30 akses ilegal ke sistem elektronik
-pasal  32 perusakan, pengubahan, penghapusan data

### 3. Pandangan Al-Qur'an  
- Surah Al-Baqarah: 205  
ayat ini menggambarkan sifat orang yang tampakbaik di depam umum,tetapi saat tidak di awasi justru berbuat kerusakan terhadaptatanan kehidupan,termasuk sistem sosial, ekonomi, dan lingkungan

### 4. Etika Cyber dan Kejujuran  
-Tidak Menyalahgunakan akses
- Transparansi dalam insiden
- Menjaga kerahasiaan data
-menginformasikan publik secara transparan
