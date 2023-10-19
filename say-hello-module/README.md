## Say Hello Module

Ini adalah contoh module yang akan kita consume dari aplikasi Go. Module ini hanya mengembalikan string `"Hello"` dengan cara memanggil function `SayHello()`. Penamaan function `SayHello()` diawali dengan huruf kapital supaya bisa diexport secara publik. Dalam contoh ini, aplikasi Go yang akan consume module ini ada didalam module `say-hello-consumer` dengan nama file `app.go`