[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/X0GmrgC2)
# **Live Code 2**
---
## **Instruction**

1. Live Code ini dikerjakan dalam format ***notebook*** isi *notebook* harus mengikuti *outline* di bawah ini:
    * Perkenalan\
    Bab pengenalan harus diisi dengan identitas (Nama dan Batch)
    * *Answer*\
    Bagian ini berisi proses dalam menjawab soal, tiap nomor soal dikerjakan dalam satu cell masing-masing dan berikan judul soal dengan markdown sebelum cell code.

2. Notebook **wajib** memberikan keterangan atau pengenalan dengan menggunakan **`markdown`** yang berisikan Judul tugas, Nama, Batch, dan penjelasan singkat tentang program yang dibuat. *Contoh:*
    ```
    
    =================================================
    Live Code 2

    Nama  : Fahmi Iman Alfarizki
    Batch : CODA-RMT-001

    Program ini dibuat untuk melakukan automatisasi pengolahan (cleaning) data text yang berguna untuk pemodelan model analisa sentimen.
    =================================================
    
    ``` 

3. Tiap function diberikan penjelasan mengenai untuk apa class/method ini dan bagaimana alur algoritmanya dengan `docstring`

  ```py
  #Contoh:

  def f(x):
    '''
    Fungsi ini ditujukan untuk menghitung kuadrat angka yang dimasukkan pengguna dengan rumus x^2.

    Argument x merupakan inputan angka berupa bilangan real.

    Contoh penggunaan:
      y = f(2)
      print(y)
      --------
      Output: 4
    '''
    return x**2

  ```
  Berikan juga keterangan/penjelasan umum tentang code yang tertulis pada suatu cell di tiap cellnya (tulis di baris paling atas dengan `comment` atau `docstring`.

4. **WARNING**: Plagiarisme sekecil apapun dapat terdeteksi. Tugas ini akan diuji tingkat plagiarismenya dengan software khusus.
---
## **Assignment Submission**

- Simpan assignment pada sesi ini dengan nama `coda_P0LC2_<nama-student>.ipynb`, misal `coda_P0LC2_raka_ardhi.ipynb`.
- Push Assigment yang telah kalian buat ke repository Github Classroom masing-masing student.
---
## **Assignment Objectives**

*Live Code 2* ini dibuat guna mengevaluasi Python sebagai berikut:

- Mampu menggunakan syntax dasar Python.
- Mampu menerapkan logika conditional pada kasus.
- Mampu menerapkan logika looping pada kasus.
- Mampu menerapkan function pada kasus.
---

## **Assignment Instructions and Cases**

Sebuah perusahaan memiliki berbagai jenis karyawan dengan tingkat gaji yang berbeda. Mereka ingin menghitung penghasilan bulanan karyawan berdasarkan jam kerja dan jenis pekerjaan. Bantulah perusahaan ini dengan membuat program Python dan fungsi-fungsi berikut:

1. Buatlah fungsi `hitung_penghasilan` yang dapat menghitung penghasilan bulanan karyawan berdasarkan tingkat gaji dan ketentuan berikut:
   - Manager: Rp. 10,000,000. per bulan
   - Staff: Rp. 5,000,000. per bulan
   - Kasir: Rp. 4,000,000. per bulan
   - Selain gaji tetap, karyawan juga akan menerima gaji lembur sebesar Rp. 20,000 per jam untuk setiap jam kerja di atas 40 jam per minggu.
(Hint: buat dictionary untuk menyimpan informasi gaji berdasarkan tingkatan karyawan, lalu periksa apakah jam kerja lebih dari 40 jam perminggu atau tidak, jika iya hitung uang lembur)

   Contoh input dan output fungsi `total_pengeluaran`:
   ```py
   >>> [In]: hitung_penghasilan("Staff", 42)

   >>> [Out]: 5040000

2. Buatlah fungsi `total_pengeluaran` yang menerima daftar karyawan beserta jumlah jam kerja mereka per minggu. Fungsi ini harus mengembalikan total pengeluaran bulanan perusahaan untuk membayar semua karyawan. (Hint: Gunakan for loop untuk menjawab pertanyaan ini. Hitung tiap data yang ada di daftar karyawan dengan memanfaatkan fungsi hitung_penghasilan).

   Contoh input dan output fungsi `total_pengeluaran`:
   ```py
   >>> [In]: daftar_karyawan = [
             {'tingkat': 'Manager', 'jam_kerja': 45},
             {'tingkat': 'Staff', 'jam_kerja': 42},
             {'tingkat': 'Kasir', 'jam_kerja': 38},
             {'tingkat': 'Staff', 'jam_kerja': 50}
            ]

            total_pengeluaran(daftar_karyawan)

   >>> [Out]: 24340000
---
## **Assignment Rubrics**

---

|Rubric|Description|Score|
|---|---|---|
|Looping|Siswa mampu menerapkan looping sesuai dengan instruksi pada soal|5 pts|
|Conditional If|Mampu menerapkan conditional if dalam suatu kasus|5 pts|
|Function|Siswa mampu menerapkan function dalam suatu kasus|5 pts|
|Run Perfectly|Tidak ada error pada kode|5 pts|
|Readability|Semua cell di notebook terdokumentasikan dengan baik dengan markdown pada tiap cell untuk penjelasan kode|5 pts|

Total Points : 25
