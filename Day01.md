# Rangkuman hari Pertama

### Pengenalan
Pengenalan mentor, tool dan environment yang akan digunakan

* Bahasa pemrograman yang akan digunakan adalah Javascript.
* IDE yang dipakai adalah Visual Studio Code.
* Situs untuk melatih kecepatan mengetik : [10fastfingers](https://10fastfingers.com/advanced-typing-test/english)
* Situs untuk mengasah kemampuan Programming : [HackerRank](https://www.hackerrank.com/home?utm_expid=.2u09ecQTSny1HV02SEVoCg.1&utm_referrer=)
* Berkontribusi pada Open Source di : [StackOverflow](https://stackoverflow.com/) & [OpenSourceFriday](https://opensourcefriday.com/)
* [Github](https://github.com/)

### Javascript
Java script pertama lahir  pada tahun 1995 untuk browser NETscape kemudian berjalan di IE 5,
pada saat itu Javascript hanya dapat dipakai untuk browser dan tidak 
terkoneksi satu dengan yang lainnya hingga pada 2009 node js lahir yang membuat Javascript
bisa dijalankan di semua platform.

Di hari pertama yang dibahas adalah beberapa tools untuk mempermudah efisiensi coding
* **Snippet** :  source code yang dapat dipakai berulang kali untuk menghindari pengetikan yang berulang ulang.
* **Copy Line up & down**   : menyalin semua yang ada dibaris ke baris dibawahnya atau diatasnya
* **Move Line up & down**   : memindahkan semua yang ada di baris ke baris dibawahnya atau diatasnya
* **Add cursor up & down**  : menambahkan kursor ke atas atau bawah, biasanya digunakan untuk mengetik tulisan
                              dalam jumlah banyak disaat bersamaan.
* **Add next occurence**    : menyeleksi code yang memiliki pola sama.

### Git & Github
GitHub adalah layanan hosting repository dari git yang berfungsi untuk mengontrol
project dan memiliki banyak fitur. Git adalah _command line_, sedangkan Github 
mempunyai tampilan antarmuka pengguna. Github juga memberikan akses kontrol dan 
fitur-fitur untuk digunakan dalam kerja tim atau project.

Di dalam github terdapat fitur **_Branch_** dimana jika kita mengerjakan atau mengembangkan
sesuatu di dalam _branch_ tersebut, maka tidak berdampak terhadap _branch_ yang lain. dan 
ada _branch_ yang bernama master branch, adalah branch yang berisi file yang terakhir dicommit
di dalam branch.

Beberapa fitur penting dari git adalah :

* **add**    Menambahkan file ke index
* **init**   Membuat repository kosong atau menimpa yang sudah ada
* **status** Menampilkan status _working tree_
* **commit**  Merekam perubahan pada repository
* **push**   Memperbarui referensi dan yang berkaitan dengan objectnya

Untuk lebih lanjut dapat anda temukan pada command **$ git help** ,dan 
berikut adalah langkah membuat Repository Git dari terminal :

1. git init 
2. git add README.md
3. git commit -m "first commit"
4. git remote add origin git@github.com:corrupteddevkit/IshtearNodeJS.git
5. git push -u origin master
