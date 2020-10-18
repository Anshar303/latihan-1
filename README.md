# pembelajaran repositori
 Nama : Anshar Rahmawan
 
Nim : 312010308

Kelas : TI.20.A.2

## Latihan 4
1.	Langkah pertama membuat folder **program 1**, saya membuat foldernya di desktop.
2.	Klik kanan pada folder yang sudah dibuat tadi lalu klik terminal lalu akan muncul seperti gambar dibawah ini :


 

![image](https://user-images.githubusercontent.com/72779594/96334037-e1d6f800-1097-11eb-95c4-587efe3e5b53.png)




















3.	Kemudian buatlah folder dengan mengetik terminal `mkdir tugas`

![image](https://user-images.githubusercontent.com/72779594/96334147-b274bb00-1098-11eb-8b8f-3070fd8c0954.png)

 
Dan nantinya di folder program 1 didalamnya ada folder baru “latihan 4”

4.	Langkah selanjutnya masuk kedalam folder “tugas” dengan mengetik `cd tugas`

 











5.	Buatlah folder tersebut menjadi repo (repository) dengan cara `git init`. Jika benar akan seperti gambar dibawah ini :

 
Jika sudah seperti ini artinya folder sudah menjadi repo

6.	Setelah itu buat file **README.md** dengan mengetik `(echo “pemebelajaran repositori” >> README.md)`

 
7.	Cara mengecek file tersebut ketik “git status” maka akan muncul sebagai berikut :

 
Warna merah tersebut berarti file belum di add

8.	Cara nya dengan mengetik “git add <file>” atau jika file yang merah lebih dari satu (git add)

 



	


Untuk mengeceknya ketik `git status`
 
Maka warna file nya akan berubah hijau, file tersebut sudah di add.
9.	Langkah selanjutnya commit file tersebut `(git commit -m “pesan”)`

 
	Jika tidak ada masalah maka akan seperti gambar diatas.




10.	Langka selanjutnya buatlah akun di http://github.com
11.	Jika sudah memiliki akun buatlah repository baru **new repository**

 

12.	Langkah selanjutnya mengisi repository nya

 
-	Isi repository nya dengan nama **latihan4**, untuk penamaan bisa dirubah sesuai keperluan.
-	Untuk description/pesan buatlah sejalas mungkin.
-	Pilihlah publick
-	Lalu create repository


13.	Maka akan muncul seperti gambar berikut.

 	
 
Copy link tersebut untuk menghubungkan dengan akun git yang ada di PC/laptop.
14.	Cara menguhubungkannya dengan mengetik `git remote add origin(origin ini nama default dri system,maka bisa kita ganti dengan nama yang kita inginkan) <link>`

 
	
	

15.	Dan Langkah terakhir ini untuk mengirim/memberikan sinyal informasi kepada server git hub, dengan cara ;   `git push -u origin master`
 
	NOTE ;
		Mengapa disini saya menggunakan 	git push -u anshar master
Karna di data sebelum nya saya telah mengganti nama default system itu menjadi (anshar) .
Pesan
-	 Mkdir <nama file> untuk membuat file baru
-	Git init untuk membuat depository local
-	Gid add untuk menambahkan file baru
-	Git commit untuk menyimpan perubahan kedalam database git
-	Git remote untuk menghubungkan file ke github
-	Git push untuk mengupload file ke github
