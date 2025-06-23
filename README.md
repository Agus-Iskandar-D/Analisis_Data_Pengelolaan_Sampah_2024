# Analisis Data Pengelolaan Sampah 2024

----

Name: Agus Iskandar Darmawan

No: 09.009.DB2025

Task: Data Analysis with Python

----

![waste management](https://github.com/Agus-Iskandar-D/Analisis_Data_Pengelolaan_Sampah_2024/blob/main/pengelolaan%20sampah.png)

## 📖 Pendahuluan

Pengelolaan sampah di Indonesia adalah isu krusial yang memerlukan perhatian serius dari berbagai pihak, mulai dari pemerintah, sektor swasta, hingga masyarakat. Pertumbuhan populasi yang pesat, urbanisasi yang terus meningkat, dan perubahan pola konsumsi masyarakat telah berkontribusi pada peningkatan volume sampah yang signifikan. Sampah yang tidak dikelola dengan baik dapat menimbulkan berbagai dampak negatif, seperti pencemaran lingkungan (tanah, air, dan udara), gangguan kesehatan masyarakat, serta hilangnya estetika lingkungan.

Di sisi lain, pengelolaan sampah yang efektif berpotensi besar untuk menciptakan nilai tambah, baik dari aspek ekonomi (misalnya melalui daur ulang dan produksi energi dari sampah) maupun sosial (penciptaan lapangan kerja dan peningkatan kualitas hidup). Oleh karena itu, Indonesia terus berupaya untuk memperbaiki sistem pengelolaan sampahnya, dengan berbagai kebijakan dan program yang digulirkan demi mencapai target yang lebih baik di masa depan.

---

## ⚠️ Permasalahan

Meskipun telah ada berbagai upaya, pengelolaan sampah di Indonesia masih dihadapkan pada sejumlah permasalahan kompleks:

1.  **Volume Sampah yang Terus Meningkat:** Laju peningkatan volume sampah seringkali melebihi kapasitas pengelolaan yang ada. Sistem Informasi Pengelolaan Sampah Nasional (SIPSN) mencatat bahwa timbulan sampah di Indonesia mencapai 34.21 juta ton per tahun. Data menunjukkan bahwa jumlah timbulan sampah terus bertambah seiring dengan pertumbuhan ekonomi dan jumlah penduduk.
2.  **Dominasi Penimbunan (Landfilling):** Sebagian besar sampah di Indonesia masih berakhir di Tempat Pemrosesan Akhir (TPA) dengan sistem penimbunan terbuka (*open dumping*) atau *sanitary landfill* yang belum sepenuhnya memadai. Hal ini menyebabkan masalah lingkungan seperti pencemaran lindi (*leachate*) dan emisi gas metana.
3.  **Rendahnya Tingkat Daur Ulang dan Komposting:** Kesadaran dan partisipasi masyarakat dalam memilah sampah dari sumbernya masih relatif rendah. Infrastruktur untuk daur ulang dan komposting juga belum tersebar merata dan belum optimal, sehingga potensi nilai ekonomi dari sampah belum termanfaatkan secara maksimal.
4.  **Keterbatasan Infrastruktur dan Teknologi:** Banyak daerah di Indonesia masih kekurangan fasilitas pengelolaan sampah yang modern dan memadai, termasuk fasilitas pengolahan, pengangkutan, dan tempat pemrosesan akhir yang sesuai standar. Pemanfaatan teknologi pengolahan sampah yang inovatif seperti *waste-to-energy* juga masih terbatas.
5.  **Peran Serta Masyarakat yang Belum Optimal:** Meskipun ada inisiatif, partisipasi aktif masyarakat dalam pengurangan sampah, pemilahan, dan daur ulang masih perlu ditingkatkan. Edukasi dan sosialisasi mengenai pentingnya pengelolaan sampah yang bertanggung jawab masih perlu digalakkan secara lebih masif.
6.  **Regulasi dan Penegakan Hukum:** Meskipun kerangka regulasi sudah ada, implementasi dan penegakan hukum di lapangan masih menghadapi tantangan, terutama terkait sanksi bagi pelanggar.
7.  **Kapasitas Sumber Daya Manusia:** Keterbatasan sumber daya manusia yang terlatih dan ahli dalam bidang pengelolaan sampah, baik di tingkat pemerintah daerah maupun operator, menjadi kendala dalam implementasi program.
8.  **Pendanaan:** Pengelolaan sampah membutuhkan investasi yang besar. Keterbatasan anggaran di tingkat daerah seringkali menghambat pembangunan dan operasional fasilitas pengelolaan sampah yang memadai.

---

## ♻️ Pengelolaan Sampah Berdasarkan Peraturan di Indonesia

Pengelolaan sampah di Indonesia diatur secara komprehensif dalam berbagai peraturan perundang-undangan. Payung hukum utamanya adalah **Undang-Undang Nomor 18 Tahun 2008 tentang Pengelolaan Sampah**. Undang-Undang ini menjadi landasan fundamental yang mengatur hak, kewajiban, peran serta masyarakat dan pemerintah, serta sanksi terkait pengelolaan sampah. Beberapa poin penting yang diatur dalam UU No. 18 Tahun 2008 meliputi:

* **Tanggung Jawab Pengelolaan Sampah:** Menegaskan bahwa pemerintah daerah memiliki kewenangan dan tanggung jawab dalam menyelenggarakan pengelolaan sampah.
* **Hierarki Pengelolaan Sampah:** Mengutamakan prinsip *reduce, reuse, recycle* (3R) sebagai prioritas utama dalam pengelolaan sampah, sebelum proses penanganan akhir (pengolahan dan pemrosesan akhir).
* **Jenis Sampah:** Mengklasifikasikan sampah menjadi sampah rumah tangga, sampah sejenis sampah rumah tangga, dan sampah spesifik.
* **Peran Serta Masyarakat:** Mengatur kewajiban setiap orang dalam pengelolaan sampah dan mendorong peran aktif masyarakat dalam pengurangan serta penanganan sampah.
* **Sanksi:** Menyediakan ketentuan pidana bagi pelanggaran terhadap ketentuan pengelolaan sampah.

Selain UU No. 18 Tahun 2008, terdapat sejumlah peraturan turunan dan terkait yang memperkuat kerangka hukum pengelolaan sampah, antara lain:

1.  **Peraturan Pemerintah (PP) Nomor 81 Tahun 2012 tentang Pengelolaan Sampah Rumah Tangga dan Sampah Sejenis Sampah Rumah Tangga:** PP ini merupakan turunan langsung dari UU No. 18 Tahun 2008 yang menjelaskan lebih detail mengenai tata cara pengelolaan sampah rumah tangga dan sejenis sampah rumah tangga, termasuk kewajiban produsen, penyediaan fasilitas, dan sistem retribusi.
2.  **Peraturan Presiden (Perpres) Nomor 97 Tahun 2017 tentang Kebijakan dan Strategi Nasional Pengelolaan Sampah Rumah Tangga dan Sampah Sejenis Sampah Rumah Tangga (Jakstranas PSN-SRT):** Perpres ini menetapkan target dan arah kebijakan nasional dalam pengelolaan sampah hingga tahun 2025. Jakstranas menjadi panduan bagi pemerintah daerah dalam menyusun kebijakan dan strategi pengelolaan sampah di tingkat daerah (Jakstrada). Perpres ini juga menekankan pentingnya sinergi antara pusat dan daerah, serta peran aktif swasta dan masyarakat.
3.  **Peraturan Menteri Lingkungan Hidup dan Kehutanan (Permen LHK) terkait:** Berbagai Permen LHK mengatur aspek-aspek spesifik, seperti:
    * **Standar Teknis:** Persyaratan teknis untuk fasilitas pengolahan sampah (misalnya TPS 3R, TPA), serta standar baku mutu lingkungan terkait pengelolaan sampah (misalnya baku mutu lindi).
    * **Daur Ulang dan Pemanfaatan Sampah:** Aturan mengenai pemanfaatan sampah sebagai bahan baku atau sumber energi, serta mekanisme daur ulang.
    * **Pengelolaan Sampah Spesifik:** Aturan khusus untuk pengelolaan sampah elektronik, limbah B3 dari rumah tangga, dan jenis sampah spesifik lainnya.
    * **Sistem Informasi Pengelolaan Sampah Nasional (SIPSN):** Mewajibkan pemerintah daerah untuk melaporkan data pengelolaan sampah mereka ke dalam sistem informasi nasional, yang digunakan untuk monitoring dan evaluasi kinerja pengelolaan sampah.

4.  **Peraturan Daerah (Perda) dan Peraturan Kepala Daerah (Perkada):** Setiap pemerintah daerah, baik provinsi maupun kabupaten/kota, diwajibkan untuk menyusun Perda tentang pengelolaan sampah yang disesuaikan dengan karakteristik dan kebutuhan daerah masing-masing, namun tetap mengacu pada UU dan PP di atas. Perda ini seringkali mengatur tentang:
    * Retribusi pelayanan persampahan.
    * Kewajiban pemilahan sampah di sumber.
    * Sanksi lokal bagi pelanggar.
    * Penunjukan badan pelaksana pengelolaan sampah.

---

## 🎯 Target Pengelolaan Sampah Indonesia Berdasarkan Kebijakan Strategis

Pemerintah Indonesia telah menetapkan target ambisius dalam pengelolaan sampah yang tertuang dalam berbagai kebijakan strategis, terutama dalam dokumen seperti Strategi Nasional Pengelolaan Sampah Rumah Tangga dan Sampah Sejenis Sampah Rumah Tangga (Jakstranas PSN-SRT) yang ditetapkan melalui Peraturan Presiden Nomor 97 Tahun 2017. Target-target ini bertujuan untuk mengatasi permasalahan yang ada dan mendorong pengelolaan sampah yang lebih berkelanjutan. Meskipun target spesifik bisa sedikit bergeser dari waktu ke waktu atau diperbarui dalam regulasi terbaru, inti dari kebijakan strategis adalah sebagai berikut:

1.  **Pengurangan Sampah dari Sumber (*Reduce*):**
    * **Target:** Mengurangi timbulan sampah dari sumbernya, baik dari rumah tangga, sektor industri, perkantoran, maupun tempat-tempat umum. Target nasional berdasarkan Jakstranas adalah pengurangan sampah sebesar **30% pada tahun 2025**. Ini mencakup kampanye pengurangan penggunaan plastik sekali pakai, promosi penggunaan kembali barang, dan edukasi konsumen untuk membeli produk dengan kemasan minimal.
    * **Kebijakan:** Mendorong produsen untuk bertanggung jawab atas sampah produk mereka (*Extended Producer Responsibility*/EPR), mendorong pemilahan sampah di tingkat rumah tangga, dan mempromosikan gaya hidup minim sampah.

2.  **Penanganan Sampah (*Handle*) yang Lebih Baik:**
    * **Target:** Meningkatkan persentase sampah yang tertangani secara benar, artinya tidak lagi dibuang secara sembarangan atau di TPA terbuka. Penanganan ini mencakup pengumpulan, pengangkutan, pengolahan, hingga pemrosesan akhir. Target nasional berdasarkan Jakstranas adalah penanganan sampah sebesar **70% pada tahun 2025**.
    * **Kebijakan:** Peningkatan fasilitas pengolahan sampah seperti bank sampah, TPS 3R (Tempat Pengolahan Sampah *Reuse, Reduce, Recycle*), fasilitas komposting, dan fasilitas daur ulang. Pembangunan dan peningkatan kualitas TPA menjadi *sanitary landfill* atau *controlled landfill*.

3.  **Peningkatan Daur Ulang dan Pemanfaatan Energi:**
    * **Target:** Meningkatkan persentase sampah yang didaur ulang dan/atau dimanfaatkan menjadi energi. Ini adalah upaya untuk mengubah sampah dari masalah menjadi sumber daya. Meskipun target spesifik untuk daur ulang dan pemanfaatan energi terintegrasi dalam target pengurangan dan penanganan, Jakstranas secara implisit mendorong peningkatan signifikan dalam kedua area ini.
    * **Kebijakan:** Mendorong investasi dalam teknologi pengolahan sampah menjadi energi (*waste-to-energy*), seperti insinerator atau fasilitas produksi *Refuse Derived Fuel* (RDF). Mengembangkan industri daur ulang dan mendukung inovasi dalam pemanfaatan kembali sampah.

4.  **Peningkatan Partisipasi Masyarakat dan Swasta:**
    * **Target:** Melibatkan seluruh elemen masyarakat dan sektor swasta secara aktif dalam pengelolaan sampah.
    * **Kebijakan:** Mengembangkan kemitraan publik-swasta (KPS) dalam pembangunan dan operasional fasilitas pengelolaan sampah. Mengadakan program edukasi dan sosialisasi berkelanjutan untuk meningkatkan kesadaran dan partisipasi masyarakat dalam memilah dan mengelola sampah.

5.  **Penguatan Kelembagaan dan Regulasi:**
    * **Target:** Meningkatkan kapasitas kelembagaan pemerintah daerah dalam pengelolaan sampah dan menguatkan kerangka regulasi serta penegakan hukumnya.
    * **Kebijakan:** Penyusunan rencana induk pengelolaan sampah daerah (Jakstrada), peningkatan kapasitas SDM, alokasi anggaran yang memadai, serta penegakan Peraturan Daerah (Perda) terkait pengelolaan sampah.

Secara keseluruhan, Indonesia bertekad untuk mencapai pengelolaan sampah yang lebih sirkular, di mana sampah diminimalisir, didaur ulang, dan dimanfaatkan kembali sebanyak mungkin, bukan hanya dibuang ke TPA. Target tahun 2025 yang ditetapkan dalam Jakstranas menjadi acuan utama dalam upaya percepatan perbaikan pengelolaan sampah di seluruh wilayah Indonesia.

---

## 📈 Analisis Data

Data yang digunakan merupakan data pengelolaan sampah tahun 2024 yang didapat dari Sistem Informasi Pengelolaan Sampah Nasional (SIPSN). Adapun data yag digunakan mencakup data komposisi sumber sampah, data komposisi jenis sampah, data capaian pengelolaan sampah, dan data timbulan sampah dari 317 kabupaten/kota di Indonesia.

### Setup Environtment dan Librari

Environment yang digunakan menggunakan conda dengan direktori disimpan direktori EnergiHijau2025 dengan conda energi_hijau. Librari yang digunakan mencakup pandas, numpy, matplotlib, seaborn, dan jupyter

### Query Analisis Data
Query merupakan pertanyaan-pertanyaan yang ingin dijawab dengan analisis yang dilakukan menggunakan python.

#### Query 1: Mengecek Capaian Pengurangan Sampah

Tujuan: Mengecek apakah pengurangan sampah memenuhi target pengurangan sampah sebesar 30%

Konsep: If-else, Pandas untuk CSV

Output: Status capaian pengurangan sampah

```

import pandas as pd

df = pd.read_csv('C:/EnergiHijau2025/Data_Capaian_Pengelolaan_Sampah.csv')

target_pengurangan = 30

for index, row in df.iterrows():
    pengurangan = row['%Pengurangan Sampah(B/A)']
    kabupaten = row['Kabupaten/Kota']
    if pengurangan > target_pengurangan:
        print(f"{kabupaten} memenuhi target pengurangan sebesar {pengurangan} %")
    else:
        print(f"{kabupaten} BELUM memenuhi target pengurangan sebesar {pengurangan} %")

```

Output:

![pengurangans sampah](https://github.com/Agus-Iskandar-D/Analisis_Data_Pengelolaan_Sampah_2024/blob/main/capaian%20pengurangan%20sampah.png)


#### QUERY 13: Bar Chart Capaian Pengurangan Sampah

Tujuan: Menvisualisasikan pengurangan sampah dalam Bar Chart

Konsep: Metplotlib, dictionary, Pandas untuk Baca CSV

Output: Bar Chart pengurangan sampah dengan target pengurangan

```

import pandas as pd
import matplotlib.pyplot as plt

def plot_pengurangan (pengurangan_dict):
    kabupaten = list(pengurangan_dict.keys())
    pengurangan = [data['pengurangan'] for data in pengurangan_dict.values()]
    plt.bar(kabupaten, pengurangan, color = 'green')
    plt.xlabel('Kabupaten/Kota')
    plt.ylabel('Capaian Pengurangan Sampah (%)')
    plt.title('Capaian Pengurangan Sampah 2024')
    plt.axhline(y=30, color = 'red', linestyle = '--', label = 'Target Pengurangan Sampah (%)')
    plt.legend()
    plt.xticks(rotation = 90)
    plt.tight_layout()
    plt.show()

df = pd.read_csv('C:/EnergiHijau2025/Data_Capaian_Pengelolaan_Sampah.csv')
pengurangan_dict = {}
for index, row in df.iterrows():
    kabupaten = row['Kabupaten/Kota']
    pengurangan_dict[kabupaten] = {'pengurangan': row['%Pengurangan Sampah(B/A)']}

plot_pengurangan(pengurangan_dict)

```

Output:

![pengurangan sampah chart bar](https://github.com/Agus-Iskandar-D/Analisis_Data_Pengelolaan_Sampah_2024/blob/main/output%20pengurangan%20sampah.png)

#### QUERY 15: Pie Chart Komposisi Jenis Sampah

Tujuan: Menvisualisasikan Proporsi jenis sampah dari CSV

Konsep: Matplotlib, Dictionary, Pandas untuk Baca CSV

Output: Pie Chart proporsi jenis sampah

```

import pandas as pd
import matplotlib.pyplot as plt

def plot_jenis(data_df):
    
   
    Sisa_Makanan = data_df['Sisa Makanan (%)'].mean()
    Kayu_Ranting = data_df['Kayu-Ranting (%)'].mean()
    Kertas_Karton = data_df['Kertas-Karton (%)'].mean() 
    Plastik = data_df['Plastik(%)'].mean()
    Logam = data_df['Logam(%)'].mean()
    Kain = data_df['Kain(%)'].mean()
    Karet_Kulit = data_df['Karet- Kulit (%)'].mean()
    Kaca = data_df['Kaca(%)'].mean()
    Lainnya = data_df['Lainnya(%)'].mean()

    labels = [
        'Sisa Makanan', 'Kayu Ranting', 'Kertas Karton', 'Plastik',
        'Logam', 'Kain', 'Karet Kulit', 'Kaca', 'Lainnya'
    ]
    sizes = [
        Sisa_Makanan, Kayu_Ranting, Kertas_Karton, Plastik,
        Logam, Kain, Karet_Kulit, Kaca, Lainnya
    ]

    colors = [
        '#FF6347', '#3CB371', '#ADD8E6', '#FFD700', '#B0C4DE',
        '#DA70D6', '#FF8C00', '#87CEEB', '#6A5ACD'
    ] 

    plt.figure(figsize=(10, 10))
    plt.pie(sizes, labels=labels, colors=colors, autopct='%1.1f%%', startangle=90,
            pctdistance=0.85, wedgeprops={'edgecolor': 'black'}) 

    
    center_circle = plt.Circle((0, 0), 0.70, fc='white')
    fig = plt.gcf()
    fig.gca().add_artist(center_circle)

    plt.title('Komposisi Jenis Sampah 2024', fontsize=16)
    plt.axis('equal') 
    plt.show()

# --- Main Part of the Script ---
try:
    df = pd.read_csv('C:/EnergiHijau2025/Data_Komposisi_Jenis_Sampah.csv')

    plot_jenis(df)

except FileNotFoundError:
    print("Error: File 'C:/EnergiHijau2025/Data_Komposisi_Jenis_Sampah.csv' tidak ditemukan.")
except KeyError as e:
    print(f"Error: Kolom yang dibutuhkan tidak ditemukan di CSV. Pastikan nama kolom sudah benar. Missing column: {e}")
except Exception as e:
    print(f"Terjadi kesalahan: {e}")

```

Output:

![Komposisi Jenis Sampah](https://github.com/Agus-Iskandar-D/Analisis_Data_Pengelolaan_Sampah_2024/blob/main/output%20komposisi%20jenis%20sampah.png)

## 💡 Kesimpulan dan Saran

### 📝 Kesimpulan

1. Hanya beberapa Kabupaten/Kota yang sudah memenuhi target penanganan dan pengurangan sampah di 2024
2. Kompisisi jenis sampah terbesar berasal dari makanan yang merupakan sampah organik

### 🌱 Saran

1. Adanya kebijakan yang mengikat kepada masyarakat untuk buang sampah pada tempatnya dengan sudah dipilah sesuai kategori jenis sampah
2. Adanya data hasil daur ulang dan pengurangan sampah, baik yang ubah menjadi kompos, bioenergi, atau menjadi bahan baku lainnya, seperti RDF, Brick, maupun diinsenirasi (bakar)
3. Edukasi kepada masyarakat terkait sampah, dari mulai jenis sampah dan memilah sampah. Masyarakat juga bisa dilatih untuk mengolah sampah organik sendiri, minimal dengan membuat biopori.

 © ETL Batch 9 
