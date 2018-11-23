# GIT

## PENGERTIAN
git adalah version control system yang digunakan para developer untuk mengembangkan software secara bersama-bersama. 
## FUNGSI UTAMA
yaitu mengatur versi dari source code program anda dengan mengasih tanda baris dan code mana yang ditambah atau diganti.
## FUNGSI LAIN 
Git ini sebenernya memudahkan programmer untuk mengetahui perubahan source codenya daripada harus membuat file baru seperti 
Program.java, ProgramRevisi.java,  ProgramRevisi2.java, ProgramFix.java. 
Selain itu, dengan git kita tak perlu khawatir code yang kita kerjakan bentrok, karena setiap developer bias membuat branch 
sebagai workspacenya.Fitur yang tak kalah keren lagi, pada git kita bisa memberi komentar pada source code yang telah 
ditambah/diubah, hal ini mempermudah developer lain untuk tahu  kendala apa yang dialami developer lain.

## PERINTAH-PERINTAH DASAR GIT 

| No  |Perintah                |Fungsi                                                                  |
| --- |:----------------------:|:-----------------------------------------------------------------------|
| 1   |Git init  |untuk membuat repository pada file lokal yang nantinya ada folder .git |
| 2   |Git status  |untuk mengetahui status dari repository lokal |
| 3   |Git add  |menambahkan file baru pada repository yang dipilih |
| 4   |Git push  |untuk mengirimkan perubahan file setelah di commit ke remote repository. |
| 5   |Git branch |melihat seluruh branch yang ada pada repository |
| 6   | Git checkout  |menukar branch yang aktif dengan branchyang dipilih |
| 7   | GIt merge |untuk menggabungkan branch yang aktif dan branch yang dipilih |
| 8   |  Git clone  |membuat Salinan repository lokal |

Contoh dari software version control system adalah:
1. github
2. bitbucket
3. snowy evening

# CARA KERJA GIT DAN GITHUB


## Mengapa menggunakan git ?

Kontrol versi adalah satu-satunya cara yang masuk akal untuk melacak perubahan dalam kode, manuskrip, presentasi, dan proyek analisis data. 
Saya biasa membuat file tar.gz bernomor untuk sebuah proyek. Tetapi mengeksplorasi perbedaan itu sulit, untuk sedikitnya. 
Dan jika Anda menggunakan git dengan benar, Anda akan menganotasikan setiap perubahan kecil.
Menggabungkan perubahan kolaborator menjadi mudah. Pernahkah Anda harus berurusan dengan kolaborator yang mengirimkan Anda modifikasi yang didistribusikan 
di banyak file, atau harus berurusan dengan dua orang yang telah melakukan perubahan pada file yang sama pada saat yang bersamaan? 
Menyakitkan. git merge adalah jawabannya.


## Mengapa menggunakan github ?

Github seperti facebook untuk programmer. Semua orang ada di sana. Anda dapat melihat apa yang mereka kerjakan dan dengan mudah membaca dengan teliti 
kode mereka dan membuat saran atau perubahan.
Ini benar-benar open source. "Open source" tidak begitu terbuka jika Anda tidak dapat dengan mudah mempelajarinya. 
Dengan github, semua kode mudah diperiksa, seperti seluruh sejarahnya.
Github menurunkan hambatan untuk berkolaborasi. Sangat mudah untuk menawarkan perubahan yang disarankan pada kode orang lain melalui github. 
Saya bisa memperbaiki kesalahan di perpustakaan phobos untuk bahasa pemrograman D , karena itu dihosting di github. Saya memperbaiki beberapa 
masalah dalam beberapa kode yang sangat berguna yang dikembangkan oleh seseorang yang saya tidak tahu, karena itu di-host di github.
Anda tidak perlu menyiapkan server git. Sangat mudah untuk mengatur semuanya .  

## GITHUB UNTUK SENDIRI
1. Download Git
Silahkan buka website resminya Git (git-scm.com). Kemudian unduh Git sesuai dengan arsitektur komputer kita. 
Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
2. Instal Git
3. Hubungkan Git dengan github dengan menjalankan perintah :
     git config --global user.name "ayuwidyainggit"
	 git config --global user.email widyaayu56020@gmail.com
4. Membuat repo baru di github
5. masuk ke direktori yang akan di push ke github 
6. jalankan git init . akan menambahkan direktory .git
7. jalankan git add * (untuk menambahkan semua projek ke github)
8. git commit -m "first commit" (unutuk menambahkan commit
9. jalankan perintah git remote add origin https://github.com/ayuwidyainggit/git-sendiri-tim.git
10. git push -u origin master (untuk mengupload projek ke github .

## GITHUB UNTUK TEAM

Cara menggunakan pull request bergantung pada jenis model pengembangan yang anda gunakan dalam proyek.
ada dua tipe utama model pengembangan yang digunakan untuk permintaan pull request 
dalam model fork dan pull siapapun bisa mengubah isi repository tanpa perlu akses ke repository sumber.
perubahan akan dapat ditarik ke repository sumber oleh pengelola proyek. Kita dapat mengizinkan siapa saja dengan akses push ke repository untuk membuat 
perubahan pada pull request

Proyek open source = projek yang memberikan kode program kepada pengguna secara bebas dan pengembangannya terbuka.