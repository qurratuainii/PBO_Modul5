# PBO_Modul5
*Latihan 1: Kata Terakhir (versi BufferedReader)

--> kita menggunakan kelas BufferedReader yang berada di java.io package untuk mendapatkan input dari keyboard. Langkah-langkah yang diperlukan antara lain :

a. Menambahkan pada bagian paling atas code : import java.io*

b. Tambahkan statement : BufferedReader dataIn = new BufferedReader(new InputStreamReader(System.in));

c. Deklarasi String temporer untuk mendapatkan input, dan gunakan fungsi readLine() untuk mendapatkan input dari keyboard. Ini harus diketikkan di dalam blok try-catch

BufferedReader dataIn = new BufferedReader(new InputStreamReader(System.in)); 

--> ini mendeklarasikan sebuah variabel bernama dataIn dengan tipe kelas BufferedReader.

String word1 = "";

--> statemnet ini merupakan tempat untuk menyimpan input dari user. Variabel word1 diinisialisasi sebagai String kosong "". 

System.out.print("Enter word 1: ");

--> ini memeberikan output string pada layar menanyakan nama user.

word1 = dataIn.readLine();

--> mendapatkan input dari user dan memberikan sebuah nilai String. Nilai ini akan disimpan ke dalam variabel word1, yang akan digunakan [ada statement akhir untuk menyambut user. 

*Latihan 2: Kata Terakhir (versi JOptionpane)

--> selain BufferedReader kita dapat menggunakan kelas JOptionpane yang didapatkan dari javax.swing package. JOptionpane membuat kemudahan dengan memunculkan dialog box standar yang memberikan kepada user sebuah nilai atau informasi sesuatu. 

word1 = JOptionpane.showInputDialog("Enter word 1");

--> membuat sebuah JOptionpane input dialog yang akan menampilkan dialog dengan sebuah pesan, sebuah textfield dan tombol OK. Hasil dari dialog tersebut adalah String dan disimpan ke dalam variabel word1.

String msg = " " + word1 + " " + word2 + " " + word3;
 
--> statement ini untuk membuat pesan yang akan disimpan ke dalam variabel msg.

JOptionPane.showMessageDialog(null, msg);

--> pada bagian ini untuk menampilkan sebuah dialog yang memiliki sebuah pesan dan tombol OK

