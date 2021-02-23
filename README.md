# project2-Mobile1
LAYOUT ANDROID menggunkan aplikasi ECLIPSE


MODUL 2 LAYOUT ANDROID

Tujuan:
Setelah mempelajari materi ini diharapkan mahasiswa memiliki kemampuan untuk:
1)	Memahami XML
2)	Memahami Desain Layout Android (Linear Layout, Relative Layout, Table Layout, Frame Layout, dan Scroll View)

1.	XML (EXTENSIBLE MARKUP LANGUAGE)

Sebuah aplikasi android dibuat dari kombinasi XML dan JAVA. Biasanya, XML digunakan untuk mengatur layout aplikasi sedangkan JAVA berperan sebagai pusat pengendalinya. Apapun platformnya konsep dasar dalam mengembangkan aplikasi adalah bagaimana menampilkan informasi di layar, melakukan proses yang dibutuhkan dan berpindah dari satu halaman ke halaman lain dengan atau tanpa data.
Dalam pemrograman Android menggunakan Eclipse, untuk mendesain tampilan antarmuka digunakan XML. Dalam membuat sebuah halaman dengan eclipse, otomatis akan terbentuk dua buah file, file pertama adalah activity, berguna untuk menampung kode java atau logika dari program (ber-ekstensi .java), file kedua adalah layout, berguna untuk menampung kode xml sebagai desain dari halaman yang akan dibuat (ber-ekstensi .xml).

XML adalah bahasa markup untuk keperluan umum yang disarankan oleh W3C dalam hal membuat dokumen markup untuk keperluan pertukaran data antar sistem yang beraneka ragam. XML merupakan kelanjutan dari HTML (HyperText Markup Language).
Contoh perintah XML :
 
2.	DESAIN LAYOUT ANDROID

Tata letak tampilan dibagi menjadi beberapa macam. Diantaranya yang sering digunakan yaitu Linear Layout, Relative Layout, Table Layout, Frame Layout,  dan Scroll View.

A.	Liner Layout

Linear Layout akan menampilkan elemen-elemen View secara garis lurus, baik vertical ataupun horizontal.
1)	Buat project baru (File  New  Android Project).
2)	Isikan pada kotak dialog project sebagai berikut:


Project Name:	LinearLayout
Build Target:	Android 2.2
Application Name:	LinearLayout
Package Name:	com.linear
Create Activity:	LinearLayoutActivity
Min SDK Version	8
3)	Buka file main.xml yang ada pada project (LinearLayout  res  layout 
main.xml).
4)	Pada contoh pertama ini kita akan membuat Linear Layout secara horizontal. Ketikan kode berikut pada file main.xml (Gambar 2.3).
5)	Jalankan project (Klik kanan Project “LinearLayout”  Run As  Android Application) dan lihat hasilnya seperti (Gambar 2.4) berikut.
6)	Selanjutnya kita akan membuat Linear Layout secara vertical. Tambahkan kode berikut pada kode main.xml sebelumnya.
7)	Jalankan kembali project (Klik kanan Project “LinearLayout”  Run As  Android Application) dan lihat hasilnya seperti (Gambar 2.6) berikut.

 
B.	Relative Layout

Relative Layout memungkinkan pengguna menyusun tata letak secara lebih leluasa. Posisi setiap widget bisa diatur relatif pada widget yang lainnya (dibawah, atau disamping widget sebelumnya). Relative Layout adalah cara terbaik untuk mendesain suatu interface.
1)	Buat project baru (File  New  Android Project).
2)	Isikan pada kotak dialog project sebagai berikut:


Project Name:	RelativeLayout
Build Target:	Android 2.2
Application Name:	RelativeLayout
Package Name:	com.relative
Create Activity:	RelativeLayoutActivity
Min SDK Version	8

3)	Ketikan kode berikut pada file main.xml yang ada pada project (RelativeLayout  res
 layout  main.xml).
4)	Jalankan project (Klik kanan Project “RelativeLayout”  Run As  Android Application) dan lihat hasilnya seperti (Gambar 2.8) berikut.

C.	Table Layout

Table Layout adalah tampilan yang disusun berdasarkan baris dan kolom. Biasanya, Table Layout terdiri dari beberapa TableRow. Didalam TableRow inilah terdapat field-field yang nantinya terlihat sebagai kolom.
1)	Buat project baru (File  New  Android Project).
2)	Isikan pada kotak dialog project sebagai berikut:


Project Name:	TableLayout
Build Target:	Android 2.2
Application Name:	Tampilan Table Layout
Package Name:	com.tablelayout
Create Activity:	TableLayoutActivity
Min SDK Version	8

3)	Ketikan kode berikut pada file main.xml yang ada pada project (TableLayout  res 
layout  main.xml).
4)	Jalankan project (Klik kanan Project “TableLayout”  Run As  Android Application) dan lihat hasilnya seperti (Gambar 2.10) berikut.

 
D.	Frame Layout

FrameLayout adalah jenis layout yang dibuat atau di rancang untuk menyisipkan widget ke dalam widget lainya. Contoh widget TextView (Contoh Text Satu) ada di dalam widget TextView yang kedua (Contoh Text Dua). Widget yang diletakan di akhir akan berada di posisi widget sebelumnya.
1)	Buat project baru (File  New  Android Project).
2)	Isikan pada kotak dialog project sebagai berikut:


Project Name:	FrameLayout
Build Target:	Android 2.2
Application Name:	Tampilan Frame Layout
Package Name:	com.framelayout
Create Activity:	FrameLayoutActivity
Min SDK Version	8

3)	Ketikan kode berikut pada file main.xml yang ada pada project (FrameLayout  res 
layout  main.xml).
 4)	Jalankan project (Klik kanan Project “FrameLayout”  Run As  Android Application) dan lihat hasilnya seperti (Gambar 2.12) berikut.


E.	Scroll View

ScrollView adalah salah satu jenis komponen yang digunakan pada user interface di layout.xml. ScrollView berbeda dengan LinearLayout dan RelativeLayout, ScrollView berfungsi untuk memuat suatu layar agar dapat ditampilkan secara penuh, serta akan menambahkan scrollbar di pojok kanan layar.
1)	Buat project baru (File  New  Android Project).
2)	Isikan pada kotak dialog project sebagai berikut:


Project Name:	ScrollView
Build Target:	Android 2.2
Application Name:	Tampilan Scroll View
Package Name:	com.scrollview
Create Activity:	ScrollViewActivity
Min SDK Version	8

3)	Ketikan kode berikut pada file main.xml yang ada pada project (ScrollView  res 
layout  main.xml).
4)	Jalankan project (Klik kanan Project “ScrollView”  Run As  Android Application) dan lihat hasilnya seperti (Gambar 2.14) berikut.

