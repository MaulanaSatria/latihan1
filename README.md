#latihan1
## Tutorial Cara Membuat Git
1. git Init : perintah untuk membuat repository local.
2. git add : perintah untuk menambahkan file baru,atau perubahan pada file pada staging sebelum proses commit.
3. git commit : perintah untuk menyimpan perubahan kedalam database git.
4. git push -u origin master : perintah untuk mengirim perubahan pada repository local menuju server repository.
5. git clone [url] : perintah untuk membuat working directory yang di ambil dari repository server.
6. git remote add origin [url] : perintah untuk menambah remote server/repository server pada local repository (working directory).
7. git pull : perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository.

## Langkah-Langkah Menggunakan Git yang Lebih Detail
1. Membuat repostory dengan perintah 'git init'
2. membuat file dengan perintah contoh ' echo "#latihan1">>\README,md'
3. Mengedit isi file tersebut dengan perintah 'nano <nama_file> -m "catatan"
4. Menggunakan perintah "git add" setelah melakukan perubahan
5. Jika telah yakin dengan perubahannya,berikan catatan dengan menggunakan perintah 'git commit -m "catatan"
6. Membuat sambungan antara repostory lokal dengan server dengan perintah 'git remote add origin'
7. Mengirim perubahan ke server dengan perintah 'git push -u origin master'
