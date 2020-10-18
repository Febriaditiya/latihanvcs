Nama	: Febri Aditiya

Nim	: 312010212

Kelas 	: TI.20.A2

## Latihan

1. Langkah pertama membuat folder **program 1** ,saya membuat foldernya berada di desktop!
2. Klik kanan pada folder yang sudah dbuat tadi lalu klik terminal lalu akan muncul seperti gambar di bawah ini:

![Untitled](https://user-images.githubusercontent.com/72905589/96337324-764d5480-10b0-11eb-8947-a2356e00411a.png)

3.	Kemudian buatlah folder dengan mengetik di terminal `mkdir latihan1`

![Untitled 1](https://user-images.githubusercontent.com/72905589/96333876-bdc6e700-1096-11eb-95e7-fea86234c4f5.png)

 
4.	Langkah selanjutnya masuk kedalam folder **latihan1** dengan mengetik `cd  latihan1`

![Untitled 2](https://user-images.githubusercontent.com/72905589/96337682-02607b80-10b3-11eb-9dab-338bb8f97aee.png)

 
5.	Buatlah folder tersebut menjadi repo (repository) dengan cara `git init`. Jika benar akan seperti gambar di bawah ini

![Untitled3](https://user-images.githubusercontent.com/72905589/96337763-93375700-10b3-11eb-86a2-9757e967bc08.png)

Jika sudah seperti ini artinya folder sudah menjadi repo

6.	Setelah itu buat file **READMI.md** dengan mengetik `(echo “latihan1” >> READMI.md)`

![Untitled4](https://user-images.githubusercontent.com/72905589/96337822-08a32780-10b4-11eb-83e4-41c2f22db71f.png)

	
 
7.	Cara mengecek file tersebut ketik `git status` maka akan muncul sebagai berikut:

![Untitled5](https://user-images.githubusercontent.com/72905589/96337844-2ff9f480-10b4-11eb-9cea-c371aee0911c.png)
 
Warna merah tersebut berarti file belum di add.

8.	Cara nya dengan mengetik `git add <file>` atau jika file yang merah lebih dari satu (git add.)

![Untitled6](https://user-images.githubusercontent.com/72905589/96337880-6768a100-10b4-11eb-94b2-0aeebe934a29.png)

 
Untuk mengecek nya ketik `git status`

![Untitled7](https://user-images.githubusercontent.com/72905589/96337937-c4645700-10b4-11eb-9563-e82ecefe5449.png)

 
Maka warna file nya akan berubah hijau, file sudah di add.

9.	Langkah selanjutnya commit file tersebut `(git commit –m “pesan”)`

![Untitled11](https://user-images.githubusercontent.com/72905589/96337988-4785ad00-10b5-11eb-9964-ebf2f0a05717.png)
 
 Jika tidak ada masalah maka akan  seperti gambar di atas.
 
10.	Langkah selanjutnya buat lah akun di http://github.com 

11.	Jika sudah memiliki akun buat lah repository baru **new repository**

![Untitled8](https://user-images.githubusercontent.com/72905589/96338004-68e69900-10b5-11eb-91d9-a7ddc3939428.png)

 
12.	Langkah selanjutnya mengisi repository nya 

![Untitled9](https://user-images.githubusercontent.com/72905589/96338028-8d427580-10b5-11eb-81e9-fbdc9e02887a.png)
 
- Isi repository nya dengan nama “latihan1” ,untuk penamaan bisa di rubah sesuai keperluan. 
- Untuk description / pesan buat lah sejelas mungkin. 
- Pilihlah publick 
- Lalu create repository.

13.	Maka akan muncul seperti gambar berikut.

![Untitled10](https://user-images.githubusercontent.com/72905589/96338049-ad723480-10b5-11eb-8693-f48a2394f883.png)

 
 
Copy link tersebut untuk menghubungkan dengan akun git yang ada di pc/laptop.

14.	Cara menghubungkan nya dengan mengetik `git remote add origin <link>`

![Untitled11](https://user-images.githubusercontent.com/72905589/96338096-fd50fb80-10b5-11eb-90c9-835ecfc886f7.png)

 
15.	Langkah selanjutnya ketik  `git push –u origin master`

![Untitled11](https://user-images.githubusercontent.com/72905589/96338096-fd50fb80-10b5-11eb-90c9-835ecfc886f7.png)

 
Maka file sudah terhubung dengan akun github anda. 

## Pesan 
- `Mkdir <nama file>` untuk membuat file baru 
- `git init` untuk membuat depositiry local 
- `git add` untuk menambah kan file baru 
- `git commit` untuk menyimpan perubahan kedalam database git
- `git remote` untuk menghubungkan file ke github
- `git push` untuk meng upload file ke github
