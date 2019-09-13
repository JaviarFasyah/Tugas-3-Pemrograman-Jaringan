# Tugas-3-Pemrograman-Jaringan
### Javiar Fasyah         1301164477
### Hilmi Triandi N		    1301164286
### Fahrur Rozi Syarbini	1301164213  

**Jawaban Soal No. 1:**  
![1_screenshot.PNG](/screenshot%20n%20fsm/1_screenshot.PNG)  
program ini mencari alamat melalui hostname yang dimasukan melalui argumen. Dan akan menampilkan error apabila masukan tidak sesuai  
  
**Jawaban Soal No. 2:**  
![2_screenshot.png](/screenshot%20n%20fsm/2_screenshot.png)  
program ini melakukan lookupport dengan masukan networktype dan service sebagai masukan, kalau masukan sesuai program akan mengembalikan port yang sesuai juga.  

**Jawaban Soal No. 3:**  
![3_screenshot.png](/screenshot%20n%20fsm/3_screenshot.png)  
Program ini bekerja dengan menggunakan input argumen host serta port ketika menjalankan programnya. Setelah itu, host dari input akan dicari dan mengembalikan alamat dari host jika ditemukan. Alamat ini digunakan untuk memanggil host yang dimaksud, lalu jika mendapat balasan maka program akan mencatat info header dari host dan mencetaknya sebagai hasil dari program.  
![3_fsm.png](/screenshot%20n%20fsm/3_fsm.png)  

**Jawaban Soal No. 4:**  
![4_screenshot.png](/screenshot%20n%20fsm/4_screenshot.png)  
Pengguna mengirimkan ping kepada sebuah host berupa sebuah pesan byte delapan index array disertai dengan checksumnya pada index kedua dan ketiga (mula-mula nol). Setelah dihitung checksum dari pesan, dimasukan nilai checksum ke index dua dan tiga dan dikirimkan host tujuan. Sama seperti soal no. 3, program akan mencari alamat input argumen host lalu mengirimkan pesan ke alamat host. Program lalu mendapat balasan berupa pesan yang nilai index nolnya berubah dan juga checksum pada index keduanya berubah (dari 8 => 0, 247 => 255) yang merupakan hasil penghitungan ulang checksum dari host tujuan.
