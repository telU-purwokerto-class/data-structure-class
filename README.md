---
layout: default
permalink: /
---

# Silabus Struktur Data

***Bila Anda guru/dosen atau tertarik dengan desain mata kuliah ini, silakan lihat dokumen [meta](https://struktur-data.github.io/syllabus/meta).***

* **Mata Kuliah:** [Struktur Data](http://bit.telkomuniversity.ac.id/?page_id=242)
* **Dosen:** Yudha Islami Sulistya <[yudhaislami@telkomuniversity.ac.id](mailto:yudhaislami@telkomuniversity.ac.id)>
* **SKS:** 3 SKS kuliah + 1 SKS praktikum
   * 14 minggu, masing-masing:
      * Kelas: 3 x 50 menit
      * Praktikum: 100 menit (10 minggu)
      * Tugas: 1 x 50 menit
* **Butuh bantuan?**
   * Lihat [issues](https://github.com/struktur-data/syllabus/issues) yang ada atau buat _issue_ baru
   * Email [yudhaislami@telkomuniversity.ac.id](mailto:yudhaislami@telkomuniversity.ac.id) untuk diskusi/konsultasi atau bertemu langsung

## Deskripsi Mata Kuliah

Pada mata kuliah ini diajarkan berbagai macam struktur data yang dapat diimplementasikan dalam program komputer, serta bagaimana memilih struktur data yang tepat untuk suatu kasus tertentu. Materi yang diajarkan meliputi:

1. Abstract Data Type (ADT);
2. representasi struktur data linier dan primitif-primitifnya (_array_, _linked list_, variasi _linked list_, _stack_, _queue_);
3. representasi struktur data non-linier dan primitif-primitifnya (_tree_, _graph_, _multilist_); dan
4. algoritma penelusuran (_preorder_, _inorder_, _postorder_) dan pencarian (BFS, DFS).

## Capaian Pembelajaran

1.	CLO1: Mahasiswa mampu membangun algoritma untuk primitif struktur data Linked List dan mengimplementasikannya dalam Bahasa Pemrograman.
2.	CLO2: Mahasiswa mampu membangun algoritma untuk primitif struktur data Stack dan Queue, serta mengimplementasikannya dalam Bahasa Pemrograman.
3.	CLO3: Mahasiswa mampu membangun algoritma untuk primitif struktur data non-linear Linked List, Graph dan Tree, serta mengimplementasikannya dalam Bahasa Pemrograman

## Prasyarat

* Matakuliah syarat: Dasar Algoritma dan Pemrograman ([CCH1A4](http://dedetarwidi.staff.telkomuniversity.ac.id/lectures/dasar-algoritma-dan-pemrograman/)).
* Pemahaman variabel, tipe data, alur kendali, dan penggunaan fungsi dasar di C++
* Memahami cara menggunakan fitur-fitur _debugging_: Debug / Continue, Run to cursor, Step over, Step into, Step out, Breakpoint, Local variables

Bila penguasaan Anda dirasa kurang untuk konsep-konsep tersebut, disarankan untuk mereview kembali. Materi-materi prasyarat dapat dilihat di bagian [Materi Pemula](#materi-pemula).

Spesifikasi komputer:

* Komputer dengan OS Windows 7 ke atas, 32-bit/64-bit, RAM minimal 2 GB

   Anda juga dapat menggunakan macOS maupun Linux, namun perlu penyesuaian _tools_ yang digunakan.

Penguasaan _tools_ berikut sangat disarankan:

* Git dan GitHub. Pengenalan Git dan GitHub akan dilakukan saat sesi kuliah. Silakan lihat bagian [GitHub](#github) untuk rujukan lebih lanjut.

## Bahan Kajian / Pokok Bahasan

Adapun bahan kajian atau pokok bahasannya adalah:

* Linear Linked List (termasuk Stack dan Queue)
* Circular Linked List
* Double Linked List
* Non Linear Linked List (termasuk Tree dan Graph)

Kajian akan didemonstrasikan menggunakan contoh live-code maupun slides yang tersedia di (TODO). Latihan lebih lanjut akan dikerjakan dalam praktikum.

## Tugas

Semua tugas dapat dilihat di bagian [Kerangka Mata Kuliah](#kerangka-mata-kuliah).

### Workflow

Bila Anda menggunakan GitHub Desktop, panduan umum berikut dapat membantu Anda:

* <https://guides.github.com/activities/forking/>
* <https://help.github.com/desktop/guides/contributing/>

Disarankan untuk menyalakan `Edit`->`Automatically Sync after Committing`. Langkah-langkahnya sebagai berikut:

1. Lakukan _Fork_ pada _repository_ tugas yang Anda inginkan (daftar _repository_ dapat dilihat di [github.com/struktur-data](https://github.com/struktur-data)).
1. _Clone repository_ tersebut ke komputer Anda.
1. Buka file utama (`*.cpp`) menggunakan Code::Blocks.
1. Ubah program untuk menyelesaikan solusi Anda.
1. Jalankan program maupun gunakan fungsi _debugging_. Ulangi hingga sesuai harapan Anda.
1. Pastikan semua kode Anda sudah di- _commit_.
1. _Push/sync_ ke GitHub.
1. [Buat _pull request_](https://help.github.com/articles/creating-a-pull-request/) pada _repository_ induk. Setiap tugas memiliki jadwal _deadline_ yang sudah ditentukan.
1. Anda tetap dapat mengirim perbaikan dan penyempurnaan sampai waktu pengirim tugas ditutup - silakan tambahkan komentar pada _pull request_ untuk memberitahu bahwa Anda telah memperbaruinya.

Saat _pull request_ dibuat, Anda akan menerima pesan bahwa "the Travis CI build is in progress" – ini berarti solusi Anda sedang diperiksa secara otomatis untuk kesalahan sintaks/kompilasi. Bila "build" gagal (menampilkan icon "X" merah), klik pranala "details" dan _scroll_ ke bagian bawah untuk melihat apa saja kesalahannya. Sesuai dengan [Ketentuan](#ketentuan) di bawah, silakan memperbaiki kesalahan dan kirimkan perubahan Anda.

Tanggapan akan diberikan pada _pull request_ Anda, jadi silakan ya membalas dengan uneg-uneg dan pertanyaan Anda! Anda dipersilakan untuk mengirimkan _pull request_ lebih awal sebagai "work-in-progress" bila Anda merasa buntu dan ingin menanyakan suatu hal. Perhatikan bahwa solusi Anda juga akan dapat diakses publik di alamat `http://USERNAME.github.io/TUGAS`.

#### Versi

Untuk tugas dengan beberapa Versi (`V1`, `V2`, dll.) yang dicantumkan dalam README: Versi tersebut dapat dijadikan panduan bagaimana mengerjakan tugas-tugas tersebut dalam langkah-langkah kecil. Pastikan Anda telah mencapai Versi tertinggi pada tanggal _deadline_. Lihat juga: [Bonus](#bonus).

### Ketentuan

Ketentuan berikut juga berlaku di dunia nyata, lho.

* [Travis CI](https://docs.travis-ci.com/) _build_ harus berhasil, antara lain:
    * File kode dapat dikompilasi dengan baik (tools yang digunakan adalah CMake 3.2.2 dan GCC).
    * Program dapat dieksekusi.
* Terapkan "good programming style" yang Anda pelajari di kelas
    * Pastikan program mudah dibaca.
        * ["Programs must be written for people to read, and only incidentally for machines to execute." -Harold Abelson](https://www.goodreads.com/quotes/9168-programs-must-be-written-for-people-to-read-and-only)
    * Pedoman lengkap penulisan kode C++ dapat dilihat di [C++ Core Guidelines](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)
* Setiap kode yang Anda ambil dari sumber lain harus Anda cantumkan atribusi, lihat: [Plagiarisme](#plagiarisme).

#### Bonus

Nilai plus akan diberikan untuk:

* Tes otomatis (misalnya menggunakan [Google Test](https://github.com/google/googletest))
* Kreativitas (syarat utama tugas tetap harus terpenuhi)
* Tugas tertentu mencantumkan bagian `BONUS` di file README.

## Kerangka Mata Kuliah

### Minggu ke-1

Sesi ke-1:

1. Pendahuluan
    * Perkenalan dosen
    * Diskusi tentang lingkup mata kuliah ini
    * Perkenalan masing-masing mahasiswa
        * Nama
        * Apa yang Anda "lakukan"?
        * Apa yang ingin Anda raih dalam mata kuliah ini?
        * Hal apa dalam pemrograman/algoritma (atau teknologi apa pun) yang Anda masih khawatir atau merasa kurang?
1. Setup
    * Berapa mahasiswa yang familiar dengan Git/GitHub?
    * Pasang [GitHub Desktop](https://desktop.github.com/)
        * Bila Anda sudah familiar dengan Git, silakan lewati bagian ini.
    * Daftar akun [GitHub](https://github.com/)
1. GitHub workflow
    * Penjelasan [workflow](#workflow)
    * Buat _pull request_ di [students repository](https://github.com/struktur-data/students)
    * Demonstrasi Travis CI
1. TODO: Slide awal: Introduction to Data Structure
1. Penjelasan [ketentuan](#ketentuan)
1. Debugging di Code::Blocks

Sesi ke-2:

1. Materi: Introduction to Data Structure

#### Tugas

1. Bergabung dengan grup WhatsApp. Pranala akan diberikan saat sesi kuliah.
2. [Lengkapi profil GitHub Anda.](https://github.com/settings/profile)
3. Mendaftar paket [GitHub Student Developer Pack](https://education.github.com/pack)
4. Pasang [Code::Blocks](http://www.codeblocks.org/downloads/26)
   * Untuk Windows, gunakan varian **mingw-setup**.
5. TODO: Kerjakan tugas pendahuluan. Batas akhir pengumpulan: sehari sebelum sesi kuliah minggu ke-2.
6. [Implementasi Linear Linked List](https://struktur-data.github.io/syllabus/assignments/linear-linked-list). Batas akhir pengumpulan: Minggu-6 perkuliahan.

### Minggu ke-2

Sesi ke-1:

* Pengertian dan kegunaan Abstract Data Type

Sesi ke-2:

* Pengertian dan kegunaan Abstract Data Type

#### Tugas

* TODO

### Minggu ke-3

Sesi ke-1:

* Pengertian dan kegunaan Pointer

Sesi ke-2:

* Pengertian dan kegunaan Pointer

Praktikum:

* TODO

#### Tugas

* TODO

### Minggu ke-4

Sesi ke-1:

* Pengertian dan Algoritma Linear List

Sesi ke-2:

* Single Linked List
* Implementasi Single Linked List pada bahasa pemrograman C++

Praktikum:

* Implementasi Algoritma Linear List pada bahasa pemrograman C++

#### Tugas

* TODO

### Minggu ke-5

Sesi ke-1:

* Pengertian dan Algoritma Double List

Sesi ke-2:

* Implementasi Algoritma Double List pada bahasa pemrograman C++

Praktikum:

* Implementasi Algoritma Double List pada bahasa pemrograman C++

#### Tugas

* TODO

### Minggu ke-6

Sesi ke-1:

* Pengertian dan Algoritma Circular List
* Implementasi Algoritma Circular List pada bahasa pemrograman C++

Sesi ke-2:

* Implementasi Algoritma Circular List pada suatu kasus

Praktikum:

* Implementasi Algoritma Circular List pada bahasa pemrograman C++
* Implementasi Algoritma Circular List pada suatu kasus

#### Tugas

* TODO

### Minggu ke-7

Sesi ke-1:

* Pengertian dan Algoritma Linked List with Last
* Implementasi Algoritma Linked List with Last pada bahasa pemrograman C++

Sesi ke-2:

* Implementasi Algoritma Linked List with Last pada suatu kasus

Praktikum:

* Implementasi Algoritma Linked List with Last pada bahasa pemrograman C++
* Implementasi Algoritma Linked List with Last pada suatu kasus

#### Tugas

* TODO

### Ujian Tengah Semester (UTS)

Materi ujian:

1. Linear List
2. Double List
3. Circular List

### Minggu ke-8

Sesi ke-1:

* Pengertian dan Algoritma Stack menggunakan Array

Sesi ke-2:

* Implementasi algoritma Stack pada bahasa pemrograman C++

Praktikum:

* Implementasi algoritma Stack pada bahasa pemrograman C++

#### Tugas

1. [Implementasi Priority Queue/Stack](https://struktur-data.github.io/syllabus/assignments/priority-queue-stack).
   Batas akhir pengumpulan: Minggu-5 perkuliahan setelah UTS (minggu ke-12).

### Minggu ke-9

Sesi ke-1:

* Pengertian dan Algoritma Queue menggunakan Array

Sesi ke-2:

* Implementasi algoritma Queue pada bahasa pemrograman C++

#### Tugas

1. [Implementasi Struktur Data Graf](https://struktur-data.github.io/syllabus/assignments/graph).
   Batas akhir pengumpulan: Minggu-6 perkuliahan setelah UTS (minggu ke-13).

### Minggu ke-10

Sesi ke-1:

* Implementasi algoritma Queue pada bahasa pemrograman C++

Sesi ke-2:

* Implementasi algoritma Queue pada bahasa pemrograman C++

Praktikum:

* Implementasi algoritma Queue pada bahasa pemrograman C++

#### Tugas

* TODO

### Minggu ke-11

Sesi ke-1:

* Review algoritma rekursif

Sesi ke-2:

* Review algoritma rekursif

#### Tugas

* TODO

### Minggu ke-12

Sesi ke-1:

* Pengertian Tree beserta implementasi algoritma penelusurannya (preorder, inorder, postorder)
* Pengertian dan Algoritma Binary Search Tree 
* Implementasi Algoritma Binary Search Tree pada bahasa pemrograman C++

Sesi ke-2:

* Implementasi Binary Search Tree pada suatu kasus

Praktikum:

* Implementasi Algoritma Binary Search Tree pada bahasa pemrograman C++

#### Tugas

* TODO

### Minggu ke-13

Sesi ke-1:

* Pengertian dan Algoritma Graph

Sesi ke-2:

* Pengertian dan implementasi algoritma penelusuran Graf (BFS dan DFS)

#### Tugas

* TODO

### Minggu ke-14

Sesi ke-1:

* Implementasi Algoritma Graph pada bahasa pemrograman C++

Sesi ke-2:

* Implementasi Graph pada suatu kasus

Praktikum:

* Implementasi Algoritma Graph pada bahasa pemrograman C++
* Implementasi Graph pada suatu kasus

#### Tugas

* TODO

### Ujian Akhir Semester (UAS)

Materi ujian:

1. Stack
2. Queue
3. Tree
   * Algoritma penelusuran tree: preorder, inorder, postorder
   * Binary Search Tree
4. Graph
   * Algoritma penelusuran graph: BFS dan DFS

## Tips Tugas Kelompok

* Kelompok maksimal dua orang
* Tentukan editor/IDE dan lingkungan yang nyaman bagi kalian
* Anggota dengan pengalaman lebih sedikit sebaiknya mendapat porsi pengerjaan lebih intensif
* Bergantian dalam mengerjakan
* Sering-seringlah menyimpan kode dan melakukan _commit & push/sync_

## Pustaka

### Pustaka Utama

* Diktat Kuliah IF2181 Struktur Data, Inggriani Liem, ITB, 2003.

###	Pustaka Pendukung

* Standish, Thomas A. [Data Structures, Algorithms, & Software Principles in C](http://openlibrary.telkomuniversity.ac.id/home/catalog/id/36466/slug/data-structures-algorithms-software-principles-in-c.html). Addison wesley Publishing Company 1995.
* AHO, Alfred V., John E. Hopcroft, Jeffrey D. Ullman. [Data Structures and Algorithm](http://openlibrary.telkomuniversity.ac.id/home/catalog/id/34600/slug/data-structures-and-algorithms.html). Addison Wesley Publishing Company. 1987.

### Materi Pemula

Agar dapat memahami mata kuliah ini dengan lancar, Anda perlu menguasai dasar algoritma dan pemrograman.
Kapan pun Anda membutuhkannya, silakan manfaatkan referensi berikut...

* [Dasar Algoritma dan Pemrograman](http://dedetarwidi.staff.telkomuniversity.ac.id/lectures/dasar-algoritma-dan-pemrograman/) oleh [Dede Tarwidi, S.Si., M.Si., M.Sc.](http://dedetarwidi.staff.telkomuniversity.ac.id/)

### Tools

#### Tools Utama

* C/C++ Compiler dan IDE: [Code::Blocks](http://www.codeblocks.org) (termasuk GCC/G++ compiler dan GDB debugger dari [TDM-GCC](http://tdm-gcc.tdragon.net/))
   * Alternatif: [Eclipse for C++ Development](https://www.eclipse.org/) + GCC/G++ compiler dan GDB debugger dari [TDM-GCC](http://tdm-gcc.tdragon.net/)

      Bila menggunakan Eclipse di Windows, agar project dapat dieksekusi:

      1. Klik kanan di _project_ > Properties
      2. Pilih C/C++ Build:

          Ganti _Build command_ menjadi: `mingw32-make`

      3. Pilih C/C++ Build > Settings > Binary Parsers:

         Centang: Windows PE

#### Tools Pendukung

* C/C++ build system: [CMake](http://www.cmake.org)
* unit testing: [Google Test](https://github.com/google/googletest)
* berbagi kode: [gist.github.com](https://gist.github.com/)
* tanya jawab: [Stack Overflow](http://stackoverflow.com/)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](http://hackerhours.org/resources.html#github)
    * [Student Developer Pack](https://education.github.com/pack)
* [Download Git](https://git-scm.com/downloads)
* GUI Clients: [TortoiseGit](https://tortoisegit.org/), [SourceTree](https://www.sourcetreeapp.com/), [GitHub Desktop](https://desktop.github.com/), [GitKraken](http://gitkraken.com/)

### Latihan Soal

* [Data Structures Challenges - HackerRank](https://www.hackerrank.com/domains/data-structures)
   * [Arrays Challenges - HackerRank](https://www.hackerrank.com/domains/data-structures/arrays)
   * [Linked Lists Challenges - HackerRank](https://www.hackerrank.com/domains/data-structures/linked-lists)
   * [Stacks Challenges - HackerRank](https://www.hackerrank.com/domains/data-structures/stacks)
   * [Queues Challenges - HackerRank](https://www.hackerrank.com/domains/data-structures/queues)
   * [Trees Challenges - HackerRank](https://www.hackerrank.com/domains/data-structures/trees)
   * [Components in a graph - HackerRank](https://www.hackerrank.com/challenges/components-in-graph/problem)
* [Data Structures Problems - HackerEarth](https://www.hackerearth.com/practice/data-structures/)
   * [Arrays 1-D](https://www.hackerearth.com/practice/data-structures/arrays/1-d/tutorial/)
   * [Singly Linked List](https://www.hackerearth.com/practice/data-structures/linked-list/singly-linked-list/practice-problems/)
   * [Stacks](https://www.hackerearth.com/practice/data-structures/stacks/basics-of-stacks/)
   * [Queues](https://www.hackerearth.com/practice/data-structures/queues/basics-of-queues/)
   * [Binary Search Tree](https://www.hackerearth.com/practice/data-structures/trees/binary-search-tree/practice-problems/)
* [CodeChef](https://www.codechef.com/)

## Pembobotan Nilai

* UTS – 25%
* UAS - 35%
* Tugas - 25%
* Praktikum – 15%

## Distribusi Nilai

| Indeks | Rentang        |
|--------|----------------|
| A      | >= 80.01       |
| AB     | 80.01 .. 80.00 |
| B      | 65.01 .. 70.00 |
| BC     | 60.01 .. 65.00 |
| C      | 50.01 .. 60.00 |
| D      | 40.01 .. 50.00 |
| E      | <= 40.00       |

## Plagiarisme

Bagi yang melakukan kecurangan/plagiarism nilainya akan diturunkan sesuai dengan tingkat plagiarismenya.

Dimohon menghargai ketentuan penggunaan dan/atau lisensi dari kode apa pun yang Anda temukan, dan apabila Anda mengimplementasikan atau menduplikasi sebuah algoritma atau kode dari sumber lain, cantumkan kredit/atribusi ke sumber berbentuk komentar dalam kode.

## Ucapan Terima Kasih

Struktur mata kuliah dan pemanfaatan GitHub berdasarkan [Advanced JavaScript](https://github.com/advanced-js/syllabus) oleh Aidan Feldman.
