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
- Daftar dependensi (contoh):
  - asttokens               3.0.0
  - colorama                0.4.6
  - comm                    0.2.2
  - contourpy               1.3.2
  - cycler                  0.12.1
  - daal                    2025.5.0
  - debugpy                 1.8.14
  - decorator               5.2.1
  - executing               2.2.0
  - filelock                3.13.1
  - fonttools               4.58.1
  - fsspec                  2024.6.1
  - ipykernel               6.29.5
  - ipython                 9.3.0
  - ipython_pygments_lexers 1.1.1
  - jedi                    0.19.2
  - Jinja2                  3.1.4
  - joblib                  1.5.1
  - jupyter_client          8.6.3
  - jupyter_core            5.8.1
  - kiwisolver              1.4.8
  - MarkupSafe              2.1.5
  - matplotlib              3.10.3
  - matplotlib-inline       0.1.7
  - mpmath                  1.3.0
  - nest-asyncio            1.6.0
  - networkx                3.3
  - numpy                   2.1.2
  - packaging               25.0
  - pandas                  2.2.3
  - parso                   0.8.4
  - pillow                  11.0.0
  - pip                     24.0
  - platformdirs            4.3.8
  - prompt_toolkit          3.0.51
  - psutil                  7.0.0
  - pure_eval               0.2.3
  - Pygments                2.19.1
  - pyparsing               3.2.3
  - python-dateutil         2.9.0.post0
  - pytz                    2025.2
  - pywin32                 310
  - pyzmq                   26.4.0
  - scikit-learn            1.6.1
  - scikit-learn-intelex    2025.5.0
  - scipy                   1.15.3
  - setuptools              70.2.0
  - six                     1.17.0
  - spectral                0.24
  - stack-data              0.6.3
  - sympy                   1.13.1
  - tbb                     2022.1.0
  - tcmlib                  1.3.0
  - threadpoolctl           3.6.0
  - torch                   2.5.1+cu121
  - torchaudio              2.5.1+cu121
  - torchvision             0.20.1+cu121
  - tornado                 6.5.1
  - tqdm                    4.67.1
  - traitlets               5.14.3
  - typing_extensions       4.12.2
  - tzdata                  2025.2
  - wcwidth                 0.2.13

### Langkah-langkah  
1. **Clone Repository**  
   ```bash
   git clone https://github.com/Informatics-ITS/ta-FathanAbi
   ```
2. **Download Dataset**
   - download dataset pada: https://github.com/PuhongDuan/HOSD
3. **Buat virtual Environment**
   - buat virtual environment
   - aktivasi virtual environment
   ```bash
   python -m venv venv_name
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
