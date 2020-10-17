Nama	: Febri Aditiya 
Nim	: 312010212
Kelas 	: TI.20.A2
Latihan 
1.	Langkah pertama membuat folder “program 1” ,saya membuat foldernya berada di desktop
2.	Klik kanan pada folder yang sudah dbuat tadi lalu klik terminal lalu akan muncul seperti gambar di bawah ini:
3.	Kemudian buatlah folder dengan mengetik di terminal “mkdir latihan1![Untitled 1](https://user-images.githubusercontent.com/72905589/96333876-bdc6e700-1096-11eb-95e7-fea86234c4f5.png)

 
4.	Langkah selanjutnya masuk kedalam folder “latihan1” dengan mengetik “cd  latihan1”
 
5.	Buatlah folder tersebut menjadi repo (repository) dengan cara “git init”. Jika benar akan seperti gambar di bawah ini
Jika sudah seperti ini artinya folder sudah menjadi repo
6.	Setelah itu buat file READMI.md dengan mengetik (echo “latihan1” >> READMI.md)
	
 
7.	Cara mengecek file tersebut ketik “git status” maka akan muncul sebagai berikut:
 
Warna merah tersebut berarti file belum di add.
8.	Cara nya dengan mengetik “git add <file>” atau jika file yang merah lebih dari satu (git add.)
 
Untuk mengecek nya ketik “git status”
 
Maka warna file nya akan berubah hijau, file sudah di add.
9.	Langkah selanjutnya commit file tersebut (git commit –m “pesan”)
 
 Jika tidak ada masalah maka akan  seperti gambar di atas.
10.	Langkah selanjutnya buat lah akun di http://github.com 
11.	Jika sudah memiliki akun buat lah repository baru “new repository”
 
12.	Langkah selanjutnya mengisi repository nya 
 
-	Isi repository nya dengan nama “latihan1” ,untuk penamaan bisa di rubah sesuai keperluan. 
-	Untuk description / pesan buat lah sejelas mungkin. 
-	Pilihlah publick 
-	Lalu create repository.
13.	Maka akan muncul seperti gambar berikut.
 
 
Copy link tersebut untuk menghubungkan dengan akun git yang ada di pc/laptop.
14.	Cara menghubungkan nya dengan mengetik “git remote add origin <link>”
 
15.	Langkah selanjutnya ketik  “git push –u origin master “
 
Maka file sudah terhubung dengan akun github anda. 
Pesan 
-	Mkdir <nama file> untuk membuat file baru 
-	git init untuk membuat depositiry local 
-	git add untuk menambah kan file baru 
-	git commit untuk menyimpan perubahan kedalam database git
-	git remote untuk menghubungkan file ke github
-	git push untuk meng upload file ke github
