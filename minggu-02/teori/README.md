# Tutorial - bab 4
Pengendali Aliran Program

Untuk macam – macam  dari pengendali perulangan ini, mengkin akan memiliki 
perbedaan di setiap bahasa pemrograman. Hal ini berkaitan langsung dengan 
aturan dari bahasa pemrograman itu sendiri. Aturan – aturan tersebut biasa disebut syntak. 
Jadi karena setiap bahasa pemrograman berbeda, maka saya akan memilih bahasa pemrograman 
python untuk dijadikan sebagai contoh.  Nah pada python, pengendali perulangan ini terdapat 3 macam. 
3 macam tersebut adalah :
1.Break statement.
2.Pass statement.
3.Continue statement.

Penggunaan else dengan perulangan.
Nah seperti yang sudah saya katakan diatas, jumlah dan macam – macam dari pengendali perulangan 
ini mungkin akan memiliki perbedaan pada setiap bahasa pemrograman

Break statement.
Nah statement yang satu ini biasa digunakan untuk menghentikan sebuah perulangan. 
Jadi kita bisa menggunakannya untuk menghentikan sebuah perulangan ketika ada kondisi di mana kita ingin menghentikannya.

for i in range (20) : //ini digunakan untuk membuat membuat perulangan yang dilakukan sebanyak 20 kali.
    if i == 10 : //nah ini digunakan untuk mengecek apakah nilai i = 10 atau tidak.
        print("angka sudah melebihi nilai 9") //nah ini untuk mencetak peringatan. Yaitu “angka sudah melebihi nilai 9”
        break //nah ini digunakan untuk menghentikan perurulangan.
    print(i) //untuk mencetak setiap perubahan nilai i.
	
Continue statement.
Nah yang satu ini digunakan untuk mengulang perulangan.. maksudnya, program yang berada di bawah statement tidak akan di eksekusi. 
Atau bisa kita katakan untuk men lewati perintah yang ada di bawahnya. 

for i in range (10) : //ini merupakan sebuah perulangan yang akan berulang selama 10 kali.
    if i == 5 : //code yang ini digunakan untuk menyeleksi nilai i apakah bernilai 5 atau tidak. 
	Jika benar, maka program yang berada dibawahnya akan dijalankan. Tepatnya yang menjorok kedalam.
        print("angka 5 tidak tidak di print karena ada statement continue") //digunakan untuk mencetak kata – kata yang berada di dalam kurung.
        Continue //nah code yang ini digunakan untuk melanjutkan sebuah perulangan. Dan pada kondisi ini saya kan melakukan mengaktifkan statment ini saat i bernilai 5.
    print(i) //code ini digunakan untuk menampilkan setiap perubahan yang terjadi pada nilai i.
	
Statement pass.
Sebenarnya statement ini tidak memiliki fungsi yang sangat penting. Dan bahkan sangat jarang digunakan oleh programer. 
Jadi pass ini sebenarnya hanya mengisi kekosongan saja. Agar program tidak eror nantinya.

Penggunaan else pada perulangan.
Nah yang terakhir adalah penggunaan else dalam sebuah perulangan. Nah penggunaan else dalam sebuah perulangan, 
akan bekerja jika kondisi statement di dalam sebuah perulangan akan bernilai fales.

a = 1 //pendeklarasian variabel a dengan nilai 0
while a == 0 : //perulangan yang menanyakan apakah nilai a itu 0 ? jika iya maka akan mencetak “perulangan”. 
Namun jika nilai a bukan 0, maka akan dilanjutkan ke ‘else’
    print(“perulangan”) //digunakan menampilka “perulangan”
else : //statement yang akan otomatis aktif dan mengerjakan program yang menjadi bagian darinya apabila perulangan tidak dijalankan. 
Atau kondisi pada perulangan sudah tidak memenuhi lagi.
    print(“else”) //digunakan untuk menampilkan teks “else”.