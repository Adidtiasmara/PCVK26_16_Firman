<div align="center">

# PCVK 2026 — Pengolahan Citra & Visi Komputer

Kumpulan jobsheet dan tugas praktikum mata kuliah Pengolahan Citra dan Visi Komputer.

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-cv2-5C3EE8?logo=opencv&logoColor=white)](https://opencv.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![Status](https://img.shields.io/badge/status-in%20progress-yellow)]()

</div>

---

## Identitas

| | |
|---|---|
| **Nama** | Muhammad Firman Aditiasmara |
| **Mata Kuliah** | Pengolahan Citra dan Visi Komputer |
| **Repositori** | [Adidtiasmara/PCVK26_16_Firman](https://github.com/Adidtiasmara/PCVK26_16_Firman) |

---

## Daftar Notebook

| Pertemuan | Topik | Notebook | Buka |
|---|---|---|---|
| D1 | Dasar citra digital & manipulasi kanal warna | `P2_Tugas_D1_16.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adidtiasmara/PCVK26_16_Firman/blob/main/P2_Tugas_D1_16.ipynb) |
| D2 | Pembuatan repositori & dasar praktikum | `P1_Tugas_D2_16.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adidtiasmara/PCVK26_16_Firman/blob/main/P1_Tugas_D2_16.ipynb) |
| Minggu 3 | Transformasi intensitas & akuisisi citra | `week3_16.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adidtiasmara/PCVK26_16_Firman/blob/main/week3_16.ipynb) |
| Minggu 5 | Histogram & equalization | `Week5_16.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adidtiasmara/PCVK26_16_Firman/blob/main/Week5_16.ipynb) |
| Minggu 6 | Spasial filter & filter modern | `Week6_16.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Adidtiasmara/PCVK26_16_Firman/blob/main/Week6_16.ipynb) |

---

## Materi yang Dipelajari

### D1 — Dasar Citra Digital
- Perbedaan urutan warna **BGR** (OpenCV) dan **RGB** (Matplotlib)
- Menampilkan citra dengan `cv2_imshow()` dan `plt.imshow()`
- Tipe data citra: `int16` vs `int32` (memori & rentang nilai)
- Kombinasi kanal warna dan pencerminan (vertikal, horizontal, keduanya)

### Minggu 3 — Transformasi Intensitas
- Transformasi **brightness** linier, **kontras**, dan **logaritmik**
- Konversi **grayscale**: averaging, lightness, dan luminance
- Selektif warna (mempertahankan satu warna, sisanya grayscale)
- Simulasi *image depth*, *average denoising*, dan *image masking*
- Akuisisi citra malam hari

### Minggu 5 — Histogram & Equalization
- Histogram manual, `numpy.histogram`, dan `cv.calcHist`
- Histogram ternormalisasi `p(j)` dan kurva **CDF**
- Pengaruh jumlah **bin** terhadap detail histogram
- **Histogram equalization** manual vs `cv.equalizeHist()`
- Equalization per kanal vs ruang warna **YCrCb / HSV / LAB**
- Tugas **dithering**

### Minggu 6 — Spasial Filter
- **Mean filter** vs **median filter** pada noise *salt and pepper*
- Pemilihan ukuran kernel **sharpening** (3×3 vs 5×5)
- **Filter kartun**: bilateral filter + adaptive threshold + `bitwise_and`

---

## Tools & Library

| Kategori | Tools |
|---|---|
| Bahasa | Python 3 |
| Pengolahan citra | OpenCV (`cv2`), scikit-image |
| Komputasi & visualisasi | NumPy, Matplotlib |
| Lingkungan | Google Colab |

---

## Struktur Repo

```
PCVK26_16_Firman/
├── P1_Tugas_D2_16.ipynb    # Praktikum D2
├── P2_Tugas_D1_16.ipynb    # Praktikum D1
├── week3_16.ipynb          # Jobsheet Minggu 3
├── Week5_16.ipynb          # Jobsheet Minggu 5
├── Week6_16.ipynb          # Jobsheet Minggu 6
└── README.md
```

---

## Cara Menjalankan

**Lewat Google Colab (disarankan):**
Klik tombol **Open in Colab** pada tabel di atas.

**Secara lokal:**
```bash
pip install opencv-python numpy matplotlib scikit-image
jupyter notebook
```

Notebook memuat citra dari Google Drive pada path
`/content/drive/MyDrive/PCVK/Gambar`. Sesuaikan path tersebut jika dijalankan lokal.

---

<div align="center">

**Muhammad Firman Aditiasmara** · 2026

</div>
