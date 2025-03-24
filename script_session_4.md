# **Naskah Presentasi - MediaWiki Acknowledgement**

## **1. Pembuka**
**Durasi: 3 menit**  
Assalamu’alaikum warahmatullahi wabarakatuh.  
Selamat pagi/siang/sore Bapak/Ibu dan teman-teman sekalian.  
Terima kasih telah hadir dalam sesi ini.  

Hari ini, kita akan membahas tentang **MediaWiki**, sebuah perangkat lunak yang menjadi dasar dari berbagai situs wiki, termasuk Wikipedia.  

Selama presentasi ini, kita akan melihat sejarahnya, fitur-fiturnya, teknologi yang digunakannya, serta penerapannya dalam berbagai bidang.  

Mari kita mulai dengan membahas sejarah MediaWiki.

---

## **2. Sejarah MediaWiki**
Awal Mula Wikipedia dan Kebutuhan akan Perangkat Lunak yang Lebih Baik
MediaWiki lahir dari kebutuhan Wikipedia, ensiklopedia daring yang didirikan oleh Jimmy Wales dan Larry Sanger pada tahun 2001. Pada awalnya, Wikipedia menggunakan perangkat lunak UseModWiki yang ditulis dalam bahasa pemrograman Perl. Namun, seiring dengan meningkatnya jumlah artikel dan pengguna, UseModWiki tidak mampu menangani beban kerja yang semakin besar. Oleh karena itu, pengembang mulai mencari solusi yang lebih efisien.

Pengembangan Phase II oleh Magnus Manske (2002)
Pada awal tahun 2002, Magnus Manske, seorang kontributor Wikipedia, mengembangkan perangkat lunak baru yang dikenal sebagai "Phase II". Perangkat lunak ini dibuat menggunakan PHP dan database MySQL untuk meningkatkan kinerja dan efisiensi dibandingkan dengan UseModWiki. Wikipedia secara resmi beralih ke Phase II pada Januari 2002, tetapi sistem ini masih mengalami masalah skalabilitas.

Rancang Ulang oleh Lee Daniel Crocker: Lahirnya MediaWiki (2003)
Untuk mengatasi masalah kinerja yang masih ada, pengembang Lee Daniel Crocker merancang ulang perangkat lunak Wikipedia, yang kemudian disebut sebagai "Phase III". Versi ini dirancang untuk lebih efisien dan dapat menangani lalu lintas yang lebih besar. Pada pertengahan tahun 2003, perangkat lunak ini diberi nama MediaWiki dan menjadi dasar dari sistem yang digunakan oleh Wikipedia hingga saat ini.

Adopsi oleh Yayasan Wikimedia (2004-2005)
Setelah Wikipedia mulai berkembang pesat, MediaWiki diadopsi secara resmi oleh Wikimedia Foundation dan mulai digunakan untuk proyek-proyek lainnya seperti Wikimedia Commons, Wikibooks, dan Wiktionary. Selain itu, MediaWiki dirilis sebagai perangkat lunak sumber terbuka, memungkinkan siapa saja untuk menggunakannya dalam proyek mereka sendiri.

Perkembangan Ekstensi dan Fitur Baru (2006-2010)
MediaWiki berkembang dengan banyak fitur baru, termasuk sistem caching, format parsing yang lebih canggih, dan ekstensi yang dapat memperluas fungsinya. Pada periode ini, ekstensi ParserFunctions, Semantic MediaWiki, dan CheckUser diperkenalkan untuk meningkatkan fleksibilitas dan keamanan sistem. Popularitas MediaWiki meningkat dan mulai digunakan oleh berbagai organisasi di luar Wikimedia.

Pengenalan VisualEditor (2013)
Salah satu tantangan utama MediaWiki adalah sintaks wiki yang sulit dipahami oleh pengguna baru. Untuk mengatasi ini, pada tahun 2013 Wikimedia Foundation merilis VisualEditor, sebuah editor berbasis WYSIWYG (What You See Is What You Get) yang memungkinkan pengguna menyunting halaman tanpa perlu memahami sintaks kode wiki. Meskipun awalnya kontroversial karena berbagai bug, VisualEditor terus diperbaiki dan menjadi alat yang lebih umum digunakan.

Dukungan untuk Perangkat Seluler dan Aksesibilitas yang Lebih Baik (2015-2018)
Dengan meningkatnya penggunaan perangkat seluler, MediaWiki mulai mengoptimalkan tampilannya agar lebih ramah bagi pengguna mobile. Selain itu, fitur Content Translation diperkenalkan untuk membantu penerjemahan artikel antar bahasa, yang membantu pertumbuhan konten Wikipedia di berbagai bahasa di dunia.

Peningkatan Keamanan dan Integrasi API (2019-2021)
Keamanan menjadi fokus utama dalam pengembangan MediaWiki di era modern. Pada periode ini, MediaWiki menambahkan fitur autentikasi dua faktor, perlindungan terhadap serangan DDoS, dan peningkatan enkripsi. Selain itu, MediaWiki mulai beralih ke model arsitektur berbasis REST API untuk mendukung integrasi dengan aplikasi pihak ketiga dan meningkatkan interoperabilitasnya.

Desain Antarmuka Baru dan Mode Gelap (2022-2023)
MediaWiki terus mengalami perubahan tampilan agar lebih modern dan mudah digunakan. Salah satu perubahan terbesar adalah pengenalan Vector 2022, sebuah tema baru yang lebih responsif dan ramah pengguna. Selain itu, mode gelap mulai diperkenalkan untuk meningkatkan kenyamanan membaca, terutama bagi pengguna yang mengakses Wikipedia di malam hari.

MediaWiki di Masa Depan (2024 dan Seterusnya)
MediaWiki terus dikembangkan dengan berbagai inovasi, termasuk peningkatan dukungan kecerdasan buatan untuk moderasi konten dan rekomendasi artikel. Selain itu, MediaWiki semakin diintegrasikan dengan layanan cloud dan platform lainnya untuk meningkatkan fleksibilitas dan aksesibilitas. Dengan komunitas pengembang yang aktif dan dukungan dari Wikimedia Foundation, MediaWiki tetap menjadi salah satu perangkat lunak wiki paling populer di dunia.

Sejarah MediaWiki mencerminkan bagaimana perangkat lunak ini berkembang dari proyek kecil menjadi tulang punggung dari salah satu ensiklopedia daring terbesar di dunia, serta menjadi alat penting bagi berbagai komunitas dan organisasi di seluruh dunia.

---

## **3. Timeline Pengembangan MediaWiki**
MediaWiki adalah perangkat lunak wiki sumber terbuka yang digunakan untuk menjalankan Wikipedia dan berbagai proyek Wikimedia lainnya. Berikut adalah garis waktu pengembangannya dalam 10 paragraf yang menggambarkan evolusi MediaWiki dari awal hingga perkembangannya saat ini.

Awal Mula (2002)
MediaWiki berawal dari perangkat lunak wiki sederhana bernama UseModWiki yang digunakan dalam Wikipedia sejak 2001. Namun, dengan semakin meningkatnya jumlah artikel dan pengguna, UseModWiki tidak lagi mampu menangani beban kerja yang tinggi. Oleh karena itu, pada awal 2002, Magnus Manske, seorang pengembang dan kontributor Wikipedia, mengembangkan perangkat lunak baru yang lebih efisien dan memiliki fitur lebih baik. Perangkat lunak ini kemudian dikenal sebagai "Phase II".

Penggantian UseModWiki (2002)
Pada bulan Januari 2002, Wikipedia beralih dari UseModWiki ke perangkat lunak baru yang dikembangkan oleh Magnus Manske. Meskipun lebih canggih dibandingkan pendahulunya, perangkat lunak ini masih menghadapi masalah kinerja. Oleh karena itu, pengembangan terus dilakukan untuk meningkatkan skalabilitas dan kecepatan sistem.

Lahirnya MediaWiki (2003)
Pada pertengahan 2002, pengembang lain bernama Lee Daniel Crocker merancang ulang sistem yang lebih efisien, yang kemudian disebut sebagai "Phase III". Versi ini akhirnya diberi nama MediaWiki dan diimplementasikan di Wikipedia pada pertengahan 2003. MediaWiki dirancang dengan basis PHP dan menggunakan MySQL untuk penyimpanan data, membuatnya lebih kuat dalam menangani lalu lintas pengguna yang tinggi.

Ekspansi ke Proyek Wikimedia Lainnya (2004-2005)
Setelah kesuksesan Wikipedia, MediaWiki mulai digunakan dalam berbagai proyek Wikimedia lainnya seperti Wikimedia Commons, Wiktionary, dan Wikibooks. Pada tahun 2004, Yayasan Wikimedia secara resmi merilis MediaWiki sebagai perangkat lunak sumber terbuka yang dapat digunakan oleh siapa saja untuk membuat dan mengelola situs wiki mereka sendiri.

Peningkatan Skalabilitas dan Fitur Baru (2006-2010)
Seiring dengan semakin besarnya Wikipedia dan proyek-proyek Wikimedia lainnya, MediaWiki terus mengalami pengembangan. Pada periode ini, banyak fitur baru diperkenalkan, seperti sistem caching untuk meningkatkan kecepatan, dukungan XML, dan fitur parser yang lebih canggih. Selain itu, ekstensi-ekstensi populer seperti VisualEditor dan Semantic MediaWiki mulai dikembangkan untuk memperluas fungsionalitas MediaWiki.

Pengenalan Editor Visual (2013)
Salah satu tantangan utama MediaWiki adalah antarmuka pengeditannya yang berbasis teks, yang kurang ramah bagi pengguna awam. Oleh karena itu, pada tahun 2013, Wikimedia Foundation memperkenalkan VisualEditor, sebuah editor visual yang memungkinkan pengguna mengedit artikel tanpa perlu memahami sintaks wiki. Meskipun awalnya mendapat banyak kritik, VisualEditor terus diperbaiki dan kini menjadi salah satu fitur utama di Wikipedia.

Dukungan untuk Mobile dan Performa Lebih Cepat (2015-2018)
Dengan meningkatnya penggunaan perangkat seluler, MediaWiki mulai menyesuaikan diri dengan tren ini. Pada periode ini, banyak peningkatan dilakukan pada tampilan dan antarmuka seluler untuk membuat pengalaman pengguna lebih nyaman. Selain itu, fitur Content Translation diperkenalkan untuk memudahkan penerjemahan artikel antar bahasa, mempercepat pertumbuhan konten di Wikipedia dalam berbagai bahasa.

Peningkatan Keamanan dan Stabilitas (2019-2021)
Seiring dengan meningkatnya ancaman keamanan siber, MediaWiki mulai menerapkan fitur keamanan yang lebih ketat, seperti autentikasi dua faktor dan peningkatan perlindungan terhadap serangan DDoS. Selain itu, pengembangan arsitektur baru dengan REST API juga mulai dilakukan untuk meningkatkan kompatibilitas MediaWiki dengan aplikasi pihak ketiga.

Pengembangan Mode Gelap dan Antarmuka Baru (2022-2023)
Dalam beberapa tahun terakhir, MediaWiki mengalami perubahan signifikan dalam desain antarmukanya. Salah satu pengembangan utama adalah Vector 2022, tema baru yang dirancang agar lebih modern dan responsif di berbagai perangkat. Selain itu, mode gelap mulai diperkenalkan untuk meningkatkan kenyamanan pengguna yang lebih suka membaca dalam kondisi cahaya rendah.

Masa Depan MediaWiki (2024 dan Seterusnya)
MediaWiki terus berkembang dengan berbagai inovasi, termasuk peningkatan kecerdasan buatan untuk membantu penyuntingan otomatis dan analisis konten. Selain itu, dengan meningkatnya kebutuhan terhadap interoperabilitas, MediaWiki berfokus pada pengembangan API yang lebih fleksibel agar lebih mudah diintegrasikan dengan aplikasi dan layanan lain. Ke depannya, MediaWiki akan terus menjadi tulang punggung Wikipedia dan berbagai proyek wiki lainnya di seluruh dunia

---

## **4. Teknologi di Balik MediaWiki**
MediaWiki adalah perangkat lunak sumber terbuka yang digunakan untuk mengelola berbagai situs berbasis wiki, termasuk Wikipedia. Perangkat lunak ini dikembangkan dengan teknologi yang memungkinkan skalabilitas tinggi, keamanan yang ketat, dan kemudahan penggunaan. Berikut adalah beberapa teknologi utama yang digunakan dalam MediaWiki.

1. Bahasa Pemrograman: PHP
MediaWiki dikembangkan menggunakan PHP, bahasa pemrograman skrip yang sering digunakan untuk pengembangan web. PHP memungkinkan MediaWiki menjalankan berbagai fungsi seperti pemrosesan teks, manajemen halaman, dan integrasi dengan basis data. Dengan optimasi yang terus-menerus, MediaWiki dapat menangani jutaan permintaan setiap harinya di Wikipedia dan proyek-proyek lainnya.

2. Database: MySQL dan MariaDB
Untuk menyimpan data, MediaWiki menggunakan MySQL atau MariaDB, yang merupakan sistem manajemen basis data relasional (RDBMS). Database ini menyimpan halaman, revisi, metadata, dan log aktivitas pengguna. Pemilihan MySQL/MariaDB memungkinkan MediaWiki menangani beban kerja besar dengan efisien melalui mekanisme indeks dan replikasi data.

3. Sistem Caching untuk Performa Cepat
MediaWiki menggunakan beberapa metode caching untuk meningkatkan kecepatan akses halaman. Beberapa teknologi caching yang digunakan adalah:

Memcached: Menyimpan data yang sering diakses dalam memori untuk mempercepat pemrosesan permintaan.

Redis: Alternatif caching yang digunakan untuk meningkatkan efisiensi dalam pengelolaan sesi pengguna dan query basis data.

Squid/Varnish: Digunakan sebagai reverse proxy caching untuk menyimpan versi halaman yang sering diakses agar tidak perlu dibuat ulang setiap kali ada permintaan.

4. Pengolahan Teks dan Rendering Halaman
MediaWiki menggunakan mesin parser berbasis PHP untuk mengubah sintaks wiki menjadi HTML yang dapat ditampilkan di peramban. Selain itu, dengan diperkenalkannya Parsoid, MediaWiki kini mendukung VisualEditor, editor berbasis WYSIWYG yang memungkinkan pengguna mengedit halaman tanpa perlu memahami sintaks kode wiki.

5. API dan Ekstensi untuk Fungsionalitas Tambahan
MediaWiki memiliki API yang kuat, memungkinkan integrasi dengan layanan lain dan pengembangan bot otomatis untuk mengelola konten. Beberapa fitur utama API MediaWiki meliputi:

REST API: Untuk komunikasi yang lebih efisien dengan aplikasi pihak ketiga.

Action API: Digunakan untuk mendapatkan data dari MediaWiki dan melakukan perubahan seperti mengedit atau mengunggah file.

Selain itu, MediaWiki memiliki sistem ekstensi yang luas, seperti Semantic MediaWiki untuk pengelolaan data terstruktur, CheckUser untuk keamanan, dan Cite untuk sistem referensi yang lebih baik.

6. Keamanan dan Manajemen Pengguna
MediaWiki memiliki sistem manajemen pengguna yang fleksibel dengan berbagai tingkat akses, mulai dari pengguna anonim hingga administrator. Fitur keamanan seperti autentikasi dua faktor (2FA) dan proteksi halaman memungkinkan perlindungan terhadap vandalisme dan akses yang tidak sah.

7. Interoperabilitas dan Skalabilitas
MediaWiki dapat diintegrasikan dengan berbagai sistem lain menggunakan protokol standar seperti OAuth, LDAP, dan OpenID untuk autentikasi pengguna. Dalam skala besar seperti Wikipedia, MediaWiki berjalan dalam arsitektur terdistribusi menggunakan Kubernetes dan Docker untuk manajemen container serta Hadoop untuk analisis data dalam skala besar.
---

## **5. Fitur MediaWiki**
1. Pengeditan Berbasis Wiki
MediaWiki memungkinkan pengguna untuk menyunting halaman dengan menggunakan sintaks wiki yang sederhana. Sintaks ini memungkinkan pembuatan tautan internal, format teks, daftar, tabel, dan berbagai elemen lainnya tanpa perlu memahami kode HTML. Selain itu, fitur preview memungkinkan pengguna melihat hasil suntingan sebelum menyimpannya.

2. VisualEditor: Pengeditan WYSIWYG
Untuk memudahkan pengguna yang tidak terbiasa dengan sintaks wiki, MediaWiki memiliki VisualEditor, editor berbasis WYSIWYG (What You See Is What You Get). Dengan VisualEditor, pengguna dapat menyunting halaman secara langsung seperti menggunakan pengolah kata, tanpa perlu mengetikkan kode markup.

3. Sistem Revisi dan Riwayat Suntingan
Setiap perubahan yang dilakukan di MediaWiki disimpan dalam riwayat revisi, memungkinkan pengguna melihat siapa yang melakukan suntingan dan apa yang diubah. Jika terjadi kesalahan atau vandalisme, halaman dapat dikembalikan ke versi sebelumnya dengan mudah.

4. Manajemen Pengguna dan Hak Akses
MediaWiki memiliki sistem perizinan yang fleksibel, memungkinkan pengaturan tingkat akses pengguna. Beberapa peran dalam MediaWiki meliputi:

Pengguna anonim: Dapat membaca dan mengedit halaman tergantung pada pengaturan wiki.

Pengguna terdaftar: Dapat mengedit, membuat halaman baru, dan menggunakan fitur lanjutan.

Administrator: Memiliki hak untuk menghapus halaman, memblokir pengguna, dan melakukan perlindungan halaman.

Birokrat: Dapat memberikan hak administrator kepada pengguna lain.

5. Sistem Caching dan Kinerja Optimal
Untuk memastikan performa yang cepat, MediaWiki menggunakan berbagai sistem caching seperti Memcached, Redis, dan Varnish untuk menyimpan halaman yang sering diakses. Hal ini memungkinkan MediaWiki menangani lalu lintas yang tinggi tanpa membebani server secara berlebihan.

6. Dukungan Multibahasa
MediaWiki memiliki fitur terjemahan otomatis dan dukungan multibahasa, memungkinkan pengguna dari berbagai negara untuk mengakses konten dalam bahasa mereka sendiri. Fitur Content Translation membantu penerjemah dalam membuat versi artikel dalam berbagai bahasa dengan lebih cepat dan efisien.

7. Pengelolaan Berkas Multimedia
MediaWiki memungkinkan pengguna untuk mengunggah gambar, video, dan file lainnya menggunakan ekstensi File Upload. Selain itu, proyek Wikimedia Commons menyediakan repositori media yang dapat digunakan di berbagai proyek Wikimedia.

8. Ekstensi dan Kustomisasi
Salah satu kekuatan utama MediaWiki adalah sistem ekstensinya. Ada ratusan ekstensi yang dapat digunakan untuk menambahkan fitur baru, seperti:
Semantic MediaWiki: Untuk mengelola data secara terstruktur.
Cite: Untuk menambahkan sistem referensi otomatis.
CheckUser: Untuk mengawasi aktivitas pengguna yang mencurigakan.

9. API untuk Integrasi dengan Aplikasi Lain
MediaWiki menyediakan REST API dan Action API, yang memungkinkan pengembang mengakses dan memodifikasi konten wiki secara otomatis. API ini digunakan oleh bot, aplikasi pihak ketiga, dan alat analitik untuk berbagai keperluan.

10. Mode Gelap dan Tampilan Responsif
Seiring dengan perkembangan teknologi, MediaWiki kini mendukung mode gelap dan tampilan yang lebih responsif melalui tema Vector 2022. Ini memberikan pengalaman pengguna yang lebih baik, terutama bagi mereka yang mengakses melalui perangkat seluler.

---

## **6. Implementasi MediaWiki**
1. Persiapan Implementasi MediaWiki
Sebelum menginstal MediaWiki, beberapa hal perlu dipersiapkan:

Server dan Infrastruktur: MediaWiki dapat diinstal di server lokal atau menggunakan layanan cloud seperti AWS, DigitalOcean, atau Linode.

Perangkat Lunak Pendukung: MediaWiki memerlukan PHP, MySQL/MariaDB, serta web server seperti Apache atau Nginx.

Kebutuhan Pengguna: Menentukan apakah MediaWiki akan digunakan untuk dokumentasi internal, komunitas daring, atau sebagai basis data publik.

2. Instalasi dan Konfigurasi
Setelah persiapan selesai, proses instalasi dilakukan dengan langkah-langkah berikut:

Mengunduh MediaWiki dari situs resmi mediawiki.org.

Mengonfigurasi basis data menggunakan MySQL atau MariaDB.

Menyesuaikan file konfigurasi seperti LocalSettings.php untuk menentukan opsi dasar seperti bahasa, nama situs, dan hak akses pengguna.

Menginstal ekstensi untuk menambah fitur tambahan seperti VisualEditor atau Semantic MediaWiki.

3. Manajemen Pengguna dan Hak Akses
MediaWiki memungkinkan pengaturan izin akses pengguna berdasarkan peran mereka:

Administrator: Dapat mengelola sistem, menghapus halaman, dan mengatur pengguna.

Pengguna Terdaftar: Dapat membuat dan menyunting halaman.

Pengguna Anonim: Bergantung pada kebijakan, mereka dapat membaca atau bahkan menyunting halaman tertentu.

Hak akses dapat dikonfigurasi melalui file LocalSettings.php atau dengan ekstensi seperti Extension:Lockdown untuk kontrol lebih lanjut.

4. Personalisasi dan Kustomisasi
MediaWiki dapat dikustomisasi untuk memenuhi kebutuhan organisasi tertentu:

Tema dan Antarmuka: Menggunakan skin seperti Vector atau Timeless untuk tampilan yang lebih modern.

Ekstensi Tambahan: Menambahkan ekstensi seperti ParserFunctions, Cite, dan CheckUser untuk meningkatkan fungsionalitas.

Pengaturan Logo dan Branding: Mengubah logo situs dengan mengganti file dalam direktori resources/assets/.

5. Penggunaan MediaWiki dalam Berbagai Skenario
a. Dokumentasi Perusahaan
Banyak perusahaan menggunakan MediaWiki sebagai basis pengetahuan internal. Hal ini membantu dalam pengelolaan dokumen teknis, kebijakan, dan prosedur kerja. Contoh implementasi yang populer adalah penggunaan MediaWiki dalam dokumentasi perangkat lunak dan teknologi di berbagai perusahaan teknologi besar.

b. Proyek Komunitas dan Open Source
Komunitas open source seperti Ubuntu dan Arch Linux menggunakan MediaWiki untuk mendokumentasikan perangkat lunak mereka. Ini memungkinkan pengembang dan pengguna berkontribusi pada dokumentasi secara kolaboratif.

c. Institusi Pendidikan
Beberapa universitas dan sekolah menggunakan MediaWiki sebagai platform pembelajaran berbasis wiki, di mana siswa dan pengajar dapat berbagi materi, tugas, dan sumber daya akademik.

6. Pemeliharaan dan Keamanan
MediaWiki memerlukan pemeliharaan rutin untuk memastikan kinerjanya tetap optimal:

Pembaruan Perangkat Lunak: Memastikan MediaWiki dan ekstensi selalu diperbarui untuk memperbaiki bug dan celah keamanan.

Pencadangan Data: Secara berkala mencadangkan basis data dan file konfigurasi untuk menghindari kehilangan informasi.

Keamanan Pengguna: Menerapkan autentikasi dua faktor (2FA) dan mengelola hak akses dengan bijak untuk mencegah penyalahgunaan sistem.

---

## **7. Penutup**
**Durasi: 3 menit**  
Demikian pembahasan kita mengenai MediaWiki, mulai dari sejarah, fitur, teknologi, hingga penerapannya.  

Semoga informasi ini bermanfaat dan memberikan wawasan baru tentang bagaimana MediaWiki dapat digunakan dalam berbagai konteks.  

Terima kasih atas perhatian Bapak/Ibu dan teman-teman sekalian.  
Jika ada pertanyaan, silakan disampaikan.  

Wassalamu’alaikum warahmatullahi wabarakatuh.
