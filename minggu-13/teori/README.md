# Pandas

Pandas merupakan toolkit yang powerfull sebagai alat analisis data dan struktur untuk bahasa pemrograman Python. Dengan menggunakan pandas kita dapat mengolah data dengan mudah, salah satu fiturnya adalah Dataframe. Dengan adanya fitur dataframe kita dapat membaca sebuah file dan menjadikannya tabble, kita juga dapat mengolah suatu data dengan menggunakan operasi seperti join, distinct, group by, agregasi, dan teknik lainnya yang terdapat pada SQL.

Banyak format file yang dapat dibaca menggunakan Pandas, seperti file .txt, .csv, .tsv dan lainnya. Agar lebih jelas mari kita mencobanya secara langsung. (Catatan: Pada artikel ini saya menggunakan python versi 3.6, jika teman-teman menggunakan versi 2.7 mungkin akan sedikit berbeda)

Menginstall Pandas
Untuk dapat menginstall pandas, kita bisa menjalankan perintah berikut :

pip install pandas
Atau jika teman-teman menggunakan library Anaconda, kita bisa menginstallnya dengan perintah beriktu :

conda install pandas
Mencoba Series
Series merupakan sebuah array satu dimensi yang memiliki label dan digunakan untuk menyimpan beragam tipe data seperti integer, string, float, bahkan objek, dan lain sebagainya. Label pada series disebut dengan index. Bagaimana cara membuat series ? Perintah dasar untuk membuat sebuah Series dengan pandas adalah

pandas.Series( data, index, dtype, copy)

pandas menyediakan beragam fungsi operasi untuk mengolah data. Contoh jika kita menggunakan series kita bisa mencari nilai max, min, dan mean secara langsung, bahkan kita juga bisa melakukan operasi perpangkatan pada nilai Series secara langsung. 