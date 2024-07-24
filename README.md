Sistem informasi sekolah berbasis laravel 8 dengan template dashboard
[Stisla](https://getstisla.com/)


# Sistem Informasi Sekolah



## Fitur

- CRUD Jurusan
- CRUD Mata Pelajaran
- CRUD Guru
- CRUD Kelas
- CRUD User
- CRUD Materi
- CRUD Tugas & Jawaban
- CRUD Jadwal Sekolah


## Screenshots

![Login](https://i.ibb.co/QrvFVsq/download.png)

![Dashboard](https://i.ibb.co/4Vvff5F/Screenshot-3.jpg)


## Instalasi

clone project atau download

```bash
  git clone git@github.com:gunawantalessy/siakad_sekolah_kelompok1.git
  cd siakad_sekolah_kelompok1
  npm install
  composer install
  cp .env.example .env
```

Buka `.env` dan atur database anda
```bash
  DB_PORT=3306
  DB_DATABASE=laravel
  DB_USERNAME=root
  DB_PASSWORD=
```

Install website
```bash
  php artisan key:generate
  php artisan migrate --seed
```

Jalankan website
```bash
  php artisan serve
```
## Default akun untuk testing

Admin
```bash
  email : admin@mail.com
  password : admin123
```

Guru
```bash
  email : budi@mail.com
  password : budi123

  email : gunawan@mail.com
  password : gunawan123
```

Siswa
```bash
  email : kevin@mail.com
  password : kevin123

  email : siska@mail.com
  password : siska123
```


