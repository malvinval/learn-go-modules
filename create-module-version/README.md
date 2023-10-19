## Membuat versi modul

Go sudah terintegrasi baik dengan Git. Jadi, kalo kita mau memberikan versi ke module yang kita buat, cukup jalanin command `git tag`. Contoh, kita mau kasih versi 1.0.0 ke module sayhello maka commandnya adalah 

```
cd say-hello-module
git tag v1.0.0
git push v1.0.0
```