# Tugas LAB 3 Web
## Profil
| # | Biodata |
| -------- | --- |
| *Nama* | Muhammad rizky abdillah |
| *NIM* | 312010368 |
| *Kelas* | TI.20.A.2 |
| *Mata Kuliah* | Pemrograman Web |
## 1. Membuat Dokumen LIST
* Buka VS Code dan buat file HTML baru. Setelah itu buat struktur HTML 

```
    <section id="order-list">
        <h2>Ordered List</h2>
        <ol>
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Basis Data 2</li>
        </ol>
        </section>
        <section id="unorder-list">
            <h2>Unordered List</h2>
            <ul type="square">
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma &amp; Pemrograman</li>
            </ul>
            </section>
            <section id="unorder-list">
                <h2>Description List</h2>
                <dl>
                <dt>Fakultas Teknik</dt>
                <dd>Teknik Industri</dd>
                <dd>Teknik Informatika</dd>
                <dd>Teknik Lingkungan</dd>
                <dt>Fakultas Ekonomi dan Bisnis</dt>
                <dd>Akuntansi</dd>
                <dd>Manajemen</dd>
                <dd>Bisnis Digital</dd>
                </dl>
                </section>
```

* Maka hasilnya akan seperti berikut.
![struktur](list.png)
## 2. Membuat Tabel Sederhana
* kemudian Membuat Tabel Sederhana
<!-- Ini adalah paragraf pertama -->
```
    <table border="1" cellpadding="6" cellspacing="0">
    <thead>
    <tr>
    <th>No.</th>
    <th>Fakultas</th>
    <th>Program Studi</th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td>1.</td>
    <td>Teknik</td>
    <td>Teknik Informatika</td>
    </tr>
    <tr>
    <td>2.</td>
    <td>Teknik</td>
    <td>Teknik Industri</td>
    </tr>
    <tr>
    <td>3.</td>
    <td>Teknik</td>
    <td>Teknik Lingkungan</td>
    </tr>
    </tbody>
    </table>
```

* model tabel pemrograman web Maka hasilnya akan seperti berikut.
![internal](tabel.png)
* menambahkan border
```
 <table border="1" cellpadding="6" cellspacing="0">
```

## 3. Membuat Tabel Form
* selanjutnya membuat tabel form dengan Html Lanjutan 
```
<form action="proses.php" method="post">
    <fieldset>
    <legend>Data Pelanggan</legend>
    <p>
    <label for="nama">Nama</label>
    <input type="text" id="nama" name="nama">
    </p>
    <p>
    <label for="alamat">Alamat</label>
    <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
    <p>
    <label>Jenis Kelamin</label>
    <input id="jk_l" type="radio" name="kelamin" value="L" /><label
    for="jk_l">Laki-laki</label>
    <input id="jk_p" type="radio" name="kelamin" value="P" /><label
    for="jk_p">Perempuan</label>
</p>
<p><input type="submit" value="Login"></p>
</fieldset>
</form>
```
* model tabel pemrograman web Maka hasilnya akan seperti berikut.
![internal](form.png)
