# Panduan Instalasi Python 3.11.9 & Visual Studio Code (VS Code)

**Mata Kuliah: Machine Learning**

Panduan ini dirancang agar Anda memiliki lingkungan kerja yang stabil. Jika langkah-langkah teks di bawah ini membingungkan, silakan merujuk ke bagian **Panduan Video** di akhir dokumen.

---

### 1. Instalasi Python 3.11.9

Python 3.11.9 adalah versi yang kita gunakan untuk menjaga kompatibilitas library machine learning.

**Untuk Windows:**

1.  Buka [python.org/downloads/windows](https://www.python.org/downloads/windows).
2.  Cari **"Python 3.11.9 - April 2, 2024"** dan unduh **Windows installer (64-bit)**.
3.  **PENTING:** Saat menjalankan installer, **WAJIB** mencentang kotak **"Add Python to PATH"** di bagian bawah.
4.  Klik **Install Now**.
5.  Di akhir instalasi, jika muncul opsi **"Disable path length limit"**, klik opsi tersebut agar Python dapat menangani lokasi file yang panjang.

**Untuk macOS:**

1.  Buka [python.org/downloads/macos](https://www.python.org/downloads/macos).
2.  Unduh **macOS 64-bit universal2 installer** untuk versi 3.11.9.
3.  Buka file `.pkg` dan ikuti instruksi hingga selesai.
4.  _Catatan:_ macOS memiliki Python bawaan sistem. Pastikan nanti di VS Code Anda memilih versi 3.11.9 yang baru diinstal.

---

### 2. Instalasi Visual Studio Code (VS Code)

1.  Unduh di [code.visualstudio.com](https://code.visualstudio.com/).
2.  **Windows:** Saat instalasi, centang semua opsi "Other", termasuk **"Add 'Open with Code' action"** agar memudahkan Anda membuka folder proyek.
3.  **macOS:** Tarik aplikasi VS Code ke folder **Applications**.

---

### 3. Konfigurasi Extension di VS Code

Buka VS Code, tekan `Ctrl+Shift+X` (Windows) atau `Cmd+Shift+X` (Mac), lalu instal:

- **Python** (oleh Microsoft): Untuk dukungan bahasa dan fitur cerdas.
- **Jupyter** (oleh Microsoft): Untuk menjalankan file `.ipynb`.

---

### 4. Uji Coba & Verifikasi

1.  Buka Terminal di VS Code letakannya di menu **Terminal > New Terminal**.
2.  Ketik `python --version` (Windows) atau `python3 --version` (Mac).
3.  Pastikan output yang keluar adalah **Python 3.11.9**.

---

### 5. Instalasi Library Utama

Jalankan perintah ini di Terminal VS Code untuk menginstal semua kebutuhan praktikum:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn yellowbrick
```

---

### 6. Panduan Video & Troubleshooting (Jika Gagal)

Jika Anda mengalami kendala seperti "Python not recognized" atau kesulitan konfigurasi, silakan ikuti panduan visual yang sangat lengkap melalui tautan berikut:

- **Pengguna Windows:** [Tutorial Instalasi Python & VS Code di Windows](https://youtu.be/xETkm9H6aaY)
  - _Tips:_ Perhatikan bagian menit 02:15 tentang pengecekan **Add Python to Path**.
- **Pengguna macOS:** [Tutorial Instalasi Python & VS Code di macOS](https://youtu.be/HSAm6s10G7g)
  - _Tips:_ Video ini menjelaskan cara menggunakan `Homebrew` dan `pyenv` untuk manajemen versi yang lebih rapi (metode profesional).

---

**Tips Tambahan:**
Jika laptop Anda memiliki spesifikasi rendah atau instalasi tetap gagal setelah melihat video, Anda bisa menggunakan **[Google Colab](https://colab.research.google.com/)** sebagai alternatif tanpa perlu instalasi apa pun.
