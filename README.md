# TUGAS 1
- **Nama**    : Kangga Fajarulhakim
- **Kelas**   : TI.23.A.4
- **NIM**     : 312310430
- **Mata Kuliah**: Pemprograman Web 1

melakukan praktikum 

1. membuat struktur halaman web dengan HTML dengan menggunakan tag <header untuk menambahkan judul, <nav yang akan berisikan navigasi untuk halaman-halaman terkait, <div dengan atribut id bernilai intro, dan <a untuk tautan yang megarahkan ke elemen id "intro"
   ![Screenshot_1](https://github.com/user-attachments/assets/aa63bb96-d6f0-4ef6-98b6-2ac2dfa0965e)

  dan hasilnya :
  ![Screenshot_2](https://github.com/user-attachments/assets/e0ab9198-a091-42cd-90a7-b84ff4c8a7fd)

2. membuat css internal yang digunakan untuk memberikan gaya pada elemen HTML untuk halaman web
   ![Screenshot_3](https://github.com/user-attachments/assets/2c247aa6-64f5-4691-a4e3-d7c4baa8e269)

   dan hasilnya :
   ![Screenshot_4](https://github.com/user-attachments/assets/8e176135-1ec7-45d1-824f-6ef2fe9fb079)

3. menambahkan teks dalam elemen paragraf <p berada di tengah dan memiliki warna teks sendiri
   ![Screenshot_5](https://github.com/user-attachments/assets/c0082aed-1e17-49be-b45b-4ae3b2a491f5)

   berikut hasilnya :
   ![Screenshot_6](https://github.com/user-attachments/assets/32f7a6cd-18ae-4bc9-be72-3f1a3e4b275e)
   inline css ini berfungsi ketika kita ingin memberikan gaya khusus pada elemen tunggal tanpa harus menggunakan stylesheet terpisah

4. membuat css eksternal untuk mengatur gaya elemen navigasi <nav dan link navigasi <a
   ![Screenshot_7](https://github.com/user-attachments/assets/0a47460f-8f24-4611-8dba-a11cc4901765)
   nav active untuk menunjukan tautan ini sedang aktif sedangkan nav hover digunakan untuk membuat efek ketika pengguna mengarahkan kursor diatasnya

   dan jangan lupa untuk menghubungkan file css eksternalnya ke dalam HTML
   ![Screenshot_11](https://github.com/user-attachments/assets/2b85fa84-7221-4a0a-98f3-3d5da06de614)

   dan hasilnya :
   ![Screenshot_8](https://github.com/user-attachments/assets/2e439276-811c-45f7-a363-ca09b9c5ad2d)

5. menggunakan id selector dan class selector
   ![Screenshot_9](https://github.com/user-attachments/assets/44711507-f3c4-42e9-a79d-7f771301ee27)
   id selector digunakan untuk menargetkan elemen HTML dengan atribut id= intro dan class selector digunakan untuk menargetkan elemen-elemen HTML yang memiliki atribut class="button

   dan ini hasilnya :
   ![Screenshot_10](https://github.com/user-attachments/assets/b6d0a106-8662-4538-9b5e-b81761899c32)

Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

  *melakukan perubahan dan penambahan*
  ![Screenshot_12](https://github.com/user-attachments/assets/5c8aa3fc-d5f7-43ba-b8a5-a40f830579cd)

  *berikut adalah hasilnya* :
  ![Screenshot_13](https://github.com/user-attachments/assets/ae498d67-88b1-4350-9a67-fe99b816b828)

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
   
  *jawaban* : h1 {...} adalah selektor elemen yang digunakan akan menerapkan gaya pada semua elemen <h1 di halaman web dan semua elemen <h1> yang ada dalam dokumen HTML akan dipengaruhi oleh gaya ini, tanpa terkecuali. sedangkan intro h1 lebih spesifik contoh dalam penerapan disini adalah untuk elemen <h1 yang terletak di dalam elemen dengan ID intro

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

  *jawaban* : internal css untuk menggantikan gaya eksternal jika didefinisikan di dalam halaman sedangkan eksternal css digunakan jika tidak ada aturan lain yang lebih spesifik atau berprioritas lebih tinggi kemudian inline css akan langsung diterapkan pada elemen, sehingga selalu menang kecuali jika ada aturan dengan important yang digunakan

  contoh internal css :
  ![Screenshot_14](https://github.com/user-attachments/assets/193cf4d9-7ff2-421f-b85f-30d5e1c22886)

  contoh eksternal css :
  ![Screenshot_15](https://github.com/user-attachments/assets/1fdea030-ce34-41c6-a49b-2a7d5254006b)

  contoh inline css :
  ![Screenshot_16](https://github.com/user-attachments/assets/5748db72-4680-4cbf-a28a-9ed0eec1cde5)

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"

   ID selektor memiliki spesifisitas lebih tinggi daripada class selektor
   spesifitas dihitung berdasarkan bobot masing-masing selektor :
   - selektor id memiliki bobot 100
   - selektor class memiliki bobot 10
   - selektor elemen memiliki bobot 1
   jadi class selektor berada di tingkat yang lebih rendah dibandingkan ID, tetapi lebih tinggi daripada selektor elemen seperti p

   contoh untuk id selektor :
   ![Screenshot_17](https://github.com/user-attachments/assets/cfaf5f74-25ea-4888-b69a-9436e6ed969d)

   contoh untuk class selector :
   ![Screenshot_18](https://github.com/user-attachments/assets/3e483156-752c-4c2a-b622-5fa1df92a7a7)









   

