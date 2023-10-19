## Say Hello Consumer

Module ini kita jadikan sebagai contoh module Go yang dependen terhadap module `github.com/malvinval/gosayhello` ([https://github.com/malvinval/gosayhello](https://github.com/malvinval/gosayhello)). Dalam module ini, kita bisa jalankan command `go get github.com/malvinval/gosayhello`, lalu jalankan command `go mod tidy`.

## Spesifikasi module dependency

- Nama module: `github.com/malvinval/gosayhello`
- Repo module: [https://github.com/malvinval/gosayhello](https://github.com/malvinval/gosayhello)
- Nama package: `sayhello`
- Callable function: `SayHello()`

## Directory **`go/pkg/mod`**

Setelah kita jalanin command `go get github.com/malvinval/gosayhello`, maka module tersebut akan masuk ke dalam directory `/home/username/go/pkg/mod/github.com/malvinval` di komputer lokal kita. Kesimpulannya adalah, directory `go/pkg/mod` digunakan untuk menyimpan seluruh mmodule yang dibutuhkan oleh project Go kita.