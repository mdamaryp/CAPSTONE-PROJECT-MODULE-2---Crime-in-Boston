# CAPSTONE-PROJECT-MODULE-2---Crime-in-Boston

CAPSTONE PROJECT MODULE 2
MUHAMMAD DAMAR YULIAN PRAKARSA
Crime in Boston
Data : https://www.kaggle.com/datasets/AnalyzeBoston/crimes-in-boston

# Latar Belakang

Pimpinan dari **Police Department** ingin merekrut seorang *data scientist* untuk menganalisa insiden yang terjadi di kota Boston, Massachusetts. Data yang akan digunakan memiliki periode 14 Juni 2015 - 3 September 2018. Hasil analisa data kriminal ini akan digunakan police departmen untuk mengatur dan merancang rencana kerja yang diharapkan akan menekan angka insiden atau semacamnya, serta untuk mengidentifikasi kejahatan apa yang sering terjadi di suatu lokasi, agar dapat mengantisipasi dan menyesuaikan polisi yang akan betugas.

# Pernyataan Masalah
**Police Department** ingin mengetahui insiden apa dan dimana lokasi yang sering terjadi. Dari informasi tersebut dapat menentukan kesiapan, tidakan dan strategi apa yang akan dilakukan untuk mengurangi angka terjadinya suatu insiden.

Sebagai seorang *data analyst*, kita akan mencoba menjawab pertanyaan berikut:
1. Bagaimana trend **angka insiden** di kota Boston?
2. Bagaimana trend **jenis insiden** di kota Boston? (Pengaruh terhadap tindakan yang perlu dilakukan)
3. Dimana distrik yang paling banyak insiden terjadi? 
4. Dimanakah titik spesifik yang paling sering terjadi suatu insiden?
5. Insiden apa yang menyebabkan adanya penembakan?

Dataset ini berisi informasi terkait kejahatan di kota boston. Ada 17 kolom di dalam dataset ini, yaitu:  

* INCIDENT_NUMBER       = ID unik untuk tiap incident
* OFFENSE_CODE          = Data ini menunjukkan ID jenis kejahatan
* OFFENSE_CODE_GROUP    = Nama dari setiap jenis kejahatan
* OFFENSE_DESCRIPTION   = Penjelasan kejahatan tertentu. (dapat digunakan untuk penyelidikan lebih lanjut)
* DISTRICT              = Kode zona
* REPORTING_AREA        = Nomor area yang dilaporkan kejahatan.
* SHOOTING              = Jika kejahatan terjadi tembakan, itu ditunjukkan dengan 'Y'
* OCCURRED_ON_DATE      = waktu kejahatan yang tepat. (tahun, bulan, hari dan waktu)
* YEAR                  = 2015,2016,2017,2018
* MONTH                 = bulan terjadinya kejahatan
* DAY_OF_WEEK           = minggu terjadinya kejahatan
* HOUR                  = jam terjadinya kejahatan
* UCR_PART              = Jenis Pelaporan Kejahatan
* STREET                = nama jalan tempat kejahatan terjadi
* Lat                   = garis lintang lokasi terjadinya kejahatan
* Long                  = garis bujur lokasi terjadinya kejahatan
* Location              = letak lintang dan bujur yang bersamaan dengan terjadinya kejahatan.
