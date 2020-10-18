pembelajaran repositori
Nama  : Anshar Rahmawan
Nim   : 312010308
Kelas : TI.20.A.2

PEMBELAJARAN REPOSITORI
1.	Langkah pertama membuat folder “PROJECT”, saya membuat foldernya di desktop.
2.	Klik kanan pada folder yang sudah dibuat tadi lalu klik terminal lalu akan muncul seperti gambar dibawah ini :


 

![image](https://user-images.githubusercontent.com/72779594/96334037-e1d6f800-1097-11eb-95c4-587efe3e5b53.png)




















3.	Kemudian buatlah folder dengan mengetik terminal “mkdir tugas”

![image](https://user-images.githubusercontent.com/72779594/96334147-b274bb00-1098-11eb-8b8f-3070fd8c0954.png)

 
Dan nantinya di folder PROJECT didalamnya ada folder baru “TUGAS”

4.	Langkah selanjutnya masuk kedalam folder “TUGAS” dengan mengetik “cd TUGAS”

 ![image](https://user-images.githubusercontent.com/72779594/96359504-cde5d180-113d-11eb-8bdc-85037dda4e3e.png)












5.	Buatlah folder tersebut menjadi repo (repository) dengan cara “git init”. Jika benar akan seperti gambar dibawah ini :
![image](https://user-images.githubusercontent.com/72779594/96359508-ddfdb100-113d-11eb-98d8-cee6d4084c50.png)

 
Jika sudah seperti ini artinya folder sudah menjadi repo

6.	Setelah itu buat file README.md dengan mengetik (echo “pemebelajaran repositori” >> README.md)
![image](https://user-images.githubusercontent.com/72779594/96359513-ed7cfa00-113d-11eb-856f-4970b20c84be.png)

 
7.	Cara mengecek file tersebut ketik “git status” maka akan muncul sebagai berikut :
![image](https://user-images.githubusercontent.com/72779594/96359519-fbcb1600-113d-11eb-9848-39031eb10e28.png)

 
Warna merah tersebut berarti file belum di add

8.	Cara nya dengan mengetik “git add <file>” atau jika file yang merah lebih dari satu (git add)
![image](https://user-images.githubusercontent.com/72779594/96359524-0f767c80-113e-11eb-801e-ed966669343d.png)

 



	


Untuk mengeceknya ketik “git status”
 ![image](https://user-images.githubusercontent.com/72779594/96359544-3634b300-113e-11eb-97f1-f2d265fc3141.png)

Maka warna file nya akan berubah hijau, file tersebut sudah di add.
9.	Langkah selanjutnya commit file tersebut (git commit -m “pesan”)
![image](https://user-images.githubusercontent.com/72779594/96359548-4482cf00-113e-11eb-8630-997595e657f5.png)

 
	Jika tidak ada masalah maka akan seperti gambar diatas.




10.	Langka selanjutnya buatlah akun di http://github.com
11.	Jika sudah memiliki akun buatlah repository baru “new repository”
![image](https://user-images.githubusercontent.com/72779594/96359556-595f6280-113e-11eb-939d-6c4b58c34bcb.png)

 

12.	Langkah selanjutnya mengisi repository nya
![image](https://user-images.githubusercontent.com/72779594/96359560-68461500-113e-11eb-9ba2-3b6c210b8ce5.png)

 
-	Isi repository nya dengan nama “latihan 1”, untuk penamaan bisa dirubah sesuai keperluan.
-	Untuk description/pesan buatlah sejalas mungkin.
-	Pilihlah publick
-	Lalu create repository


13.	Maka akan muncul seperti gambar berikut.
![image](https://user-images.githubusercontent.com/72779594/96359568-827ff300-113e-11eb-97e5-a4108db32be2.png)

 	
 
Copy link tersebut untuk menghubungkan dengan akun git yang ada di PC/laptop.
14.	Cara menguhubungkannya dengan mengetik “git remote add origin(origin ini nama default dri system,maka bisa kita ganti dengan nama yang kita inginkan) <link>”
![image](https://user-images.githubusercontent.com/72779594/96359574-9166a580-113e-11eb-80e1-853134fa9a4e.png)

 
	
	

15.	Dan Langkah terakhir ini untuk mengirim/memberikan sinyal informasi kepada server git hub, dengan cara ;   git push -u origin master
 ![image](https://user-images.githubusercontent.com/72779594/96359581-a04d5800-113e-11eb-9850-df7242f67262.png)

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
