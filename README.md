"# Alpro2" 
Langkah-langkah pembuatan repository melalui github dan local repository
1.	Membuat akun untuk Github, sign up dengan memasukkan email dan password
2.	Membuat repository dalam Github dengan mengklik logo + dan "New repository". Kemudian masukkan nama repository-nya, setelah itu create repository.
3.	File readme.md dapat dibuat juga melalui github dengan Add a README file. 
Kemudian bisa di-edit dengan mengklik nama file-nya, yaitu README.md. Lalu dilanjutkan dengan edit this file.
4.	Apabila dengan local repository, maka setelah membuat repository baru.
Setelah itu, copy link https yang ada untuk di clone ke dalam local repository. 
Bisa juga dengan mengcopy line berikut langsung ke command prompt.
Sehingga di local repository sudah muncul file README.md, file README.md ini kemudian ter-push kembali ke github.
5.	Setelah file README.md di edit sendiri lagi, ketika mengecek dengan git status, maka akan muncul keterangan modified dengan warna merah di nama filenya. Setelah itu di add . untuk mengubahnya jadi hijau, artinya untuk memasukkan file baru it uke dalam index sehingga terbaca. Kemudian di git commit -m "perubahan baru" untuk menunjukkan perubahan dan perbedaan dari yang pertama. Untuk di cek, menggunakan git log, nantinya akan tercantum/tercetak untuk first init dan perubahan yang baru. 
6.	Untuk dimasukkan ke dalam repository github, menggunakan git push origin master.


Git Basics Operations yang digunakan untuk langkah-langkah sebelumnya:
1.	Git config
Untuk mengatur konfigurasi git, mulai dari username dan email.
git config user.name ...
git config user.email ..
2.	Git init
Untuk membuat repository pada file local, sehingga nanti ada folder .git 
3.	Git add
Untuk menambahkan file baru ke repository local sehingga terbaca.
4.	Git clone
Untuk membuat salinan (dalam hal ini dari repository github) ke repository local.
5.	Git commit
