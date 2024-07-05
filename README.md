# Prediksi Harga Uber dan Lyft di Boston Menggunakan Linear Regression

buka link berikut untuk detail projectnya : <a href="https://github.com/fachriansyahmh/Prediksi_Harga_Uber_dan_Lyft_di_Boston_Menggunakan_Linear_Regression/blob/main/PYTN_KampusMerdeka_FP1_Fachriansyah-Muhammad-Haikal.ipynb" target="_blank">Project</a>

## Latar Belakang

Seiring berjalannya waktu, pertumbuhan penduduk di dunia semakin meningkat, begitu pula dengan pertumbuhan penduduk di kota Boston, New York. Hal ini menyebabkan peningkatan kebutuhan masyarakat di kota Boston, termasuk kebutuhan akan transportasi publik seperti Uber dan Lyft. Uber dan Lyft adalah dua perusahaan layanan transportasi berbasis aplikasi yang menyediakan layanan ride-sharing atau car-sharing. Mereka memungkinkan pengguna untuk memesan perjalanan melalui aplikasi di ponsel, di mana pengemudi yang terdaftar akan menjemput dan mengantar mereka ke tujuan yang diinginkan.

Pada tahun 2015, Kota Boston memperkenalkan dataset mengenai Uber dan Lyft sebagai bagian dari program "Digital Bridge" yang bertujuan untuk meningkatkan transportasi umum dan mendorong penggunaan teknologi dalam sistem transportasi perkotaan. Tujuan utama dari diperkenalkannya dataset ini adalah untuk memberikan akses terbuka kepada para peneliti, pengembang, dan masyarakat umum untuk menganalisis data perjalanan ride-sharing dan menghasilkan wawasan yang berharga. Untuk membantu masyarakat Kota Boston memilih transportasi publik yang lebih terjangkau, diperlukan adanya sistem prediksi harga transportasi publik yang menyediakan layanan ride-sharing atau car-sharing (Uber dan Lyft) di Kota Boston dengan menggunakan model Linear Regression.

## Dataset

Dataset yang digunakan dalam proyek ini adalah **Uber and Lyft Dataset Boston**, yang berisi data perjalanan transportasi publik dengan layanan ride-sharing atau car-sharing di kota Boston. Dataset ini memiliki 693,071 entri dengan 57 atribut. Namun, dalam proyek ini, hanya 11 atribut yang digunakan untuk membuat sistem prediksi, yaitu:

- `hour`: Waktu pemesanan transportasi
- `day`: Tanggal pemesanan transportasi
- `month`: Bulan pemesanan transportasi
- `source`: Titik jemput
- `destination`: Titik antar
- `cab_type`: Jenis perusahaan transportasi
- `name`: Tipe layanan transportasi
- `price`: Harga layanan
- `distance`: Jarak tempuh (destination-source)
- `surge_pricing`: Mekanisme kenaikan harga yang dipicu oleh tingginya permintaan transportasi di suatu daerah
- `short_summary`: Cuaca

## Objektif

1. Menemukan faktor-faktor yang mempengaruhi harga/tarif pada layanan Uber dan Lyft.
2. Menemukan akurasi prediksi harga/tarif pada layanan Uber dan Lyft dengan menggunakan metode Linear Regression.
3. Memberikan wawasan yang dapat bermanfaat bagi masyarakat di kota Boston mengenai layanan Uber dan Lyft.

## Pengambilan Kesimpulan

### Faktor-Faktor

Dapat diketahui faktor-faktor yang mempengaruhi harga/tarif pada layanan Uber dan Lyft, antara lain:

- Waktu (`hour`)
- Tanggal (`day`)
- Bulan (`month`)
- Perusahaan (`cab_type`)
- Tipe layanan (`name`)
- Jarak (`distance`)
- Kenaikan harga (`surge_pricing`)
- Cuaca (`short_summary`)

### Akurasi

Berdasarkan Coefficient of Determination sebesar 93.30%, model Linear Regression ini dapat memprediksi harga transportasi publik (Uber dan Lyft) dengan akurasi yang tinggi.

### Wawasan

Beberapa wawasan yang ditemukan dalam layanan Uber dan Lyft adalah sebagai berikut:

1. **Jam Keberangkatan**:
   - Tarif layanan akan meningkat pada jam-jam padat seperti jam berangkat atau pulang kerja. Misalnya, pada jam 07.00 tarif layanan lebih mahal dibandingkan dengan jam keberangkatan yang lebih sepi.
   
2. **Cuaca**:
   - Tarif layanan akan meningkat pada saat cuaca hujan. Misalnya, biaya layanan lebih murah pada saat cuaca terang dan berawan dibandingkan saat cuaca hujan.
   
3. **Jenis Layanan**:
   - Perbedaan jenis layanan yang dipilih juga memengaruhi tarif layanan. Misalnya, tarif Lyft XL lebih mahal dibandingkan dengan layanan Lyft biasa.

## Kesimpulan

Proyek ini berhasil mengidentifikasi faktor-faktor yang mempengaruhi harga/tarif pada layanan Uber dan Lyft di kota Boston dan membangun model prediksi harga dengan akurasi tinggi menggunakan metode Linear Regression. Wawasan yang diperoleh dapat digunakan oleh masyarakat untuk membuat keputusan yang lebih terinformasi mengenai penggunaan layanan ride-sharing atau car-sharing di Boston.
