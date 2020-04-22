# buku-alamat.github.io
Langkah-langkah pembuatan Buku Alamat:
1. Membuat project baru Angular dilakukan menggunakan command line (cmd) NodeJs jika menggunakan Windows. tuliskan perintah berikut : ng new buku-alamat
2. Akan muncul output "Would you like to add Angular routing? (y/N)" jawab dengan mengetik "y"
3. Selanjutnya akan muncul pertanyaan "Which stylesheet format would you like to use?" pilihlah CSS
![image](https://user-images.githubusercontent.com/62319661/79248508-204fe800-7ea6-11ea-91e7-ced15686c7c5.png)
![image](https://user-images.githubusercontent.com/62319661/79248569-3198f480-7ea6-11ea-880e-e9658612c48e.png)
4. kemudian masuk kedalam folder yang sudah di buat tadi. tuliskan perintah : cd buku-alamat
5. Setelah masuk kedalam folder aplikasi Angular tulislah perintah:  ng serve
![image](https://user-images.githubusercontent.com/62319661/79248842-92c0c800-7ea6-11ea-8a3d-332e5c77f72e.png)
6. Tanda proses ini berhasil adalah munculnya informasi Compiled successfully. Buka browser dan masuk ke alamat localhost:4200
7. Untuk mengintegrasikan material kedalam project Angular tulis perintah berikut ini: ng add @angular/material
![image](https://user-images.githubusercontent.com/62319661/79249167-137fc400-7ea7-11ea-960b-2ad326cd6e7d.png)
8. Membuat Component baru untuk membuat desain dialog, tuliskan perintah berikut: ng generate component tambah-alamat
9. buat komponen baru dengan menuliskan perintah berikut:  ng generate component detail-alamat
10. buat komponen dialog-konfirmasi menggunakan perintah berikut: ng g c dialog-konfirmasi
![image](https://user-images.githubusercontent.com/62319661/79249956-365ea800-7ea8-11ea-8f94-c328b18e04d7.png)
11. Unduh file dari repositori github https://github.com/faridsurya/restapi_codeigniter3. Ekstrak file tersebut dan pindahkan ke folder htdocs pada XAMPP. Ubah nama folder menjadi rest-api.
12. Berikutnya adalah membuat api.service.ts dengan menjalankan perintah berikut:  ng g service api
![image](https://user-images.githubusercontent.com/62319661/79250397-c7ce1a00-7ea8-11ea-9f25-44ce33cfdd3c.png)
13. kemudian setting kode dari beberapa file tertentu. berikut tampilan kode dari file yang sudah di setting
![image](https://user-images.githubusercontent.com/62319661/79251301-28118b80-7eaa-11ea-9fff-2ab2ddc78d67.png)
![image](https://user-images.githubusercontent.com/62319661/79251343-3790d480-7eaa-11ea-81c3-12c58c70904e.png)
![image](https://user-images.githubusercontent.com/62319661/79251371-4081a600-7eaa-11ea-9e43-ff1b5d75b1d3.png)
![image](https://user-images.githubusercontent.com/62319661/79251440-542d0c80-7eaa-11ea-8e47-20f278d99b53.png)
![image](https://user-images.githubusercontent.com/62319661/79251462-5d1dde00-7eaa-11ea-8b83-11d9f39a8efa.png)
![image](https://user-images.githubusercontent.com/62319661/79251486-660eaf80-7eaa-11ea-8160-acb38cda246a.png)
![image](https://user-images.githubusercontent.com/62319661/79251522-758df880-7eaa-11ea-845a-bb1c8afcd6ca.png)
![image](https://user-images.githubusercontent.com/62319661/79251544-7d4d9d00-7eaa-11ea-8c33-b6ff4df8e1dd.png)
![image](https://user-images.githubusercontent.com/62319661/79251571-83437e00-7eaa-11ea-929f-ede79d11b308.png)
![image](https://user-images.githubusercontent.com/62319661/79251591-89395f00-7eaa-11ea-980b-8a82d92275e5.png)
![image](https://user-images.githubusercontent.com/62319661/79251847-ee8d5000-7eaa-11ea-8d60-a393f97e46f9.png)
![image](https://user-images.githubusercontent.com/62319661/79251876-f6e58b00-7eaa-11ea-9aab-e928c767a20f.png)
![image](https://user-images.githubusercontent.com/62319661/79251922-08c72e00-7eab-11ea-84ef-f8c3a6c67352.png)
![image](https://user-images.githubusercontent.com/62319661/79251935-0e247880-7eab-11ea-986d-68242bef94e8.png)
14. selanjutnya membuat database. Untuk melakukan hal ini, buka aplikasi Phpmyadmin melalui browser dengan alamat localhost/phpmyadmin. Buatlah database baru dengan nama buku_alamat.
![image](https://user-images.githubusercontent.com/62319661/79252429-c94d1180-7eab-11ea-9cfe-39694eaabc2f.png)
15. Buatlah contoh data sample dengan mengeksekusi kode sql berikut ini: INSERT INTO `alamat` (`id`, `nama`, `hp`, `email`, `alamat`, `kota`, `provinsi`,`kodepos`) VALUES (NULL, 'Syarafina', '082325435347', 'ara@gmail.com', 'sorosutan', 'Yogyakarta', 'DIYogyakarta','55162');
16. Tahap terakhir adalah mendistribusikan aplikasi Angular agar dapat dijalankan pada browser. Jalankan perintah berikut ini: ng build --base-href ./
![image](https://user-images.githubusercontent.com/62319661/79257196-7f682980-7eb3-11ea-8781-d4ccb317f665.png)
17. Perintah tersebut akan menciptakan folder dist pada proyek Angular. Pindahkan isi folder tersebut pada folder htdocs pada Xampp. Pastikan nama folder pada htdocs adalah buku-alamat. Akses melalui browser dengan alamat localhost/buku-alamat.
![image](https://user-images.githubusercontent.com/62319661/79255233-20ed7c00-7eb0-11ea-837a-b3736ac6338c.png)

selama pembuatan buku alamat ini terdapat berbagai masalah yang di dominasi dari error coding. jadi sangat di anjurkan untuk melihat dan memahami lebih detail dan jelas apa saja fungsi yang harus dimasukkan dan kemana arah fungsi tersebut di tujukan. 
