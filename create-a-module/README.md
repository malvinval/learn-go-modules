## Cara membuat module

Untuk inisialisasi project atau module Go, langsung aja bikin sebuah directory, masuk ke directory tersebut, lalu jalanin command `go mod init <nama_module>`. Biasanya nama module itu sama dengan nama directory project, tapi ya terserah si kalo mau pake nama lain.

Perlu diingat bahwa project Go di repository ini ga perlu ditempatin di path `$GOPATH/src`. Dimana aja bebas, **tapi jangan ditempatkan di path `GOROOT`**. `GOROOT` itu path instalasi bahasa Go di komputer, dan jangan dipake untuk menyimpan source files project disana.

Langsung praktek aja ya. Di repository ini ada directory `say-hello-module` dan `say-hello-consumer`. Directory `say-hello-module` akan berperan sebagai module, dan directory `say-hello-consumer` berperan sebagai aplikasi Go yang menggunakan module `say-hello-module`.