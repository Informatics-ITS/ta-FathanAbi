# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Fathan Abi Karami  
**NRP**: 5025211156   
**Judul TA**: Klasifikasi Few-Shot Citra Hiperspektral Menggunakan Contrastive Learning Untuk Pemetaan Tumpahan Minyak  
**Dosen Pembimbing**: Wijayanti Nurul Khotimah, S.Kom., M.Sc., Ph.D.  
**Dosen Ko-pembimbing**: Prof. Dr. Eng. Nanik Suciati, S.Kom., M.Kom.

---

## 📺 Demo Aplikasi  
Embed video demo di bawah ini (ganti `VIDEO_ID` dengan ID video YouTube Anda):  

[![Demo Aplikasi](https://i.ytimg.com/vi/zIfRMTxRaIs/maxresdefault.jpg)](https://www.youtube.com/watch?v=VIDEO_ID)  
*Klik gambar di atas untuk menonton demo*

---

*Konten selanjutnya hanya merupakan contoh awalan yang baik. Anda dapat berimprovisasi bila diperlukan.*

## 🛠 Panduan Instalasi & Menjalankan Software  

### Prasyarat  
Python 3.12.5

CUDA

### Langkah-langkah  
1. **Clone Repository**  
   ```bash
   git clone https://github.com/Informatics-ITS/ta-FathanAbi
   ```
2. **Download Dataset**
   - download dataset pada: https://github.com/PuhongDuan/HOSD
3. **Buat virtual Environment**
   - buat virtual environment
   ```bash
   python -m venv venv_name
   ```
   - aktivasi virtual environment
   ```bash
   python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
   ```
   - register virtual environment sebagai kernel
4. **Instalasi Dependensi**
   ```bash
   pip install -r requirements.txt
   ```
   catatan: instalasi torch, torchvision, dan torchaudio berdasarkan versi dari CUDA dan model GPU yang digunakkan. Silakan merujuk ke dokumentasi resmi CUDA dan/atau GPU yang digunakkan untuk instalasi package tersebut.

5. **Jalankan Aplikasi**
   - buka folder experiment
   - pilih salah satu file eksperiment, sesuai struktur model yang diinginkan
   - konfigurasi parameter pada eksperiment (pastikan path file / folder benar)
   - running menggunakan jupyter notebook (pastikan kernelnya sesuai yang telah dibuat)

6. **Visualisasi Hasil**
   - gunakan program \visualisasi_hasil_prediksi.ipynb pada folder visualisasi
   - konfigurasi path folder yang berisikan hasil prediksi dari langkah sebelumnya
   - konfigurasi path dataset
   - gunakan kernel yang sama pada langkah sebelumnya
   - jalankan program


---

## ✅ Validasi

Pastikan proyek memenuhi kriteria berikut sebelum submit:
- Source code dapat di-build/run tanpa error
- Video demo jelas menampilkan fitur utama
- README lengkap dan terupdate
- Tidak ada data sensitif (password, API key) yang ter-expose

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: abikarami60@gmail.com
- Pembimbing Utama: wijayanti@if.its.ac.id
