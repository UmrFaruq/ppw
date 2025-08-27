# Pengantar

## Pengantar Web Mining

Web mining merupakan proses mencari dan mengekstrak informasi yang tersedia di world wide web. Proses ini melibatkan beberapa teknik untuk mengidentifikasi pola, tren, dan hubungan. web mining juga adalah bidang multidisiplin untuk menggabungkan teknik dari data mining, kecerdasan buatan, pembelajaran mesin, dll.

## Web Crawling
    
Web Crawling adalah suatu proses penelusuran informasi yang relevan dan akurat menggunakan alat mesin pencarian yang bernama web crawler. adapun tools/library/framework yang digunakan, seperti :

- Scrapy : framework crawling yang ada di python.
    
- Selenium : Library python yang bisa mengendalikan web browser.
    
- BeautifulSoup : Library python untuk html/xml.

## Web Data Processing

Web data processing adalah proses mengolah data mentah hasil dari pencarian web(crawling/scraping). Dimana sebelum data diolah pasti ada kejanggalan seperti data tidak lengkap, tag, simbol, dan teks acak. Maka dilakukanlah prosesing data agar data bisa diolah dengan baik dan tepat. 

## Pembelajaran Terawasi (Supervised Learning)

Pembelajaran Terawasi (Supervised Learning) adalah salah satu mesin learning yang digunakan untuk membangun model prediktif menggunakan data yang berlabel, yang dimana data yang digunakan sudah memiliki label yang diinginkan. Algoritma yang sering digunakan untuk pembelajaran terawasi yaitu, Support vector machines (SVM), Decision Tree, KNN, dan random forest.     


## Pembelajaran Tak Terawasi (Unsupervised Learning)

Pembelajaran Tak Terawasi adalah kebalikannya dari pembelajaran terawasi karena tidak memiliki label / output yang diinginkan. jadi pembelajaran tidak terawasi yaitu menghasilkan data/informasi yang mentah setelah itu mencari pola sendiri menggunkana algoritma umum.

## Web Content Mining

Web Content Mining adalah mencari informasi secara otomatis yang berguna dari data / dokumen. web content mining berfokus pada pencarian gambar, audio, text, metadata, video dan hyperlink.

## Web Usage Mining

Web usage mining adalah teknik penggalian pola dalam mengakses halaman web yang ditandai melalui informasi log, click stream, cookies, dan query. Fungsi web usage mining adalah untuk mencari tahu ketertarikan pelanggan dalam produk tertentu melalui penggalian pola tersebut.

## Web Structure Mining

Web Structure Mining adalah teknik untuk mencari struktur link informasi melalui hyperlink sehingga dapat mengetahui ketertarikan dari suatu web dengan web lainnya. setelah itu digabungkan untuk membuat ringkasan informasi yang didapat. 

## Deployment System

Setelah crawling → preprocessing → modeling, langkah terakhir adalah deploy agar bisa dipakai orang lain:

-Buat API → pakai Flask / FastAPI untuk melayani prediksi.

-Integrasi Dashboard → pakai Streamlit / Dash untuk tampilan.

-Deploy ke Cloud → AWS, Google Cloud, Azure.

-Gunakan Docker → supaya mudah dipindah & reprodusibel.