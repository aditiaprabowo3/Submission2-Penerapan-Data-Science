# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

### Latar Belakang Bisnis
Sejak didirikan pada tahun 2000, Jaya Jaya Institut telah menjadi salah satu institusi pendidikan tinggi yang dikenal akan kualitas pendidikannya. Dengan dukungan tenaga pengajar profesional dan kurikulum yang relevan, institusi ini telah melahirkan banyak lulusan unggulan yang mampu bersaing di dunia kerja.

Meski demikian, tantangan serius tengah dihadapi, yaitu tingginya jumlah mahasiswa yang tidak menyelesaikan studi atau mengalami dropout. Fenomena ini tidak hanya mengancam reputasi dan integritas institusi, tetapi juga memengaruhi efisiensi operasional, tingkat kelulusan, serta kepercayaan masyarakat terhadap kualitas pendidikan yang diberikan.

Guna mengatasi permasalahan tersebut, dibutuhkan pendekatan strategis berbasis data yang memungkinkan pendeteksian dini terhadap mahasiswa yang berisiko dropout. Dengan begitu, institusi dapat melakukan intervensi secara proaktif, seperti pemberian bimbingan akademik atau dukungan lainnya.

Sebagai bagian dari solusi, pengembangan dashboard pemantauan performa mahasiswa menjadi langkah penting. Dashboard ini akan membantu pihak manajemen dan pengajar dalam memantau kemajuan mahasiswa secara menyeluruh, mengidentifikasi pola-pola risiko dropout, serta mengambil keputusan yang tepat dan cepat dalam rangka menekan angka putus studi.

### Permasalahan Bisnis

Berikut adalah permasalahan bisnis yang ingin diselesaikan:

1. **Angka dropout yang masih tinggi**  
   Banyak mahasiswa yang tidak berhasil menyelesaikan masa studinya, yang berdampak negatif pada citra institusi serta pencapaian target kelulusan.

2. **Belum tersedia sistem untuk mendeteksi risiko dropout secara dini**  
   Saat ini institusi belum memiliki mekanisme analitik yang mampu mengidentifikasi mahasiswa berpotensi dropout dengan cepat dan tepat berdasarkan data yang ada.

3. **Pemantauan performa mahasiswa belum terpadu**  
   Data akademik mahasiswa masih tersebar dan belum dikemas dalam bentuk visualisasi terpadu yang memudahkan pemantauan oleh dosen dan pihak manajemen.

4. **Minimnya tindakan intervensi berbasis prediksi data**  
   Tanpa dukungan data prediktif yang jelas, langkah-langkah bimbingan dan intervensi menjadi tidak efektif karena dilakukan tanpa target yang tepat.

5. **Diperlukannya dashboard interaktif untuk monitoring performa**  
   Institusi membutuhkan platform visual yang interaktif dan mudah diakses untuk menampilkan perkembangan performa mahasiswa secara real-time dan mendukung pengambilan keputusan strategis.

### Cakupan Proyek

Proyek ini bertujuan untuk membantu **Jaya Jaya Institut** dalam menurunkan tingkat *dropout* siswa melalui pendekatan berbasis data dan visualisasi interaktif. Cakupan proyek difokuskan pada pemanfaatan data performa siswa, analisis prediktif, serta pengembangan dashboard pemantauan performa yang informatif dan mudah digunakan. Berikut adalah ruang lingkup yang dikerjakan dalam proyek ini:

1. **Pengumpulan dan Pembersihan Data**
   - Mengakses dan mengimpor data siswa dari berbagai sumber seperti sistem akademik atau data kehadiran.
   - Melakukan pembersihan data dengan mengatasi nilai duplikat, data kosong (*missing values*), dan memastikan format data konsisten.

2. **Eksplorasi dan Analisis Data (EDA)**
   - Melakukan analisis statistik awal untuk memahami karakteristik siswa dan pola-pola yang mengarah pada *dropout*.
   - Mengidentifikasi fitur-fitur penting seperti IPK, kehadiran, keterlambatan, latar belakang ekonomi, dan prestasi akademik.

3. **Pemodelan Prediktif**
   - Membangun model klasifikasi untuk memprediksi kemungkinan siswa mengalami *dropout*.
   - Menggunakan algoritma machine learning seperti:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
   - Melakukan evaluasi model menggunakan metrik akurasi, precision, recall, dan F1-score.

4. **Pembuatan Dashboard Pemantauan**
   - Mengembangkan dashboard interaktif menggunakan **Looker Studio**.
   - Dashboard menampilkan visualisasi seperti:
     - Distribusi siswa berdasarkan status (aktif/dropout).
     - Performa akademik berdasarkan jurusan, semester, dan gender.
     - Tren *dropout* per periode waktu.
     - Indikator risiko siswa terhadap *dropout* yang dapat difilter berdasarkan variabel tertentu.

5. **Integrasi dan Uji Coba Dashboard**
   - Mengintegrasikan data terbaru ke dalam dashboard secara berkala atau real-time.
   - Melakukan uji coba fungsionalitas untuk memastikan dashboard mudah digunakan oleh pengguna non-teknis.

6. **Pemberian Rekomendasi Strategis**
   - Menyusun saran berbasis hasil analisis untuk mendukung intervensi dini terhadap siswa berisiko tinggi.
   - Rekomendasi diarahkan pada kebijakan pembinaan, bimbingan akademik, dan dukungan psikososial.

7. **Dokumentasi dan Pelatihan**
   - Menyediakan dokumentasi teknis dan panduan penggunaan dashboard.
   - Memberikan pelatihan kepada tenaga pengajar dan staf akademik untuk memaksimalkan pemanfaatan dashboard dalam pengambilan keputusan.

Dengan cakupan proyek ini, diharapkan Jaya Jaya Institut dapat:
- Mendeteksi lebih awal siswa yang berisiko *dropout*.
- Mengambil langkah intervensi yang lebih tepat sasaran.
- Menurunkan angka *dropout* dan meningkatkan tingkat kelulusan secara berkelanjutan.

### Persiapan

**Sumber Data:**  

Dataset yang digunakan berasal dari Jaya Jaya Institut, sebuah institusi pendidikan tinggi yang telah berdiri sejak tahun 2000. Selama bertahun-tahun, institusi ini telah mencetak banyak lulusan dengan reputasi baik, namun juga menghadapi tantangan berupa tingginya angka siswa yang tidak menyelesaikan pendidikannya (dropout).

Tingginya angka dropout ini menjadi perhatian serius karena dapat memengaruhi citra dan kualitas institusi. Oleh karena itu, dataset ini digunakan untuk membangun model prediktif yang dapat mengidentifikasi siswa yang berpotensi mengalami dropout, sehingga intervensi atau bimbingan khusus dapat diberikan sejak dini.

Dataset dapat diakses melalui: [Students Performance Data - Dicoding Dataset](https://github.com/dicodingacademy/dicoding_dataset/blob/main/students_performance/data.csv)

**Setup Environment untuk Google Colab:**

Berikut adalah langkah-langkah untuk memulai di **Google Colab**:

1. **Buka Google Colab:**
   - Akses [Google Colab](https://colab.research.google.com/).
   - Buat notebook baru dengan memilih **New Notebook**.

2. **Mengimpor Library yang digunakan**

Untuk memulai proyek ini di **Google Colab**, kita perlu mengimpor beberapa library yang akan digunakan dalam proses data manipulation, visualisasi, preprocessing, pemodelan, dan evaluasi. Berikut adalah daftar library yang akan digunakan:

```python
# 1. Import semua library yang diperlukan
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler, LabelEncoder
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.svm import SVC
from sklearn.metrics import classification_report, confusion_matrix, accuracy_score
import xgboost as xgb
from sklearn.metrics import accuracy_score
import joblib
from sklearn.utils import resample
from sklearn.utils import shuffle
```
3. **Menyiapkan Dataset yang Digunakan**

Pada langkah ini, kita akan memulai dengan membaca dataset yang telah disediakan dan melakukan pemeriksaan awal terhadap data yang ada. Dataset ini akan digunakan untuk analisis lebih lanjut.

```python
# Membaca dataset
dataset = "https://raw.githubusercontent.com/dicodingacademy/dicoding_dataset/main/students_performance/data.csv"
df = pd.read_csv(dataset, sep=';')
```

Setelah membaca dataset, kita akan menampilkan beberapa informasi awal, seperti 5 data teratas, tipe data dari setiap kolom, jumlah nilai unik untuk setiap kolom kategorikal, serta analisis deskriptifnya.

```python
# Menampilkan 5 data teratas
df.head()
```

```python
# Menampilkan informasi tipe data dan missing values
df.info()
```
```python
# Menampilkan jumlah nilai unik tiap kolom kategorikal
print("\nNilai unik untuk kolom kategorikal:")
for col in df.select_dtypes(include='object').columns:
    print(f"{col}: {df[col].nunique()} nilai unik")
```
```python
# Mengecek jumlah nilai NULL
df.isnull().sum()
```
```python
# Menampilkan statistik deskriptif
df.describe()
```

Langkah-langkah ini penting untuk memahami struktur dataset yang kita gunakan serta mengecek adanya data yang hilang (missing values), yang perlu ditangani sebelum melakukan analisis lebih lanjut.

### 4. **Data Preparation / Preprocessing**

Pada tahap ini, dilakukan beberapa langkah persiapan data agar dapat digunakan secara optimal untuk proses analisis dan pemodelan machine learning. Karena dataset yang digunakan tidak memiliki nilai kosong (*missing values*), maka proses pembersihan data lebih difokuskan pada eksplorasi dan transformasi data numerik dan kategorikal.

Langkah pertama adalah mengidentifikasi dan memvisualisasikan distribusi data numerik. Hal ini bertujuan untuk melihat pola penyebaran dan mendeteksi potensi *outlier* pada setiap fitur numerik.

```python
# Kolom numerik
numerical_cols = df.select_dtypes(include=['int64', 'float64']).columns

# Plot distribusi
plt.figure(figsize=(15, 10))
for i, col in enumerate(numerical_cols[:6]):
    plt.subplot(2, 3, i+1)
    sns.histplot(df[col], kde=True)
    plt.title(f'Distribusi {col}')
plt.tight_layout()
plt.show()
```

Selanjutnya, dilakukan visualisasi data kategorikal untuk mengetahui frekuensi kemunculan tiap kategori dalam kolom yang bersifat kategorikal.

```python
# Kolom kategorikal
categorical_cols = df.select_dtypes(include='object').columns

# Plot frekuensi
plt.figure(figsize=(15, 10))
for i, col in enumerate(categorical_cols[:6]):
    plt.subplot(2, 3, i+1)
    df[col].value_counts().plot(kind='bar')
    plt.title(f'Frekuensi {col}')
    plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```
Kemudian, dilakukan analisis korelasi antar fitur numerik untuk mengetahui hubungan antar variabel menggunakan matriks korelasi.

```python
# Matriks korelasi
plt.figure(figsize=(12, 8))
corr_matrix = df.corr(numeric_only=True)
sns.heatmap(corr_matrix, annot=True, fmt=".2f", cmap='coolwarm')
plt.title("Matriks Korelasi")
plt.show()
```
Kolom target Status yang semula berupa label kategorikal (Dropout dan Graduate) kemudian dikonversi menjadi nilai numerik menggunakan LabelEncoder.

```python
# Encode target label (Status)
le_status = LabelEncoder()
df['Status'] = le_status.fit_transform(df['Status'])  # Graduate=0, Dropout=1
```
Data kemudian dipisahkan menjadi fitur numerik dan fitur kategorikal. Fitur numerik akan dinormalisasi, dan fitur kategorikal akan diencode agar dapat diterima oleh algoritma machine learning.

```python
# Pisahkan fitur numerik dan kategorikal
categorical_cols = df.select_dtypes(include=['object']).columns.tolist()
numerical_cols = df.select_dtypes(include=['int64', 'float64']).columns.tolist()
numerical_cols.remove('Status')  # Jangan encode target

# Encode kolom kategorikal (jika ada)
for col in categorical_cols:
    df[col] = LabelEncoder().fit_transform(df[col])
```
Terakhir, data dipisahkan menjadi fitur (X) dan target (y), lalu dilakukan standarisasi terhadap fitur numerik menggunakan StandardScaler.

```python
# Fitur dan target
X = df.drop('Status', axis=1)
y = df['Status']

# Standarisasi fitur numerik
scaler = StandardScaler()
X[numerical_cols] = scaler.fit_transform(X[numerical_cols])
```
Dengan preprocessing ini, data sudah siap untuk digunakan dalam proses pelatihan model prediksi status kelulusan siswa. 

5. **Model Training**

Pada tahap ini, kita akan membagi dataset menjadi data pelatihan dan data pengujian. Kemudian, kita akan melatih beberapa model machine learning untuk memprediksi nilai 'Status Siawa' (Apakah Siswa tersebut akan di Dropout/Graduate/Enrolled).

Kita akan membagi dataset menjadi dua bagian: data pelatihan (80%) dan data pengujian (20%).

```python
# Split data menjadi train dan test
X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, random_state=42, stratify=y)

print("Jumlah data latih:", X_train.shape)
print("Jumlah data uji:", X_test.shape)
```

Beberapa model machine learning yang akan digunakan untuk melatih data antara lain: Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), dan XGBoost.

```python
# Melatih model
models = {
    'Logistic Regression': LogisticRegression(max_iter=1000),
    'Decision Tree': DecisionTreeClassifier(),
    'Random Forest': RandomForestClassifier(),
    'KNN': KNeighborsClassifier(),
    'SVM': SVC(),
    'XGBoost': xgb.XGBClassifier(use_label_encoder=False, eval_metric='logloss')
}

# Pelatihan semua model
for name, model in models.items():
    model.fit(X_train, y_train)
```

6. **Menyimpan Hasil Evaluasi Model**

Setelah melatih model, langkah selanjutnya adalah mengevaluasi kinerja masing-masing model menggunakan data pengujian (test data). Evaluasi dilakukan menggunakan metrik-metrik seperti akurasi, precision, recall, dan F1-Score.

**Evaluasi Model Menggunakan Data Pengujian**  
Berikut adalah kode untuk melakukan prediksi menggunakan model yang telah dilatih dan menghitung metrik evaluasi untuk masing-masing model.

```python
# Menyimpan hasil evaluasi
results = []

for name, model in models.items():
    y_pred = model.predict(X_test)
    acc = accuracy_score(y_test, y_pred)
    report = classification_report(y_test, y_pred, output_dict=True, zero_division=0)

    results.append({
        "Model": name,
        "Akurasi": acc,
        "Precision": report['weighted avg']['precision'],
        "Recall": report['weighted avg']['recall'],
        "F1-Score": report['weighted avg']['f1-score']
    })

# Konversi ke DataFrame untuk tampilan tabel
results_df = pd.DataFrame(results)
results_df = results_df.sort_values(by="Akurasi", ascending=False).reset_index(drop=True)

# Tampilkan hasil evaluasi model dalam bentuk tabel
print("📊 Hasil Evaluasi Model:\n")
print(results_df.to_string(index=False))

# Menampilkan model dengan akurasi tertinggi
best_model = results_df.iloc[0]
print(f"\n✅ Model terbaik adalah: {best_model['Model']} dengan akurasi: {best_model['Akurasi']:.4f}")
```

Didapatkan hasil evaluasinya seperti ini :
## 📊 Hasil Evaluasi Model

| Model               | Akurasi  | Precision | Recall   | F1-Score |
|---------------------|----------|-----------|----------|----------|
| Random Forest       | 0.771751 | 0.757113  | 0.771751 | 0.755995 |
| Logistic Regression | 0.768362 | 0.749981  | 0.768362 | 0.753128 |
| XGBoost             | 0.767232 | 0.760310  | 0.767232 | 0.762175 |
| SVM                 | 0.759322 | 0.747835  | 0.759322 | 0.746566 |
| Decision Tree       | 0.693785 | 0.699507  | 0.693785 | 0.696455 |
| KNN                 | 0.666667 | 0.649668  | 0.666667 | 0.655683 |

✅ **Model terbaik adalah:** Random Forest dengan akurasi **0.7718**

## Business Dashboard

![Screenshot (1780)](https://github.com/user-attachments/assets/8f96bc19-651e-4cda-a5b4-a372a60b814e)

Dashboard ini merupakan **Dashboard Analitik Mahasiswa** yang bertujuan untuk memvisualisasikan data terkait **status akademik mahasiswa** berdasarkan berbagai faktor seperti status pendaftaran, kelompok usia, jurusan, serta rata-rata nilai semester. Dashboard ini membantu institusi pendidikan dalam memantau performa mahasiswa dan mengidentifikasi potensi masalah seperti dropout.

### Fitur-Fitur Dashboard

1. **Distribusi Mahasiswa Berdasarkan Status**
   - Menampilkan persentase mahasiswa dengan status:
     - **Graduate**: 49.6%
     - **Dropout**: 32.1%
     - **Enrolled**: 17.9%
   - Ditampilkan dalam bentuk diagram lingkaran.

2. **Jumlah Total Mahasiswa**
   - Tercatat sebanyak **4.424 mahasiswa** yang dianalisis dalam dashboard ini.

3. **Nilai Rata-Rata Semester**
   - **Grade Semester 1**: 10,64  
   - **Grade Semester 2**: 10,23

4. **Status Mahasiswa Berdasarkan Kelompok Usia**
   - Visualisasi menunjukkan distribusi status (Dropout, Graduate, Enrolled) berdasarkan kelompok umur: 17–20, 21–24, 25–29, 30–35, dan >35 tahun.

5. **Rata-Rata Nilai Semester Berdasarkan Status**
   - Menampilkan rata-rata nilai semester 1 dan semester 2 untuk setiap kategori status mahasiswa:
     - Graduate memiliki nilai tertinggi.
     - Dropout memiliki rata-rata nilai terendah.

### Akses Dashboard

[Dashboard Looker Studio](https://lookerstudio.google.com/reporting/f1870669-99d3-4ffb-9269-2d5d3a17f725)

---

## Tujuan Dashboard:

- Memantau kinerja akademik mahasiswa
- Meningkatkan tingkat kelulusan
- Mengurangi angka droupout
- Mengidentifikasi mahasiswa berisiko droupout
- Mendukung pengambilan keputusan berbasis data
- Mengevaluasi efektivitas program akademik
- Memfasilitasi komunikasi antar departemen akademik

## Menjalankan Sistem Machine Learning

Untuk menjalankan prototype sistem machine learning yang telah dibuat, ikuti langkah-langkah berikut ini:

> **Link Akses Streamlit**: [Lihat di StreamlitOnline](https://aditiaprabowo3submission2-penerapan-data-science-cxutdepbmbzyz.streamlit.app/)

![screencapture-aditiaprabowo3submission2-penerapan-data-science-cxutdepbmbzyz-streamlit-app-2025-05-29-14_47_42](https://github.com/user-attachments/assets/50135b8a-5f7d-4fd1-aa09-1e1663f7579c)

Untuk menjalankan proyek ini secara lokal, silakan ikuti panduan berikut:

### Clone Repository

Clone repositori ke komputer lokal Anda menggunakan perintah berikut:

```bash
git clone https://github.com/aditiaprabowo3/Submission2-Penerapan-Data-Science.git
cd Business-Dashboard
python -m venv env
venv\Scripts\activate
pip install -r requirements.txt

```
### Menjalankan Prediksi pada streamlit
```bash
streamlit run app.py
```

## Conclusion
Melalui analisis data dan visualisasi interaktif dalam bentuk business dashboard, beberapa insight penting berhasil diperoleh:

- Mayoritas mahasiswa berada pada status **Graduate** (49,6%), diikuti oleh **Dropout** (32,1%), dan **Enrolled** (17,9%).
- Jumlah mahasiswa tertinggi berada pada kelompok usia **17–20 tahun**, yang didominasi oleh status Graduate, Dropout dan Enrolled.
- Mahasiswa dengan status **Graduate** memiliki **rata-rata nilai semester tertinggi**, sedangkan mahasiswa **Dropout** cenderung memiliki nilai terendah.
- Terdapat penurunan nilai rata-rata dari Semester 1 (10.64) ke Semester 2 (10.23), menunjukkan adanya penurunan performa akademik.

---

### Rekomendasi Action Items

1. **Program Intervensi Dini untuk Mahasiswa Rentan Dropout**  
  Identifikasi mahasiswa dengan performa rendah dan lakukan pendekatan akademik atau konseling untuk meningkatkan keterlibatan belajar.

2. **Analisis Lanjutan Berdasarkan Jurusan**  
  Evaluasi jurusan dengan tingkat Dropout tinggi untuk mengetahui penyebabnya, apakah dari kurikulum, metode pengajaran, atau faktor eksternal lainnya.

3. **Optimalisasi Bimbingan Akademik**  
  Tingkatkan peran dosen pembimbing untuk memantau perkembangan mahasiswa dan memberikan dukungan yang tepat waktu.

4. **Penyesuaian Strategi Pengajaran Berdasarkan Usia**  
  Sesuaikan pendekatan pembelajaran dengan karakteristik kelompok usia tertentu agar lebih efektif dalam mendorong kelulusan.

5. **Pemanfaatan Data Secara Berkelanjutan**  
  Gunakan dashboard ini sebagai alat monitoring berkala untuk pengambilan keputusan berbasis data dalam meningkatkan performa akademik secara menyeluruh.
