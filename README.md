Membuat folder baru bernama "artists_who_can_sing"
```bash
mkdir artists_who_can_sing
```
Masuk kedalam folder
```bash
cd artists_who_can_sing
```
Download file zip menggunakan wget 
```bash
wget --no-check-certificate 'https://drive.google.com/uc?export=download&id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut' -O tutorials.zip
```
Unzip dan memindahkan file zip kedalam folder baru bernama "singing_tutorials"
```bash
unzip tutorials.zip -d singing_tutorials
```
Menampilkan semua list yang ada
```bash
ls -la
```
Mencari flag
```bash
find . -type f -iname "*opera*NBAYoungboy*" -exec grep -i "FLAG" {} \;
```
Download file yang ada dalam flag
```bash
wget -O plsrunmeiamnotmalwarefr https://files.catbox.moe/9l4qu8 --no-check-certificate
```
Ganti permission dari program yang sudah di download dari flag
```bash
chmod +x plsrunmeiamnotmalwarefr
```
Jalankan program
```bash
./plsrunmeiamnotmalwarefr
```
Buat file untuk memberhentikan program yang berjalan
```bash
touch ransom.moolah
```
Matikan program
