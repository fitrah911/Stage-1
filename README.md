# PulangPegi

Anan Agrani
Augita Dewabrata
Aulia Gita Pratiwi
Dhyana Rara Ayu Gandini
Fitrah Alamsyah
Khalid Atthariq Wiraguna Aseran

## Descriptive Statistics
1. Apakah ada kolom dengan tipe data kurang sesuai, atau nama kolom dan isinya kurang sesuai?
○ Tidak ada, semua data sudah sesuai
○ axs
2. Apakah ada kolom yang memiliki nilai kosong? Jika ada, apa saja?
○ Terdapat 4 kolom yang memiliki missing value atau nilai kosong yaitu :

-`Children` : 4 kolom atau 0.003%

-"Country` : 488 kolom atau  0.409%

- `Agent` : 16.340 kolom atau  13.686 %

- `Company` : 112.593 kolom atau 94.307%

- axs
3. Apakah ada kolom yang memiliki nilai summary agak aneh?
○ Yang aneh dari summary statistics dataset Hotel Booking adalah :
1. Nilai minimal `adult` 0, tidak mungkin babies/children check in sendiri tanpa adanya
orang yang lebih dewasa
2. Nilai minimal `adr` negatif

## Multivariate Analysis
1. Bagaimana korelasi antara masing-masing feature dan label. Kira-kira feature mana saja yang paling
relevan dan harus dipertahankan?
○ Semua data relevan, sehingga tidak ada data yang di drop kecuali kolom yang membuat
multicollinearity
○ asx
2. Bagaimana korelasi antar-feature, apakah ada pola yang menarik? Apa yang perlu dilakukan terhadap
feature itu?
○ Terdapat beberapa kolom yang menyebabkan multicollinearity, yaitu:
- Kolom `stays_in_week_nights` dan `stays_in_weekend-nights` yang memiliki nilai korelasi 0,5
yang menyebabkan multicollinearity, sehingga salah satu dari kolom akan di drop
- Kolom `arrival_date_year` dan `arrival_date_week_number` yang memiliki nilai korelasi -0,54
yang menyebabkan multicollinearity, sehingga salah satu dari kolom akan di drop
○ asx
3. Tuliskan juga jika memang tidak ada feature yang saling berkorelasi
○ Semua kolom memiliki korelasi satu sama lain