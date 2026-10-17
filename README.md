# UTS Machine Learning - 241011400683

**Identitas Mahasiswa**
- Nama: BAGUS HERMAWAN
- NIM: 241011400683
- Kelas: Reg B

**Link Repo:** https://github.com/hermawan098/uts-machine-learning-241011400683

## Ringkasan Hasil

Analisis data periklanan untuk prediksi dengan Logistic Regression.

- **Model:** Logistic Regression (Manual Gradient Descent vs Sklearn)
- **Akurasi:** 0.7333 (73.33%) - Hasil identik antara manual dan sklearn
- **Koefisien Manual:** b = -12.91, m = 1.14
- **Koefisien Sklearn (L2, C=1.0):** b = -12.25, m = 1.07
- **Koefisien Sklearn (Tanpa Penalty):** b = -17.80, m = 1.59

### Kesimpulan Perbandingan
1. Akurasi sama membuktikan implementasi manual sigmoid, loss, dan gradient descent sudah benar.
2. Perbedaan nilai b/m wajar karena Sklearn default pakai Regularisasi L2 (penalty=L2, C=1.0) untuk cegah overfitting.
3. Tanpa penalty, nilai koefisien Sklearn lebih mendekati manual.

## File
- tugas_UTS.ipynb - notebook lengkap
- Ads_Data.csv & Email_Data.csv - dataset
