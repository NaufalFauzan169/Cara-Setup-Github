 <!-- dibuat oleh ai -->
## CARA SETUP GITHUB ##
Cara Membuat Local Repository
1. Buka terminal atau command prompt.
2. Buat folder baru untuk project Anda.
    ```bash
    mkdir nama_folder
    cd nama_folder
    ```
3. Inisialisasi repository Git di dalam folder tersebut.
    ```bash
    git init
    ```
4. Buat file baru atau salin file yang sudah ada ke dalam folder tersebut.
5. Tambahkan file ke staging area.
    ```bash
    git add nama_file
    ```
6. Commit perubahan yang telah Anda buat.
    ```bash
    git commit -m "Pesan commit pertama"
    ```
7. Buat repository baru di GitHub.
8. Salin URL repository yang telah Anda buat.
9. Hubungkan repository lokal dengan repository di GitHub.
    ```bash
    git remote add origin <URL_REPOSITORY>
    ```
10. Push perubahan ke repository di GitHub.
    ```bash
    git push -u origin master
    ```
11. Jika Anda melakukan perubahan di file, ulangi langkah 5 hingga 10 untuk mengupdate repository di GitHub.
12. Untuk menarik perubahan dari repository di GitHub ke lokal, gunakan perintah berikut:
    ```bash
    git pull origin master
    ```
13. Untuk melihat status repository, gunakan perintah berikut:
    ```bash