# RINGKASAN
Pengenalan dan Persiapan Awal. Pada awalnya, eksperimen dilakukan dengan memilih media penyimpanan eksternal berupa flash disk sebagai sumber data yang akan diselidiki. Langkah pertama adalah menciptakan struktur folder yang terorganisir dengan baik untuk menyimpan semua hasil investigasi. Dalam hal ini, saya memulainya dengan membuat folder "CASES" sebagai induk di mana semua kasus akan disimpan. Kemudian, saya membuat sub-folder dengan nomor kasus 001 di dalamnya. Untuk memudahkan pengelolaan kasus, saya juga menambahkan indikator jenis investigasi dengan memberi tag tambahan. Tag tersebut terdiri dari kode "H" untuk jenis investigasi tertentu, diikuti dengan tag penyelidik "Dharma", dan inisial anggota tim penyelidik "D".

Struktur Folder Kasus. Setelah struktur folder induk dan sub-folder kasus dibuat, langkah selanjutnya adalah menetapkan sub-folder di bawah folder kasus 001. Ini termasuk folder "Docs" untuk dokumen, "Image" untuk gambar, "temp" untuk sementara, "Autopsy" untuk data dan hasil analisis Autopsy, dan "Reports" untuk laporan-laporan yang dihasilkan.

Pembuatan Dokumen dan Pencatatan. Dalam setiap langkah proses forensik digital, pencatatan yang akurat sangat penting. Oleh karena itu, saya membuat dokumen teks baru dengan nama 001-H-Dharma-D-doc.txt di dalam folder dokumen. Dokumen ini berfungsi sebagai catatan log yang mencatat setiap aktivitas yang dilakukan, termasuk waktu pembuatan folder dan langkah-langkah lainnya. Pencatatan dilakukan dengan hati-hati menggunakan notepad, dan saya selalu memastikan untuk menyimpan perubahan sebelum keluar dari aplikasi.

Proses Analisis Forensik Digital. Langkah selanjutnya dalam eksperimen ini adalah melakukan analisis forensik digital menggunakan aplikasi Autopsy. Proses dimulai dengan menyalin data yang dicurigai, seperti Exhibit001, ke dalam folder yang sesuai di dalam struktur folder kasus. Selanjutnya, Autopsy 4.21.0 dijalankan untuk memproses data kasus 001-H-Dharma-D.

Pengaturan Kasus dalam Autopsy. Untuk memulai analisis dalam Autopsy, saya membuka aplikasi dan memilih opsi "New Case". Saya mengisi informasi tentang nama kasus, direktori dasar, dan mode pengguna. Informasi kontak yang relevan juga ditambahkan untuk keperluan manajemen kasus yang lebih baik.

Analisis Data dan Pencarian Hash. Setelah pengaturan kasus selesai, langkah selanjutnya adalah mengatur detail host dan memilih file image yang akan dianalisis. Autopsy memungkinkan pengguna untuk mengatur zona waktu dan mengisi nilai hash untuk memfasilitasi pencarian yang efektif. Proses pencarian hash berguna untuk mengatur database hash, memfilter file yang dikenal baik atau buruk, dan memudahkan proses analisis.

Pencarian dan Tandai Data Relevan. Dalam tahap analisis, saya menggunakan fitur pencarian Autopsy untuk mencari kata kunci atau pola dalam data yang dicurigai. Setelah menemukan data yang relevan, saya menandainya dengan tag file untuk referensi selanjutnya. Ini membantu dalam mengorganisir dan memprioritaskan data yang penting dalam proses penyelidikan.

Pembuatan Laporan dan Kesimpulan. Setelah semua proses analisis selesai, saya membuat laporan yang mencakup hasil analisis dan aktivitas yang dilakukan dalam Autopsy. Laporan tersebut mencakup detail tentang semua tindakan yang dilakukan dalam pemeriksaan forensik, termasuk hasil pencarian, tag file, dan temuan penting lainnya. Kesimpulan dari eksperimen ini adalah bahwa Autopsy menyediakan alat yang efektif dan komprehensif untuk melakukan analisis forensik digital dengan cara yang terstruktur dan terdokumentasi dengan baik.


# STEP BY STEP
## PART 1
1. Buka Autopsy, pilih New Case
   ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/8dadb081-11a2-4993-9b0e-7d506efd0626)
2. Isi Case Information
   ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/08a370a6-ff60-4be9-bfef-f530f7cbacbf)
3. Tambahkan Optional Information, kemudian tekan Finish
   ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/b828b16d-63e0-409b-aa94-5aea6d37fad9)
4. Kemudian Select Host Name
   ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/f4892686-de8c-4f67-9149-da09fca669d9)
5. Kemudian pilih Data Source Type, disini saya menggunakan Disk Image or VM File
   ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/4179c511-4772-4c8c-b61a-f5fd2e80dced)
6. Kemudian Select Data Source
   ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/730fad87-b9fa-42ed-b302-7f3c8ecef79b)
7. Set Module sesuai dengan kebutuhan, kemudian Next dan Finish
   ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/5755c9e2-2ef5-4a09-80fc-a382b1c0022e)
8. Autopsi file-file yang berada dalam Path di gambar, untuk detail file bisa di scroll kesamping dan di klik
   ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/0b528f6e-7e36-4022-ab68-58923075508a)
   ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/54a99e89-0c86-444c-84a2-b6b8db804f0b)
9. Kalian bisa explore ke Menu lainnya seperti File Views
10. Yang terakhir adalah Laporan (Report), tekan Generate Report kemudian tentukan format Report, kemudian tentukan apa yang ingin dijadikan Report, bisa semua hasil atau yang spesifik
    ![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/04f04da2-33cc-426f-a955-4ddd7a8ea30a)

## PART 2
Untuk part 2 tidak bisa saya lakukan karena mungkin spek laptop terlalu rendah dan file terlalu besar, yang jadinya hanya melakukan loading di analisa file dan tidak dapat menampilkan Data Artifact dan Analyst Result.
![image](https://github.com/marieroseoo/Autopsy-Exercise---1203210117/assets/150213177/25a7718c-a5da-4bae-9670-d035d616540f)

## Reference
Part 1 https://www.youtube.com/watch?v=fEqx0MeCCHg
Part 2 https://www.youtube.com/watch?v=5SHB4HwkX28
