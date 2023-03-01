Data Siswa Kelas 8 MTsN 1 Lumajang
==================================

## Indonesian (Indonesia) [id-ID]

Ini adalah berkas basis data SQLite berisi seluruh data siswa kelas 8 MTsN 1 Lumajang 
pada tahun 2022/2023.

Untuk melihat berkas ini, berasumsikan bahwa Anda menggunakan Windows:
1. [Unduh perangkat lunak SQLite3](https://www.sqlite.org/2022/sqlite-tools-win32-x86-3400100.zip) dan ekstrak berkas ``sqlite3.exe`` ke dalam sebuah folder.
2. Unduh berkas ``kelas_8.dat`` dan simpan di suatu tempat, misalnya di _My Documents_.
3. Di folder tempat Anda mengekstrak ``sqlite3``, tahan Shift lalu klik kanan ruang kosong. Pilih _Show more options..._ jika Anda memakai Windows 11, lalu pilih _Open command window here_ atau _Open PowerShell window here_.
4. Jendela terminal akan terbuka. Ketikkan ``.\sqlite3 -table `` diikuti dengan jalur dimana berkas kelas_8.dat terletak, dan pernyataan SQL ini: ``SELECT * from kelas_8;`` lalu tekan Enter. Contohnya, jika Anda menyimpan berkasnya kedalam _drive_ ``D:``, ketikkan:
```
.\sqlite3 -table D:\kelas_8.dat "SELECT * from kelas_8;"
```

5. Tabel akan segera dicetak pada terminal. Anda juga bisa menambahkan tanda lebih-dari, diikuti dengan nama berkas untuk menyimpan tabel yang dicetak. Contohnya, untuk menyimpan tabel yang dicetak kedalam sebuah berkas bernama "tabel.txt" pada _drive_ ``D:``, ketikkan seperti ini:
```
.\sqlite3 -table d:/kelas_8.dat "SELECT * from kelas_8;" > D:\tabel.txt
```

Bila Anda sedang di Linux atau Termux:
1. Pertama-tama perbarui daftar paket dengan mengetik:
```
sudo apt update
```
2. Sekarang unduh dan pasang SQLite dengan mengetikkan perintah dibawah. Sebuah paket terkompres yang akan diunduh hanya sekitar 1 megabyte, jadi kuota data Anda tidak terkuras habis.
```
sudo apt install sqlite
```
3. [Unduh berkas database](https://raw.githubusercontent.com/intel386dx/data-siswa-kelas-8-matsanlu-2022-2023/main/kelas_8.dat) dengan mengetik:
```
curl https://raw.githubusercontent.com/intel386dx/data-siswa-kelas-8-matsanlu-2022-2023/main/kelas_8.dat -o kelas_8.dat
```
4. Sekarang ketikkan perintah ini untuk mencetak database dalam bentuk tabel ke terminal.
```
.\sqlite3 -table d:/kelas_8.dat "SELECT * from kelas_8;"
```

5. Tabel akan segera dicetak pada terminal. Anda juga bisa menambahkan tanda lebih-dari, diikuti dengan nama berkas untuk menyimpan tabel yang dicetak. Contohnya, untuk menyimpan tabel yang dicetak kedalam sebuah berkas bernama "tabel.txt" pada _drive_ ``D:``, ketikkan seperti ini:
```
.\sqlite3 -table d:/kelas_8.dat "SELECT * from kelas_8;" > D:\tabel.txt
```
>
> **Catatan:** Anda dapat menghilangkan perintah ``sudo`` di Termux karena tidak memerlukan _superuser_ untuk memperbarui dan memasang paket.
>

Integritas berkas dapat dipastikan dengan kode hash SHA-3 berikut:
```
42af3142893be36c68d7ce168edd7a4e71193c2ae391ee603d38dd28
```

## English (United States) [en-US]

This is an SQLite database file containing all grade 8 student data of MTsN 1 Lumajang
in 2022/2023.

To view this file, assuming that you're using Windows:
1. [Download the SQLite3 software](https://www.sqlite.org/2022/sqlite-tools-win32-x86-3400100.zip) and extract the ``sqlite3.exe`` file into a folder.
2. Download the ``kelas_8.dat`` file and store at a place, e.g. _My Documents_ or the ``D:`` drive.
3. At a folder where you extracted ``sqlite3.exe``, hold Shift and right-click an empty space. Select _Show more options..._ if you're using Windows 11, then select _Open command window here_ or _Open PowerShell window here_.
4. A terminal window will open. Type ``.\sqlite3 -table `` followed by a path where the ``kelas_8.dat`` at, and this SQL statement: ``SELECT * from kelas_8;``, then press Enter. For example, if you place the file at the ``D:`` drive, type:
```
.\sqlite3 -table d:/kelas_8.dat "SELECT * from kelas_8;"
```

5. The table will be printed on the terminal soon. You can append a greater-than sign, followed by a file name to save the printed table. For example, to save the printed table to a file named "table.txt" at the drive ``D:``, type like this:
```
.\sqlite3 -table d:/kelas_8.dat "SELECT * from kelas_8;" > D:\table.txt
```

If you're on Linux or Termux:
1. First update the package list by typing this command:
```
sudo apt update
```
2. Now download and install SQLite by typing the command below. It downloads a small, compressed package that is about 1 megabytes, so it won't break your data plan.
```
sudo apt install sqlite
```
3. [Download the database file](https://raw.githubusercontent.com/intel386dx/data-siswa-kelas-8-matsanlu-2022-2023/main/kelas_8.dat) by typing:
```
curl https://raw.githubusercontent.com/intel386dx/data-siswa-kelas-8-matsanlu-2022-2023/main/kelas_8.dat -o kelas_8.dat
```
4. Now type this command to print the database as a tabular data onto the terminal.
```
.\sqlite3 -table d:/kelas_8.dat "SELECT * from kelas_8;"
```

5. The table will be printed on the terminal soon. You can append a greater-than sign, followed by a file name to save the printed table. For example, to save the printed table to a file named "table.txt" at the drive ``D:``, type like this:
```
.\sqlite3 -table d:/kelas_8.dat "SELECT * from kelas_8;" > D:\table.txt
```
>
> **Note:** You can omit the ``sudo`` command in Termux because it doesn't need a superuser account to update and install packages.
>

The file integrity can be verified with the following SHA-3 hash code:
```
42af3142893be36c68d7ce168edd7a4e71193c2ae391ee603d38dd28
```

