## Menambah dependency module

Seringkali module Go yang kita buat itu menerapkan fitur yang sebenarnya sudah diimplementasikan di module lain. Sehingga, kita bisa membuat module kita menjadi dependen terhadap module lain tersebut. Module lain tersebut bisa disebut sebagai dependency module kita.

Dalam contoh ini, kita akan menjadikan module `github.com/malvinval/gosayhello` ([https://github.com/malvinval/gosayhello](https://github.com/malvinval/gosayhello)) sebagai dependency dari aplikasi Go kita. Consumer dari module tersebut adalah `say-hello-consumer` ([https://github.com/malvinval/learn-go-modules/tree/master/say-hello-consumer](https://github.com/malvinval/learn-go-modules/tree/master/say-hello-consumer)).

## Jalankan command

Dalam module `say-hello-consumer`, silahkan jalankan command:

1. `go get github.com/malvinval/gosayhello`
2. `go mod tidy`

## Directory **`go/pkg/mod`**

Setelah kita jalanin command `go get github.com/malvinval/gosayhello`, maka module tersebut akan masuk ke dalam directory `/home/username/go/pkg/mod/github.com/malvinval` di komputer lokal kita. Kesimpulannya adalah, directory `go/pkg/mod` digunakan untuk menyimpan seluruh mmodule yang dibutuhkan oleh project Go kita.