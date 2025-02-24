# Cara Instal FSMB

## 1. Update Sistem

Pastikan sistem Anda dalam keadaan terbaru dengan menjalankan:  

```
sudo apt-get update
```

## 2. Instal Dependensi yang Dibutuhkan

Instal Python, pip, virtual environment, dan Git:

```
sudo apt-get install python3 python3-pip python3.12-venv nmap hydra git
```

Jika python3.12-venv tidak tersedia, gunakan:

```
sudo apt-get install python3-venv
```

## 3. Klon Repository dari GitHub

Unduh source code FSMB dari GitHub dengan perintah:

```
git clone https://github.com/fixploit03/FSMB.git
```

## 4. Pindah ke Direktori FSMB

Masuk ke dalam folder proyek:

```
cd FSMB
```

## 5. Buat Virtual Environment

Buat virtual environment untuk mengelola dependensi proyek:

```
python3 -m venv .modules
```

## 6. Aktifkan Virtual Environment

Aktifkan virtual environment sebelum menginstal dependensi:

```
source .modules/bin/activate
```

## 7. Instal Modul yang Dibutuhkan

Gunakan pip untuk menginstal semua dependensi dari requirements.txt:

```
pip install -r requirements.txt
```

## 8. Pindah ke Direktori src

Masuk ke dalam folder utama program:

```
cd src
```

9. Beri Izin Eksekusi pada Program

Pastikan program dapat dieksekusi dengan:

```
chmod +x fsmb
```

## 10. Salin Program ke /usr/local/bin

Salin file eksekusi agar bisa dijalankan dari mana saja:

```
sudo cp fsmb /usr/local/bin
```

Selesai deh ^_^
