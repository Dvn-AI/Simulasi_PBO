LANGKAH-LANGKAH MEMBUAT JAVA GUI "BUKU" DENGAN APLIKASI CRUD DAN MENGKONEKSIKANNYA KE DATABASE
-------------------------------------------------------------------------------------------------------



1. 	Pertama-tama, buat class non-main dengan nama sesuai keinginan. Didalam class tersebut akan diisi dengan method-method yang menjadi pendukung bagi class Java Swing
2. 	Setelah itu, buat class baru dengan tipe JFrameForm, lalu buat struktur tampilan GUI sebagai tampilan output saat class Java Swing dijalankan. Contohnya seperti berikut:


   	 ![image](https://github.com/user-attachments/assets/8d9588b0-7b0b-46b5-a99b-6edfe897267a)


4. 	Langkah selanjutnya, buat inisialisasi dengan menggunakan ‘DriverManager.getConnection()’ untuk koneksi database. Lalu membuat objek ‘PreparedStatement’ dan ‘ResultSet’ untuk menjalankan operasi database. 
5. 	Setelah itu masuk pada pembuatan CRUD. Buat method-method 'Insert' untuk memasukkan dan menyimpan data yang diinginkan.
6.  Kemudian, buat method Update untuk memperbaharui data yang telah diinput dan disimpan.
7. 	Langkah selanjutnya, buat method 'Delete' untuk menghapus data baik yang telah disimpan maupun diupdate.
8.  Setelah itu kita buat 'Clear', fungsinya adalah untuk membersihkan textfield sehingga proses input data lebih cepat. 
9.  Lalu pindah ke laman "Design" pada class terkait, klik kanan pada area tabel. Kemudian pilih events >>> Mouse >>> mouseClicked
10. Fungsi dari mouseClicked sendiri adalah untuk menangkap events atau kejadian yang terjadi saat mouse ditekan. Contoh saat mengklik Insert, maka program akan menangkap maksud pengguna untuk Insert dsb.
11. Terakhir, kita buat method 'Tampil' untuk menampilkan data dari database atau yang sudah kita input sebelumnya kedalam tabel GUI
12. Dan hasilnya akan terlihat seperti ini,


    A. INSERT
    -------------


    ![image](https://github.com/user-attachments/assets/7b680890-ee7b-49a5-b4f2-e85444f114a0)



    B. UPDATE
    ------------


    ![image](https://github.com/user-attachments/assets/4dccd8fc-a11d-40dd-9fc0-1f93f423a488)



    C. DELETE
    -----------


    ![image](https://github.com/user-attachments/assets/7048bd87-4b89-4bc5-99b3-873c98445576)



    



































