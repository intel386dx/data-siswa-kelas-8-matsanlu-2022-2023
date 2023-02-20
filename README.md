Data Siswa Kelas 8 MTsN 1 Lumajang
==================================

## Indonesian (Indonesia) [id-ID]

Ini adalah berkas basis data SQLite berisi seluruh data siswa kelas 8 MTsN 1 Lumajang 
pada tahun 2022/2023.

Untuk melihat berkas ini, berasumsikan bahwa Anda menggunakan Windows:
1. [Unduh perangkat lunak SQLite3](https://www.sqlite.org/2022/sqlite-tools-win32-x86-3400100.zip) dan ekstrak berkas ``sqlite3.exe`` ke dalam sebuah folder.
2. Unduh berkas ``kelas_8.db`` dan simpan di suatu tempat, misalnya di _My Documents_.
3. Di folder tempat Anda mengekstrak ``sqlite3``, tahan Shift lalu klik kanan ruang kosong. Pilih _Show more options..._ jika Anda memakai Windows 11, lalu pilih _Open command window here_ atau _Open PowerShell window here_.
4. Jendela terminal akan terbuka. Ketikkan ``sqlite3 -table `` diikuti dengan jalur dimana berkas kelas_8.db terletak, lalu tekan Enter. Contoh:
```
sqlite3 -table [jalur berkas kelas_8.db]
```

5. Di terminal sqlite3, ketikkan kalimat dibawah ini dan tekan Enter. Tanda bintang (*) dibawah ini bisa diganti dengan nama-nama kolom yang akan dicetak yang dipisah koma.
```
SELECT * FROM kelas_8;
```

6. Tabel akan segera dicetak pada terminal.

Integritas berkas dapat dipastikan dengan kode hash SHA-3 berikut:
```
42af3142893be36c68d7ce168edd7a4e71193c2ae391ee603d38dd28
```

## English (United States) [en-US]

This is an SQLite database file containing all grade 8 student data of MTsN 1 Lumajang
in 2022/2023.

To view this file, assuming that you're using Windows:
1. [Download the SQLite3 software](https://www.sqlite.org/2022/sqlite-tools-win32-x86-3400100.zip) and extract the ``sqlite3.exe`` file into a folder.
2. Download the ``kelas_8.db`` file and store at a place, e.g. _My Documents_.
3. At a folder where you extracted ``sqlite3.exe``, hold Shift and right-click an empty space. Select _Show more options..._ if you're using Windows 11, then select _Open command window here_ or _Open PowerShell window here_.
4. A terminal window will open. Type ``sqlite3 -table `` followed by a path where the ``kelas_8.db`` at, then press Enter. Example:
```
sqlite3 -table [path to the file kelas_8.db]
```

5. At the sqlite4 terminal, type the sentence below and press Enter. The asterisk (*) can be substituted with comma-separated column names that are going to be printed.
```
SELECT * from kelas_8;
```

5. The table will be printed on the terminal soon.

The integrity of the file can be verified with the following SHA-3 hash code:
```
42af3142893be36c68d7ce168edd7a4e71193c2ae391ee603d38dd28
```

