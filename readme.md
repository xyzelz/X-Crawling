<h1 align="center">🐦 Twitter Keyword Crawler & Preprocessor</h1>

<p align="center">
  Crawl tweet dari <strong>Twitter</strong> berdasarkan kata kunci lalu lakukan <em>pembersihan dan preprocessing teks</em> menggunakan Python 🐍
</p>

---

## 🚀 Fitur Unggulan

🔍 **Cari otomatis berdasarkan keyword tertentu**  
📥 **Ambil tweet** menggunakan `snscrape`  
🧹 **Preprocessing teks**: tokenisasi, lowercase, hapus tanda baca  
🛑 **Stopword removal**  
🌱 **Stemming Bahasa Indonesia** dengan `Sastrawi`  
📊 **Simpan hasil akhir ke CSV**

---

## 🗂️ Struktur Proyek

```bash
.
├── x crawling.ipynb     # Notebook utama untuk crawling dan preprocessing
├── requirements.txt     # Daftar dependensi
└── README.md            # Dokumentasi ini
```

---

## 🧪 Cara Penggunaan

### 1. Clone repo

```bash
git clone https://github.com/xyzelz/X-Crawling.git
cd X-Crawling
```

### 2. Install dependensi

```bash
pip install -r requirements.txt
```

### 3. Jalankan notebook

Buka file `x crawling.ipynb` menggunakan Jupyter Notebook atau VS Code.

🗣 Masukkan **kata kunci** yang ingin dicari.  
📁 Hasil crawling dan preprocessing akan tersimpan sebagai file `.csv`.

---

## ⚙️ Proses Preprocessing

1. **Lowercasing**  
2. **Hapus tanda baca dan angka**  
3. **Tokenisasi** (split teks menjadi kata)  
4. **Stopword removal**  
5. **Stemming** dengan library `Sastrawi`

Contoh input-output:

| Teks Asli                                      | Setelah Preprocessing                    |
|------------------------------------------------|------------------------------------------|
| "Makan gratis di warteg dekat stasiun!"        | makan gratis warteg dekat stasiun        |

---

## 🛠 Teknologi yang Digunakan

- Python 3.x  
- `snscrape`  
- `pandas`  
- `re`  
- `Sastrawi`  
- `nltk` (opsional)

---

## 📌 Catatan Penting

- ❌ **Bukan proyek resmi Twitter**
- 🧠 Hanya untuk keperluan **edukasi dan penelitian**
- 📉 Pastikan tidak melebihi batas pemakaian wajar dari sumber data

---

## 🤝 Kontribusi

Kontribusi sangat terbuka!  
Silakan fork, kembangkan fitur, atau bantu perbaiki bug.  
Buka issue atau pull request jika ada ide 💡

---

## 👤 Author

Made with ❤️ by [@xyzelz](https://github.com/xyzelz)  
📬 Hubungi jika ada pertanyaan atau ide tambahan

---

⭐ **Berikan bintang** jika kamu merasa proyek ini bermanfaat!
