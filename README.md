# SINERGI K3 — kanal rilis publik

Repo ini **hanya** menyimpan APK rilis dan manifest pembaruan yang diunduh
aplikasi. Source code, dokumen laporan, dan keystore tetap berada di repo
privat terpisah.

Aplikasi membaca:

```
https://github.com/luthfihadi78/sinergik3-releases/releases/latest/download/latest.json
```

Setiap rilis berisi APK arm64 bertanda tangan dan `latest.json` dengan versi,
nomor build, URL APK, ukuran, dan SHA-256. Pipeline rilis di repo source
menerbitkan aset ini secara otomatis.
