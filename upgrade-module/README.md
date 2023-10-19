## Cara upgrade module

Simple caranya. Cukup bikin tag baru aja di Git. Misal, dari yang sebelumnya tag `v1.0.0` jadi tag baru `v1.5.0`. Coba praktekin aja upgrade module `github.com/malvinval/gosayhello` jadi `v1.5.0`.

## Command

`git tag v1.5.0`
`git push origin v1.5.0`

## WARNING

Sekecil apapun perubahan yang kita lakukan ke module, sangat disarankan untuk push perubahannya dengan release tag version yang berbeda dari sebelumnya. Kenapa? coba pelajarin tentang caching di Go yang membuat Go bisa mengingat dependency apa aja yang pernah kita pakai.