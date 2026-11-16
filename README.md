# Tugas Docker Minggu 9

## Deskripsi
Proyek ini merupakan praktikum membuat halaman profil pribadi menggunakan Docker dan Nginx. Halaman web dijalankan menggunakan container agar dapat diakses melalui browser.

## Struktur File
- Dockerfile: Berisi instruksi untuk membuat Docker image.
- index.html: Berisi halaman profil pribadi.
- README.md: Berisi penjelasan proyek dan cara menjalankannya.

## Cara Build
```bash
docker build -t profil-melania:1.0 .
```

## Cara Run
```bash
docker run -d --name profil-melani -p 8082:80 profil-melania:1.0
```

## Screenshot

![Halaman profil di localhost:8082](hasil_localhost.jpg)
