<h3 align="center">LAPORAN PRAKTIKUM</h3>
<h3 align="center">APLIKASI BERBASIS PLATFORM</h3>
<h3 align="center">TUGAS 2</h3>
<h3 align="center">MODUL 7 & 8</h3>

<br>
<p align="center">
  <img src="screenshots/logo telkom university.png" width="150"/>
</p>
<br>

<p align="center">
Disusun oleh:
<br><br>
D’SHARLENDITA FEBIANDA AURELIA  
<br>
2311102069  
<br>
S1 IF-11-04  
</p>

<br>

<p align="center">
Dosen Pengampu:
<br>
Cahyo Prihantoro, S.Kom., M.Eng  
</p>

<br><br>

<p align="center">
PROGRAM STUDI S1 INFORMATIKA  
<br>
FAKULTAS INFORMATIKA  
<br>
TELKOM UNIVERSITY PURWOKERTO  
<br>
2026  
</p>

---

# DASAR TEORI

## 1. NodeJS
NodeJS merupakan sebuah runtime environment yang digunakan untuk menjalankan JavaScript di sisi server. NodeJS dibangun menggunakan engine V8 dari Google Chrome, sehingga mampu mengeksekusi kode JavaScript dengan cepat dan efisien.

NodeJS menggunakan konsep non-blocking I/O dan event-driven, yang memungkinkan server menangani banyak request secara bersamaan tanpa harus menunggu proses sebelumnya selesai. Hal ini membuat NodeJS sangat cocok digunakan untuk pengembangan aplikasi web yang membutuhkan performa tinggi.

Dalam aplikasi ini, NodeJS digunakan sebagai backend untuk menangani proses CRUD serta komunikasi antara frontend dan penyimpanan data dalam format JSON.

Sumber:
Node.js Foundation (https://nodejs.org)  
Tilkov, S., & Vinoski, S. (2010). Node.js: Using JavaScript to Build High-Performance Network Programs.

---

## 2. JSON (JavaScript Object Notation)
JSON (JavaScript Object Notation) adalah format pertukaran data yang ringan dan mudah dibaca oleh manusia serta mudah diproses oleh mesin. JSON menggunakan struktur pasangan key dan value untuk merepresentasikan data.

JSON banyak digunakan dalam aplikasi web modern sebagai media pertukaran data antara client dan server karena formatnya yang sederhana dan fleksibel.

Pada aplikasi ini, JSON digunakan sebagai media penyimpanan data mahasiswa sehingga data dapat dengan mudah diakses, diubah, dan ditampilkan kembali.

Sumber:
ECMA International – ECMA-404 JSON Standard  
Crockford, D. (2006). The application/json Media Type for JavaScript Object Notation (JSON).

---

## 3. JQUERY
jQuery merupakan library JavaScript yang dirancang untuk mempermudah manipulasi DOM, penanganan event, serta interaksi dengan server menggunakan AJAX.

Dengan jQuery, penulisan kode JavaScript menjadi lebih sederhana dan efisien dibandingkan menggunakan JavaScript murni. jQuery juga mendukung berbagai browser sehingga memudahkan pengembangan aplikasi web yang kompatibel.

Dalam aplikasi ini, jQuery digunakan untuk mengatur event, mengambil data input, serta berkomunikasi dengan server menggunakan AJAX.

Sumber:
jQuery Foundation (https://jquery.com)  
Resig, J. (2006). jQuery Library Documentation.

---

## 4. PLUGIN JQUERY (DATA TABLES)
Plugin jQuery adalah ekstensi tambahan yang digunakan untuk menambah fitur tertentu pada jQuery. Salah satu plugin yang populer adalah DataTables.

DataTables merupakan plugin jQuery yang digunakan untuk menampilkan data dalam bentuk tabel interaktif yang mendukung fitur pencarian, pengurutan (sorting), dan pagination.

Dalam aplikasi ini, DataTables digunakan untuk menampilkan data mahasiswa agar lebih mudah dibaca dan dikelola oleh pengguna.

Sumber:
DataTables jQuery Plugin (https://datatables.net)  
SpryMedia Ltd. (DataTables Documentation)

---

## 5. CRUD (CREATE, READ, UPDATE, DELETE)
CRUD merupakan konsep dasar dalam pengolahan data yang terdiri dari empat operasi utama, yaitu:
- Create (menambahkan data)
- Read (menampilkan data)
- Update (memperbarui data)
- Delete (menghapus data)

Konsep CRUD digunakan dalam hampir semua aplikasi berbasis database atau sistem informasi untuk mengelola data.

Pada aplikasi ini, seluruh fitur yang dibuat mengacu pada konsep CRUD untuk mengelola data mahasiswa.

Sumber:
Database Systems – Connolly & Begg (2015), Database Systems: A Practical Approach  
Elmasri, R., & Navathe, S. (2016). Fundamentals of Database Systems.

---

## 6. BOOTSTRAP
Bootstrap merupakan framework CSS yang digunakan untuk mempermudah pembuatan tampilan web yang responsif dan menarik. Bootstrap menyediakan berbagai komponen siap pakai seperti grid system, form, tombol, dan navigasi.

Dengan menggunakan Bootstrap, pengembang dapat membuat tampilan website yang konsisten dan dapat menyesuaikan dengan berbagai ukuran layar, baik desktop maupun mobile.

Dalam aplikasi ini, Bootstrap digunakan untuk membangun tampilan halaman form, tabel, dan halaman edit agar lebih rapi dan user-friendly.

Sumber:
Bootstrap Team (https://getbootstrap.com)  
Otto, M., & Thornton, J. (2011). Bootstrap Documentation.

---

# STRUKTUR FOLDER


## Screenshot

### Halaman Form
![Form](screenshots/form.png)

### Halaman Data
![Data](screenshots/tabel.png)

### Halaman Edit
![Edit](screenshots/edit.png)
