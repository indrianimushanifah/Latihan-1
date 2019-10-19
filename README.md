TUTORIAL MENGGUNAKAN GIT UNTUK PENGGUNA AWAL
1. Install Terlebih Dahulu Aplikasi GIT



    ![Screenshot (40)](https://user-images.githubusercontent.com/53387786/67143933-0b99eb00-f29b-11e9-924e-042ea518962a.png)


2. Bukalah Aplikasi git anda dan jalankan Perintah "git config --global user.nama "nama anda" lalu enter dan tulis "git config --global user.email anda"


    ![Screenshot (41)](https://user-images.githubusercontent.com/53387786/67144075-d55d6b00-f29c-11e9-80ff-d3fff159bf93.png)

3. Buka Github.com 
4. Tambahkan repositori baru
    
    Perhatikan beberapa hal berikut :
    
    a. Repositori name : nama repository (latihanku).
    
    b. Description : "biasanya berisi siapa saja yang terlibat" (Dalam project ini aku kosongkan)
    
    c. Public/Private : (Kondisi repository mau dipublikasikan atau pribadi)
    
    d. Initiallize the repository with README : ini adalah isi dokumentasi pada project yang dikerjakan,
        (saya sarankan tidak usah di centang) setelah semua terisi maka klik tombol "create repository"
    
    
    
    ![Screenshot (43)](https://user-images.githubusercontent.com/53387786/67144243-ead39480-f29e-11e9-8056-955e3b9fa761.png)

 5. Buka Aplikasi GIT BASH.
 6. Buat Directory project pratikum pertama dengan nama Latihanku
    - Buat Terlebih dahulu Folder di Data D (saya Buat namanya "indriani")
    - klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad
    - Buat direktory project praktikum pertama dengan nama latihanku
    
      -> $ mkdir latihan1
      
      -> $ cd latihan1
      
      
      ![Screenshot (46)](https://user-images.githubusercontent.com/53387786/67144773-c8447a00-f2a4-11e9-8f20-c4a535f684ef.png)



    - direktory aktif menjadi: d:\indriani\latihanku

 7. Jalankan perintah git init, untuk membuat repository local.
      -> $ git init
    - Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git
    - Pada direktori tersebut, semua perubahan pada working directory akan disimpan.

      ![Screenshot (47)](https://user-images.githubusercontent.com/53387786/67144867-1312c180-f2a6-11e9-95ff-ba6e2ba2ca54.png)
      
      
  8. Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
  
  9. disini kita akan coba buat satu file bernama README.md (text file)

        -> $ echo “#Latihan 1” >> README.md

     - File README.md berhasil dibuat.


        ![Screenshot (48)](https://user-images.githubusercontent.com/53387786/67145025-9b459680-f2a7-11e9-8a10-e98d90550acd.png)
  10. Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
        -> $ git add README.md
        
      - File README.md berhasil ditambahkan.
      
      
        ![Screenshot (49)](https://user-images.githubusercontent.com/53387786/67145115-b6fd6c80-f2a8-11e9-8fc4-74962802144f.png)
  11. Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
       
       -> $ git commit -m “File pertama saya”

      - Perubahan berhasil disimpan.
            


        ![Screenshot (50)](https://user-images.githubusercontent.com/53387786/67145288-6f77e000-f2aa-11e9-9761-910611e02f38.png)

  12. Membuat repository server
  
      - Server reopsitory yang akan kita gunakan adalah http://github.com
  
      - Anda harus membuat akun terlebih dahulu. 
  
      - Pada laman github, klik tombol start a project, atau

      - Dari menu (icon +) klik New Repository
      
      

        ![Screenshot (52)](https://user-images.githubusercontent.com/53387786/67145503-3b052380-f2ac-11e9-85c4-2ecf7fbb1f19.png)
        
        
   13. Menambahkan Remote Repository
   
       - Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local 
       
          repository, sehingga dapat diakses oleh banyak user.
          
       - Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]
       
          -> $ git remote add origin https://github.com/indrianimushanifah/Latihan-1/

       
       
           ![Screenshot (53)](https://user-images.githubusercontent.com/53387786/67145680-6c322380-f2ad-11e9-9ae1-616bb4823066.png)
           
           
   14. Push (Mengirim perubahan ke server)
   
       - Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
       
         -> $ git push -u origin master

       - Perintah ini akan meminta memasukkan username dan password pada akun github.com
       
   15. Melihat hasilnya pada server repository
   
       - Buka laman github.com, arahkan pada repositori-nya. Lalu Refresh.
       
       - Maka perubahan akan terlihat pada laman tersebut.







                                               --> SELAMAT MENCOBA SEMOGA BERMANFAAT <--






