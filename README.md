# FSMB

FSMB adalah Sebuah alat berbasis GUI untuk melakukan Brute Force Attack pada protokol SMB (Server Message Block) menggunakan Hydra dan Nmap. Alat ini dirancang untuk tujuan edukasi dan pengujian keamanan pada sistem yang Anda miliki atau memiliki izin untuk diuji.

## Persyaratan Sistem

- Python 3.x
- Nmap
- Hydra
- PyQt5

## Cara Instal

```
apt-get update
apt-get install python3
apt-get install python3-pip
apt-get install python3.12-venv
apt-get install git
git clone https://github.com/fixploit03/FSMB.git
cd FSMB
python3 -m venv .modules
source .modules/bin/activate
pip3 install -r requirements.txt
cd src
chmod +x fsmb
cp fsmb /usr/local/bin
```

