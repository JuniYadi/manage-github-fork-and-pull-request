## Manage GitHub untuk Team Member

Pada halaman ini akan saya jabarkan penggunaan fork, clone, branch dan pull request untuk github dan vscode.

## Fork dan Clone Repository

### Fork Induk Repository
* Klik `Fork` Pada Pojok Kanan Atas Repository Induk (Lihat Gambar)

![01.png](images/01.png)

* Jika `Fork` berhasil, maka kita akan bisa melihat repository Induk didalam akun github yang kita gunakan (Lihat Gambar)
* Kemudian Copy `URL GIT` pada akun kita tersebut, karena kita akan menggunakan repository `Fork` ini untuk push, **Jangan Push langsung ke Repository Induk**

![02.png](images/02.png)

### Clone Repository ke PC/ Laptop
* **PENTING: yang saya clone, bukan dari pojok-projects, tetapi dari JuniYadi yang kita fork pertama tadi, sesuaikan URL Clone seperti gambar ke-2 diatas**
![03.png](images/03.png)

## Manage Code dengan VSCode

### Tambahkan folder repository ke VSCode (Klik: Add Folder)
![04.png](images/04.png)
![05.png](images/05.png)

### Buat Branch Baru untuk Manage Codingan Kita
* Pada Keyboard, tekan `CTRL + P`
* Kemudian ketik: `>git` maka akan muncul list git command (Lihat Gambar)
* Kemudian masukkan nama branch baru anda

![06.png](images/06.png)


### Check Branch VSCode
* Pastikan branch yang digunakan pada VSCode sesuai dengan branch baru yang telah dibuat tadi.
* Karena kita bekerja dalam tim, usahakan untuk tidak menggunakan branch `master` agar ketika `Pull Request` ke Repository induk tidak terjadi bentrok

![07,png](images/07.png)

### Push New Branch ke Github
* Sebelum memulai coding, kita push dahulu branch baru ini ke github pada repository yang kita gunakan
* Masuk ke `Source Control` pada menu sebelah kiri
* Klik `titik tiga` kemudian klik `Publish Branch`

![08.png](images/08.png)

![09.png](images/09.png)

### Push Commit Code dengan VSCoode
* Untuk push, kita juga bisa langsung dari VSCode
* Klik Tanda `+` pada `Source Control`, ini untuk stage coddingan kita

![10.png](images/10.png)

* Masukkan `Comment Commit` pada box kemudian klik tanda centang

![11.png](images/11.png)

* Lakukan push codingan ke repository github dengan mengklik titik tiga disebelah tombol centang tadi dan klik `push`

![12.png](images/12.png)

* Anda bisa melakukan stag commit sebanyak apapun, perubahan coding anda tidak akan hilang
* Anda juga bisa melakukan bulk commit push, jadi tidak harus stage commit kemudian push satu per-satu

### Cek Perubahan Codingan pada GitHub
* Ubah branch repository sesuai dengan repository baru yang kita buat
* Klik `Compare & Pull Request`

![13.png](images/13.png)

### Pull Request 
* Setelah kita mengecek commit apa saja yang terpush ke branch, saatnya melakukan Pull Request
* Pada `Compare & Pull Request`, dibawahnya ada pilihan untuk `Pull Request` dan klik saja maka akan terkirim.

![14.png](images/14.png)

* Pull Request telah terkirim, silahkan tunggu review, jika tidak ada conflict, maka akan gambar hijau seperti diatas
* jika Pull Request ada conflict, pastikan kami memperbaiki dulu conflictnya ya dengan push codingan mana yang conflict