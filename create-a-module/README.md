## Cara membuat module

Untuk inisialisasi project atau module Go, langsung aja bikin sebuah directory, masuk ke directory tersebut, lalu jalanin command `go mod init <nama_module>`. Biasanya nama module itu sama dengan nama directory project, tapi ya terserah si kalo mau pake nama lain.

Perlu diingat bahwa project Go di repository ini ga perlu ditempatin di path `$GOPATH/src`. Dimana aja bebas, **tapi jangan ditempatkan di path `GOROOT`**. `GOROOT` itu path instalasi bahasa Go di komputer, dan jangan dipake untuk menyimpan source files project disana.

Langsung praktek aja ya.

1. Kita rilis module dengan nama `github.com/malvinval/gosayhello`, yang disimpan dalam repository GitHub [https://www.github.com/malvinval/gosayhello](https://www.github.com/malvinval/gosayhello).

2. Kita berikan tag release `v1.0.0` ke module tersebut.

## Commands

1. `go mod init github.com/malvinval/gosayhello`
2. `git tag v1.0.0`
4. `git push origin v1.0.0`

Jangan lupa push semuanya ke repository.