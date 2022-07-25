1. membuat sebuah folder kosong dengan nama-mu sendiri (mkdir Jaki)
2. didalam *folder* tersebut buatlah 
    - *folder* `sekolah` (mkdir sekolah)
    - *folder* `kerja` (mkdir kerja)
3. masuk ke dalam folder `sekolah` (cd sekolah)
    - buat *file* dengan nama `ijazah.txt`, yang mana file tersebut akan memiliki teks seperti: (touch ijazah.txt)

        ```jsx
        Perkenalkan namaku $NAMA

        Aku berasal dari $DAERAH

        Salam Kenal :D
        ```

    - tampilkan isi dari *file* tersebut menggunakan `CLI command` (cat ijazah.txt)
    - kemudian buat 1 file lagi dengan nama `portfolio.txt`, yang mana file tersebut akan memiliki teks seperti: (touch portofolio.txt)

        ```jsx
        Saya pernah bekerja pada beberapa perusahaan salah satu 
        diantaranya ialah

        - $PERUSAHAAN
        - $PERUSAHAAN
        - $PERUSAHAAN
        ```

4. keluar dari *folder* sekolah (cd ..)
5. masuk kedalam *folder* `kerja` (cd kerja)
    - buat *file* dengan nama `cv.txt`, yang mana hal tersebut akan memiliki teks seperti: (touch cv.txt)

        ```jsx
        Salam,

        Perkenalkan namaku $NAMA, saya memiliki kegemaran
        - $HOBBY
        - $HOBBY
        - $HOBBY
        ```

    - tampilkan isi dari *file* tersebut menggunakan `CLI command` (cat cv.txt)
6. Pada tahap ini kamu lupa jika sebenarnya *file* `portfolio.txt` serahusnya tidak berada pada *folder* `sekolah`, jadi kamu harus **memindahkannya** ke dalam folder `kerja` (mv portofolio.txt ../kerja)
