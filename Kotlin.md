## Kotlin

##### Pengenalan Bahasa Pemrograman

Bahasa pemrograman atau bahasa komputer adalah  instruksi standar untuk memerintah komputer (mesin). Seperti halnya manusia untuk memerintah atau berbicara dengan manusia butuh bahasa. seperti yang kita tahu bahasa manusia banyak. Bahasa pemrograman juga begitu banyak seperti Kotlin, Java, Python, PHP, Ruby, Golang, C dan masih banyak lagi.

Untuk membuat aplikasi Android bisa menggunakan dua bahasa pemrograman yaitu Java atau Kotlin. Kali ini kita menggunakan bahasa Kotlin. Cukup satu bahasa kuasai sampai jadi master.

Kita bisa belajar menjalankan program bahasa kotlin di https://kotlinlang.org/

![Screen Shot 2019-09-01 at 10.18.48](/Users/sulistiyanto/Documents/TeoriKotlin/Screen Shot 2019-09-01 at 10.18.48.png)

Silahkan buka alamat  https://kotlinlang.org/

Yuk kita bahas satu persatu kode program diatas.

**package hello** disini adalah alamat file kita simpan. Kalau kita buat aplikasi android akan otomatis dibuatkan package-nya.

**fun main()** adalah fungsi utama untuk menjalankan perintah bahasa kotlin. **fun** ini wajib ditulis ketika kita membuat sebuah fungsi. **main()** ini adalah nama fungsinya yang wajib ada kurung buka tutup.

**Jangan lupa setiap kita menulisan code harus didalam tanda kurung kurawal { }**, kecuali pembuatan variabel bisa di luar atau dalam kurung kurawal.

Apakah kita bisa membuat fungsi sendiri? BISA. kita coba menambahkan fungsi buatan kita.

```kotlin
fun jalan() {
  println("Jalan-jalan")
}
```

bagaimana menampilkan tulisan Jalan-jalan? tinggal panggil saja fungsi jalan() di dalam main(). Hasil penambahan kode dan memanggil fungsi jalan.

```kotlin
package hello

fun main() {
  jalan()
  println("Hello World")
}

fun jalan() {
  println("Jalan-jalan")
}
```

##### Variabel dan Tipe Data

Variabel adalah tempat untuk menyimpan **data** atau sebuah nilai. Variabel di kotlin ada dua cara penulisan yaitu diawali **var** atau **val**. Syarat pembuatan variabel yang baik adalah

- Diawali huruf kecil dan menggunakan kata yang mudah dipahami.
- Tidak boleh ada spasi. Kalau ada dua atau lebih kata bagaimana? Penulisan kata kedua diawali huruf besar. contoh **birthDate**
- Biasakan menggunakan bahasa inggris. Apa tidak bisa bahasa indonesia? Bisa. namun penggunaan bahasa inggris lebih baik untuk kerja tim dikemudian hari dengan orang dalam maupun luar negeri agar kompak.

Contoh :

```kotlin
var name = "Tiyan"
var age = "20"
var birthDate = "17 Mei 1990"
```

penamaan variabel :

var **nama_variabel** = **nilai**

atau

```kotlin
val name = "Tiyan"
val age = "20"
```

Terus perbedaannya apa **var** dan **val**? **var** nilainya bisa diganti kalau **val** nilainya tidak bisa diganti. 

Praktek

```kotlin
var name = "Tiyan"
fun main() {
    println("Nama saya $name")
}
```

Untuk menampilkan nilai variabel kita kasih tanda '**$**' di depan nama variabel, seperti contoh diatas.

Tugas sekarang tampilkan kalimat 

**Nama saya ... berumur ... dan tinggal di kota ...** 

 Isi titik tersebut dengan memanggil nama variabel.

Tipe Data adalah kelompok **data** berdasarkan jenis-jenis tertentu

```kotlin
var name: String = "Tiyan"
var age: Int = 30
var weight: Double = 70.7
```

Sebenarnya ada bebrapa tipe data namun kali ini kita bahas 3 tipe data yang sering digunakan yaitu :

String = ini untuk jenis data bertipe kalimat atau kata dengan di tandai petik dua diatas ""

Int = ini untuk jenis data bertipe bilangan bulat. contoh mulai angka 0 .. dst

Double = ini untuk jenis data bertipe bilangan pecahan, contoh 1.1, 2.9 