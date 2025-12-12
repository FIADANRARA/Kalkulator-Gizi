# 🥗GIZI ANTI RIBET: Kalkulator AKG Lagrange

## Selamat Datang di NutriMatch !

Halo NutriPeeps si pelajar dan pejuang hidup sehat!
<div align="center">
<img src="https://raw.githubusercontent.com/FIADANRARA/Kalkulator-Gizi/main/Gizimo.gif" width="220"/>
</div>

Kenalin aku **Gizimo**, maskot ceria dari NutriMatch! 🥑✨

Aku ada di sini buat bantu kalian cek kebutuhan gizi harian dengan cara yang:
- gampang ✔  
- cepat ✔  
- akurat banget ✔  

Yuk, bareng aku kita hitung AKG kamu pake metode keren: **Interpolasi Lagrange!**  
Ayo hidup sehat tanpa ribet!

### 🖼 Klik Link di bawah ini ya
<img width="960" height="428" alt="image" src="https://github.com/user-attachments/assets/9e829e1d-13f5-4b10-9a3d-2b9873958cb2" />

**Klik di bawah ini!👇** 
<div align="center">

<a href="https://kalkulator-gizi-chaciwsfvtwi9xxvkz6tlj.streamlit.app/" target="_blank">
  <img src="https://img.shields.io/badge/OPEN%20NUTRIMATCH-Click%20Here!-ff69b4?style=for-the-badge&logo=streamlit&logoColor=white" />
</a>
</div>
 

---

## Kenapa sih NutriPeeps harus nyoba kalkulator ini?

Soalnya banyak kalkulator gizi di luar sana yang cuma ngegas ke angka bulat terdekat atau umurnya dibuletin, berat badan dibuletin.
Padahal tubuh kita kan nggak hidup dari pembulatan💀

Nah kalau di sini beda!
Gizimo pakai ilmu pasti: Interpolasi Lagrange biar hasilnya bener-bener presisi, sesuai kamu, sesuai angka kamu, bukan angka tetangga ✨

### Otak di Balik Akurasi: Interpolasi Lagrange

Gizimo membangun sebuah model matematika untuk mengisi celah antara data AKG standar (titik-titik rujukan).

| Fitur | Manfaat untuk Anda |
| :--- | :--- |
| **Interpolasi Lagrange** | Menghasilkan kurva yang melewati *semua* titik data AKG rujukan. |
| **Estimasi Presisi** | Jika Berat Badan (BB) Anda 67,5 kg, kami tidak membulatkannya ke 60 kg atau 70 kg. Kami hitung AKG yang persis untuk 67,5 kg. |
| **Personalisasi** | Hasil yang Anda dapatkan adalah AKG (x) yang spesifik, di mana x adalah Berat Badan Anda. |

#### Konsep Inti:

Metode ini menggunakan Polinomial Lagrange P(x) untuk menentukan nilai gizi y berdasarkan Berat Badan x Anda.

**1. Rumus Polinomial Lagrange:**


![Rumus Polinomial Lagrange](polinomial_lagrange.png)



**2. Rumus Basis Polinomial:**


![Rumus Basis Polinomial Lagrange](basis_lagrange.png)

---

## 💻 Detail Proyek (The Engine Room)

Proyek ini adalah implementasi dari pembelajaran mata kuliah Metode Numerik yang disajikan dalam bentuk aplikasi web yang siap pakai.

* **Bahasa:** Python
* **Kerangka Kerja Web:** [Streamlit](https://streamlit.io/) (Membuat aplikasi data interaktif menjadi sangat cepat).

## 🛠️ Tim Kontributor

| Nama | NIM |
| :--- | :--- |
| **Aliffia Hilva Salsabila** | K1323006 |
| **Fauziah Rahmawati Sholehah** |K1323026 |


## 📜 Lisensi & Status

Proyek ini **Aktif** dan dikembangkan untuk tujuan edukasi dan kesehatan masyarakat.
* **Versi Saat Ini:** v1.0.0 (Stabil)
