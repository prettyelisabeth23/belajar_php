# Associative Array PHP

## Deskripsi

Program ini merupakan contoh penggunaan **Associative Array pada PHP** untuk menyimpan dan menampilkan data nilai mahasiswa berdasarkan nama mata kuliah. Associative array adalah array yang menggunakan **key** sebagai indeks berupa nama atau teks, sehingga data dapat diakses berdasarkan key tersebut.

## Penjelasan Program

Program membuat dua associative array, yaitu `$mahasiswa_satu` dan `$mahasiswa_dua`. Array `$mahasiswa_satu` dibuat menggunakan fungsi `array()`, sedangkan `$mahasiswa_dua` dibuat dengan cara memasukkan setiap pasangan key dan value secara langsung. Nama mata kuliah seperti **Matematika, Fisika, PABI, English, dan Sisop** digunakan sebagai key, sedangkan nilai **95, 90, 96, 93, dan 98** digunakan sebagai value.

Selanjutnya, program menggunakan `echo` untuk menampilkan nilai mata kuliah ke layar. Data diakses menggunakan key, contohnya `$mahasiswa_dua["Matematika"]` digunakan untuk mengambil nilai Matematika. Operator titik (`.`) digunakan untuk menggabungkan teks dengan nilai array, sedangkan `\n` digunakan untuk membuat baris baru.

Program ini dibuat untuk memahami konsep dasar **pembuatan, penyimpanan, pengaksesan, dan penampilan data menggunakan Associative Array dalam PHP**.

## Konsep yang Digunakan

* **PHP** – Bahasa pemrograman yang digunakan.
* **Associative Array** – Menyimpan data menggunakan pasangan `key => value`.
* **Array Access** – Mengakses data berdasarkan key.
* **`echo`** – Menampilkan data ke layar.
* **Concatenation (`.`)** – Menggabungkan teks dengan nilai.
* **New Line (`\n`)** – Membuat baris baru pada output.

## Contoh Output

```text
Marks for mahasiswa satu is:
Matematika: 95
Fisika: 90
PABI: 96
English: 93
Sisop: 98
```

## Kesimpulan

Program ini menunjukkan dua cara membuat associative array pada PHP serta cara mengakses dan menampilkan data berdasarkan key. Dengan menggunakan associative array, data nilai mata kuliah dapat disimpan dan diakses dengan lebih terstruktur dan mudah dipahami.
