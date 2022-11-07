# Writing and Presentation Test Week 2
## **Back End**
### **Back End Development**
- Back End yaitu bagian belakang layar pada website
- Back End adalah semua macam teknologi yang berada di sisi server dari sebuah website
- Bahasa Pemrograman Back End adalah C, JAVA, C++, Phyton, JS, RUST, GOLANG
- Server adalah jaringan komputer yang menyediakan jenis layanan tertentu pada komputer lain.
- Komputer server biasanya didukung dengan prosesor yang bersifat scalable dan RAM yang besar.
- API adalah sekumpulan instruksi program dan protokol yang digunakan untuk membangun aplikasi perangkat lunak.
- REST API bertugas sebagai penghubung/perantara antara Front-End dan Back-end untuk saling bertukar informasi(request dan response).
- MERN adalah salah satu kombinasi teknologi antara front-end dan back-end untuk membuat aplikasi website. 
- MERN adalah singkatan dari MongoDB, Express, React, dan NodeJS. Teknologi Full-stack yang menggunakan 1 bahasa yaitu Javascript.

### **Database intro**
- Database adalah kumpulan informasi yang disimpan didalam komputer secara sistematik dan saling berelasi.
- Database merupakan sekumpulan tabel yang berisikan informasi untuk diolah yang kemudian data tersebut bisa digunakan di dalam sebuah sistem.
- Untuk membuat Database diperlukan sebuah software yang dinamakan dengan DBMS(Database Management System)
- DBMS adalah software yang dapat digunakan oleh user untuk berkomunikasi dengan data yang ada dalam media penyimpanan.
- ipe utama pada Database management System antara lain, Hierarchical, Network, Relational, Non Relational, and Object Oriented.
- Istilah pada database :
1. Table, Table adalah kumpulan value yang dibangun oleh baris dan kolom, yang didalamnya berisikan atribut dari sebuah data.
2. Field, Field adalah kolom dari sebuah tabel dimana masing-masing field memiliki tipe data masing-masing.
3. Record, Record merupakan kumpulan nilai yang saling terkait. Record merupakan isi dari sebuah tabel.

- SQL atau Structured Query Language merupakan suatu bahasa (Language) yang digunakan untuk mengakses database.
- SQL adalah Bahasa Query yang digunakan untuk melakukan interaksi di RDMS (Relational Database Management System) 
- SQL dapat :
1. Membuat dan menampilkan dan menghapus data dalam database
2. Mengatur siapa saja yang mendapatkan akses
3. membuat dan hapus database

- DDL merupakan kumpulan perintah SQL yang digunakan untuk membuat, mengubah dan menghapus struktur dan definisi metadata dari objek-objek Database.
- Alter digunakan untuk mengubah struktur dari tabel yang ada, seperti untuk menambahkan atau menghapus kolom/field.
- Perintah Drop digunakan untuk menghapus Database, Table, dan View atau Index.
- Perintah SELECT digunakan untuk menyeleksi data berdasarkan syarat yang diberikan.
- INSERT	digunakan untuk memasukkan data ke kolom-kolom yang terdapat pada tabel/view.
- UPDATE digunakan untuk melakukan editing pada isi dari kolom (field) yang dipilih. Hal ini dilakukan untuk memperbaiki data lama / terjadi kesalahan.
- DELETE digunakan untuk menghapus data dalam tabel yang menjadi target.
- GRANT digunakan untuk memberikan hak akses pada user.
- REVOKE digunakan untuk mencabut hak akses yang telah diberikan pada user.
- Database relationship adalah relasi atau hubungan antara beberapa tabel dalam bahasa yang kita miliki.
- Relasi antar tabel dihubungkan oleh Primary key dan foreign key.
- Primary key adalah atribut yang tidak hanya mengidentifikasi secara unik suatu kejadian, tapi juga mewakili setiap kejadian suatu entitas.
- Foreign key adalah atribut yang melengkapi relationship dan menunjukan hubungan antara tabel induk dengan tabel anak.
- Macam tipe database relationship :
1. One To One Relationships
2. One to Many and Many to One Relationships
3. Many to Many Relationships
4. Self Referencing Relationships

### **MySQL Lanjutan**
- Database Normalization, teknik analisis data yang mengorganisasikan atribut-atribut data dengan cara mengelompokkan sehingga terbentuk entitas yang non-redundant, stabil, dan fleksible. Tujuannya :
1. Menghilangkan redundan data pada database.
2. Memudahkan juka ada perubahan struktur table database.
3. Memperkecil pengaruh jika ada perubahan dari struktur table database.
 
### **Authentication & Authorization in Express**
- Authentication itu butuh username dan password atau id dan password
- Authorization itu pada saat sudah login kita dapat hak akses apa saja pada saat sudah login.
