# SINERGI K3 — kanal rilis publik

Repo ini **hanya** menyimpan APK rilis dan manifest pembaruan yang diunduh
aplikasi. Source code, dokumen laporan, dan keystore tetap berada di repo
privat terpisah.

Aplikasi membaca manifest dari branch `rilis`:

```
https://raw.githubusercontent.com/luthfihadi78/sinergik3-releases/rilis/latest.json
```

Branch `rilis` ditulis ulang setiap rilis dan hanya berisi APK terbaru +
`latest.json` + catatan rilis. Manifest memuat versi, nomor build, URL APK,
ukuran, dan SHA-256; aplikasi menolak memasang APK yang sidiknya tidak cocok.
Pipeline rilis di repo source menerbitkan aset ini secara otomatis.
