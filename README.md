# latihanVCS
Nama	: Reka Hani Latifah Nurhasanah

NIM	: 312010343

Kelas	: TI.20.A.2

## latihan Version Control System (VCS)

1. 	Langkah pertama membuat folder **program 1**  
saya membuat folder nya berada 	di desktop 
2.	Klik kanan pada folder yang sudah di buat tadi lalu klik terminal
	lalu akan muncul seperti gambar di bawah ini:
	
 ![0](https://user-images.githubusercontent.com/72785627/96355351-e8528780-110a-11eb-926f-e5acb233c4df.png)
 
3.	 Kemudian buatlah folder dengan mengetik di terminal `(mkdir latihan1)`

![1](https://user-images.githubusercontent.com/72785627/96355363-0324fc00-110b-11eb-89be-5eb9b63001bc.png)

dan nantinya di folder program 1 didalam nya ada folder baru **latihan1**

4.	Langkah selanjut nya masuk kedalam folder “latihan1” dengan mengetik `(cd latihan1)`

![2](https://user-images.githubusercontent.com/72785627/96355386-69118380-110b-11eb-8f46-c05781f9eaca.png)

5.	Buatlah folder tersebut menjadi repo (repository) dengan cara `git init`.
	Jika benar akan seperti gambar di bawah ini:
	
![3](https://user-images.githubusercontent.com/72785627/96355401-89d9d900-110b-11eb-9737-df259907ea8a.png)

jika sudah seperti ini artinya folder sudah menjadi repo.

6.	Setelah itu buat file README.md dengan mengertik `(echo “latihan 1” >> 	README.md)`

![4](https://user-images.githubusercontent.com/72785627/96355472-31efa200-110c-11eb-8dd4-52dec4943b0b.png)

7.	Cara mengecek file tersebut ketik `git status` maka akan muncul sebagai berikut

![5](https://user-images.githubusercontent.com/72785627/96355506-8dba2b00-110c-11eb-8aa8-7d109793e39f.png)

warna merah tersebut berarti file belum di add.

8. 	Cara nya dengan mengetik `git add <file>` atau jika file yang merah lebih dari satu `( git add . )`

![6](https://user-images.githubusercontent.com/72785627/96355574-336d9a00-110d-11eb-81f3-80a8f1e50c0b.png)

untuk mengecek nya ketik `git status`

![7](https://user-images.githubusercontent.com/72785627/96355613-b1ca3c00-110d-11eb-820b-71593ade5a1e.png)

maka warna file nya akan berubah hijau, file sudah di add.

9.	Langkah selanjutnya commit file tersebut `(git commit -m “pesan”)`

![8](https://user-images.githubusercontent.com/72785627/96355626-dfaf8080-110d-11eb-9a1d-f9254e6b33c1.png)

jika tidak ada masalah maka akan seperti gambar di atas.

10. langkah selanjutnya buat lah akun di github  (http://github.com)

11. Jika sudah memiliki akun buat lah repository baru `new repository` 

![9](https://user-images.githubusercontent.com/72785627/96355666-40d75400-110e-11eb-94e7-0c669da215ad.png)

12.	Langkah selanjutnya mengisi repository nya 

![10](https://user-images.githubusercontent.com/72785627/96355681-695f4e00-110e-11eb-86c4-3f12591df812.png)

- isi repository nya dengan nama “latihan1” ,untuk penamaan bisa di rubah sesui keperluan.	
- untuk description / pesan buat lah sejelas mungkin.
- pilih lah public 
- lalu create repository 

13.	Maka akan muncul seperti gambar berikut 

![11](https://user-images.githubusercontent.com/72785627/96355714-dbd02e00-110e-11eb-8531-ad5ee273ee03.png)

copy link tersebut untuk menghubungkan dengan akun git yang ada di pc/ laptop.

14.	Cara menghubungkan nya dengan mengetik `git remote add origin <link>`

![12](https://user-images.githubusercontent.com/72785627/96355745-7c265280-110f-11eb-8cba-bc946300e9dd.png)

15.	Langkah selanjutnya ketik `git push -u origin master`

![13](https://user-images.githubusercontent.com/72785627/96355762-9d873e80-110f-11eb-82a6-4fe31412a94d.png)

## Pengertian
 - `mkdir <nama file>` untuk membuat file baru
 - `git init` untuk membuat depository local
 - `git status` untuk mengecek apakah ada perubahan di dalam file 
 - `git add` untuk menambah kan file baru 
 - `git commit` untuk menyimpan perubahan kedalam database git.
 - `git remote` untuk menghubungka file ke github
 - `git push` untuk meng upload file ke github
