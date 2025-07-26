# **Pengenalan Python & Tools**

## 🎯 Tujuan Pembelajaran:

Setelah mengikuti modul ini, diharapkan mampu:

*   Menjelaskan sejarah dan manfaat bahasa Python.
*   Mengetahui alasan mengapa Python populer.
*   Memahami perbedaan antara interpreter dan compiler.
*   Menginstal dan menggunakan tools pendukung Python seperti:

    *   Python Interpreter
    *   Code Editor (VS Code / Jupyter Notebook/ Google Colab)
    *   Terminal/Command Prompt
    *   Menulis dan menjalankan program Python sederhana.

# 1.   Apa itu python?

  Python adalah bahasa pemrograman tingkat tinggi yang dirancang dengan fokus pada keterbacaan kode dan kemudahan penulisan. Diciptakan oleh Guido van Rossum dan dirilis pertama kali pada tahun 1991, Python kini menjadi salah satu bahasa pemrograman paling populer di dunia. Python bersifat open-source, artinya siapa saja dapat menggunakannya secara gratis dan berkontribusi dalam pengembangannya. Bahasa ini mendukung berbagai paradigma pemrograman, termasuk pemrograman berorientasi objek, fungsional, dan imperatif. Salah satu keunggulan Python terletak pada sintaksnya yang sederhana dan mirip dengan bahasa manusia, sehingga cocok bagi pemula maupun profesional. Python digunakan secara luas di berbagai bidang, mulai dari pengembangan web, automasi, pengolahan data, kecerdasan buatan (AI), hingga Internet of Things (IoT). Kombinasi antara fleksibilitas, komunitas yang besar, serta dukungan pustaka yang sangat lengkap menjadikan Python pilihan utama dalam dunia pemrograman saat ini.

# 2.  Instalasi python

Python sendiri bisa di install baik windows, macOS maupun Linux. Tetapi pada modul kali ini kita akan melakukan proses instalasi pada windows.


*   Masuk ke browsure dan buka situs resmi python: https://www.python.org
*   Klik download dan pilih menu download for windows, pilih python versi terbaru ( di sesuaikan lagi dengan kapasitas PC nya).
* Setelah selesai jalankan proses instalasi seperti biasa: https://www.youtube.com/watch?v=U6POiWZnGFs (tutorial instal)
* Melakukan verifikasi atau pengecakan ulang apakah python sudah terinstal di CMD dengan memasukan beberapa code berikut:




```python
python --version
# Jika outputnya sesuai dengan versi terbaru python yaitu 3.13.5 maka instalasi berhasil
```

# 3.  Install editor yang akan di gunakan

Ada beberapa editor yang sering di gunakan dalam pengoperasian python seperti VS Code, Google colab, Jupyter Notebook


*   Google Collab editor yang paling gampang di gunakan karna bawaan google:
    * Search Google colab
 
      ![colab](Pengenalan%20Python%20dan%20Tools/colab.png)

    * Notebook baru

*  VS Code
   * Kunjungi situs: https://code.visualstudio.com
   * Klik Download for Windows.
   * Jalankan installer dan ikuti petunjuk instalasi (Saat instalasi, centang opsi "Add to PATH" dan "Install code command" jika muncul).
   * Setelah selesai buka VS Code, klik menu Extensions (ikon kotak di sidebar kiri atau tekan Ctrl + Shift + X)

      ![vscode](Pengenalan%20Python%20dan%20Tools/vscode.png)
  
   * Cari “Python” dari Microsoft → klik Install (Extension ini memungkinkan kamu menjalankan file .py langsung dari editor).
   * jika ingin membua file baru pada VS Code bisa melalui folder di pc masing" atau langsung saja melalui VS Code dengan klik pada menu file di side bar atas pojok kiri dan pilih New File, lalu simpan file dengan format py atau ipynb ( rilla_cantik.py / rilla_cantik.ipynb)


# 4. Pengoperasian Python



*   Buka VS Code atau Google Collab yang telah di intall tadi, jika menggunakan VS Code ikuti tahap nomor 3 di mana harus buat file terlebih dahulu dengan menggunakan format py, jika menggunakan collab berarti langsung saja di jalankan.
*   Jalankan code dasar berikut



```python
print("Hello, World!")
# outputnya berupa Hello, World
```



*   Jika di jalankan di Goggle collab, ketik codenya dan jalan kan perintah di tombol panah run yang terletak di samping sel terminalnya:

    ![hello](Pengenalan%20Python%20dan%20Tools/hello.png)

*   Jika menggunakan VS Code tombol runnya terletak di sebelah kanan:

    ![vscodepanah](Pengenalan%20Python%20dan%20Tools/vscodepanah.png)

Fungsi print sendiri merupakan fungsi bawaan python yang di gunakan untuk menampilkan output ke layar, di mana outputnya adalah Hello World, tanda kurung () biasa di gunakan untuk memanggil fungsi jadi apapun yang ada di dalam kurung akan di kirim sebagai argumen dalam fungs print, dan untuk tanda kutip sendiri tergantung tipe data yang di gunakan karena pada contoh kali ini menggunakan data tipe string makannya menggunakan tanda kutip yang menunjukan bahwa data tersebut adalah data teks.


```python
#Beberapa code yang bisa di gunakan sebagai uji coba( ketik manual jangan copy paste)

print("Selamat datang di dunia Python!")
```

```python
print(" Nama saya ( bebas isi siapa )")
```

```python
print(" Nama saya rilla")
```

```python
nama = "Andi"
umur = 20
print("Nama saya:", nama)
print("Umur saya:", umur)

```

# Latihan Pemahaman

1. Buat variabel untuk menyimpan data berikut:

  * Nama
  * Kelas
  * Jurusan

  Lalu tampilkan semua data menggunakan print(), contoh output:

  ![tugas](Pengenalan%20Python%20dan%20Tools/tugas.png)
