# Instalasi Laravel 12 Menggunakan Laravel Installer

Repositori ini berisi panduan langkah demi langkah untuk melakukan instalasi Laravel 12 menggunakan Laravel Installer.

## Prasyarat

Sebelum memulai instalasi, pastikan Anda telah menginstal:

- PHP >= 8.2
- Laragon
- Composer
- Ekstensi PHP pendukung seperti `pdo`, `mbstring`, `openssl`, dll
- Web server (seperti Apache atau Nginx)
- MySQL atau database lain sesuai kebutuhan

## Langkah Instalasi

### 1. Buka dan Start Laragon

![image](https://github.com/user-attachments/assets/bd3d4212-0e76-44c9-b03d-4eee44c84ae3)

- Pastikan Apache dan MySQL sudah aktif
- Pastikan juga sudah mengaktifkan ekstensi php seperti `pdo`, `mbstring`, `openssl`

### 2. Buka terminal / CMD

![image](https://github.com/user-attachments/assets/02024960-2acf-4b0a-80f9-c01170a56635)

### 3. Instal Laravel Installer

```bash
composer global require laravel/installer
```

![image](https://github.com/user-attachments/assets/66afc2ba-d4bd-4b3c-99e5-091e5cc4c040)

### 4. Pindah ke direktori Laragon

```bash
cd C:\laragon\www
```

![image](https://github.com/user-attachments/assets/f48a90cf-d7b1-4537-a8e3-f3db7c95542e)

### 5. Buat proyek Laravel

```bash
laravel new proyekbaru
```

![image](https://github.com/user-attachments/assets/720faa16-8dc0-4925-a5a4-8a2a2b4051d1)

- ```'proyekbaru'``` dapat diganti dengan nama proyek yang ingin digunakan

![image](https://github.com/user-attachments/assets/5c8d0ec6-91ad-4761-80d4-445aba47f6f4)

- Pilih starter kit yang ingin dipakai (opsional)

![image](https://github.com/user-attachments/assets/f3d1f468-8b26-498c-b0ce-1bc94eae87eb)

- Pilih testing frameworknya

![image](https://github.com/user-attachments/assets/f9f7e7bd-ba53-411b-b4a8-e05ee8c9a69f)

- Pilih database yang ingin digunakan

![image](https://github.com/user-attachments/assets/5992ce2e-c5a7-4913-9da6-3b1d74f48706)

- Migrate agar membuat struktur database secara default dengan memilih yes

![image](https://github.com/user-attachments/assets/9ce0e368-1665-4d47-a283-1a16d15e8688)

- Instal dependency proyek dan membuat versi build dari aplikasi dengan memilih yes

![image](https://github.com/user-attachments/assets/18c8cf86-6db4-4d3e-b7e9-d9437e618a7b)

- proyek laravel bernama 'proyekbaru' sudah dibuat

### 6. Jalankan Proyek Laravel

```bash
cd proyekbaru
```

![image](https://github.com/user-attachments/assets/a21f6325-b7c8-4a47-b9df-bd149cced0a4)

- Pindah ke direktori proyek tadi yang baru dibuat

```bash
php artisan ser
```

![image](https://github.com/user-attachments/assets/b16220fb-ac27-4331-b1f1-9202dfa49c55)

- Jalankan server lokal

![image](https://github.com/user-attachments/assets/05493bd4-45ac-48b5-abfc-25bfd6484479)

- Buka di browser

![image](https://github.com/user-attachments/assets/2129855a-fab9-4fb2-8271-821e03735baa)

- Domain .test yang disediakan laragon juga dapat digunakan dengan hostname sesuai nama proyek













