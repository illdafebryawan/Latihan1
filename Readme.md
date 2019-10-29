# Latihan
##Latihan 1

###Megenal VCS (Version Control System) adalah sebuah infrastruktur yang dapat mendukung pengembangan software secara kolaboratif. Setiap anggota yang berada di dalam sebuah tim pengembangan software dapat menulis kode programnya masing - masing kemudian digabungkan ke server yang sudah memiliki VCS yang digunakan.

Selain mengandalkan konkurensi yang dapat mempercepat pengembangan software, VCS juga mempunyai kemampuan untuk kembali ke versi software sebelumnya jika terjadi suatu bencana terhadap versi software yang sedang dikembangkan saat ini. Kemampuan ini disebut reversibility. Selain itu, dengan menggunakan VCS setiap perubahan pada software seperti penambahan file atau pengubahan isi file dapat dipantau bagian mana yang diubah dan siapa yang mengubah. Sehingga pengerjaan software akan lebih transparan dan terukur.

####Langkah langkah menggunakan git

    Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

    Buka dan download installer GIT untuk Windows.
    Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.

Installing GIT on Windows 3. Jalankan perintah berikut ini di terminal:

git config --global user.name "John Smith" git config --global user.email "example@email.com" Catatan: Jangan lupa mengganti John Smith dan example@email.com dengan detail login Anda sendiri.

Untuk memulai, Anda bisa membuat repository atau men-checkout yang sudah ada. Setelah instalasi, perintah git-init akan men-setup semuanya. Selain itu, perintah git clone bisa membuat salinan repository lokal untuk user.

Membuat file dengan perintah, contoh 'echo "# Latihan1" > Readme.md' Mengedit isi file tersebut dengan perintah 'nano <nama_file>' Gunakan perintah "git add" setelah melakukan perubahan

Jika telah yakin dengan perubahannya, berikan catatan dengan menggunakan perintah 'git commit -m "catatan"' Membuat sambungan antara repository lokal dengan server dengan perintah 'git remote add origin ' Mengirim perubahan ke server dengan perintah 'git push -u origin master'
