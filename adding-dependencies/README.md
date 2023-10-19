## Menambah dependency module

Seringkali module Go yang kita buat itu menerapkan fitur yang sebenarnya sudah diimplementasikan di module lain. Sehingga, kita bisa membuat module kita menjadi dependen terhadap module lain tersebut. Module lain tersebut bisa disebut sebagai dependency module kita. Cara untuk menambahkan dependency module kita adalah dengan menjalankan command `go get nama_module`.

Dalam contoh ini, kita akan menjadikan module `say-hello-module` sebagai dependency dari aplikasi Go kita yakni `say-hello-consumer`.