# PERINTAH DASAR LINUX

## mkdir
melakukan perintah :

    mkdir pert1

fungsinya untuk membuat folder baru di dalam direktori kerja.

- pert1 ini sebagai nama folder yang akan dibuat
#

## cd
melakukan perintah :

    cd belajar

fungsinya untuk masuk ke dalam folder yang diinginkan dan menjadikannya direktori kerja pada saat itu.

- belajar ini sebagai folder yang kita masuk
#

## cd ..
melakukan perintah :

    cd ..

fungsinya ketika sedang masuk ke dalam folder/direktori dan memakai perintah cd .. maka, folder/direktori tersebut kembali ke folder/direktori kerja sebelumnya.
#

## ls
melakukan perintah :

    ls belajar

fungsinya untuk melihat daftar file/folder yang ada di direktori kerja.

- belajar disini sebagai perintah yang akan dilihat daftar file/folder, ketika sudah melakukan perintah tersebut maka akan terlihat daftar file/folder.
- contohnya ketika melakukan perintah ls belajar maka, akan keluar daftar folder pert1 pert2

memodifikasi perintah untuk lebih tertuju pada direktori tersebut :
- -R untuk mencantumkan semua file di subdirektori
- a untuk menampilkan semua file, termasuk yang tersembunyi
#

## rm
melakukan perintah :

    rm -r belajar

fungsingnya untuk menghapus file.

- belajar sebagai file yang akan dihapus tersebut

memodifikasi perintah untuk lebih tertuju pada direktori tersebut :
- -r untuk menghapus direktori dan file secara rekursif (sebuah perulangan yang tidak melibatkan iterasi)
- -f untuk mengizinkan penghapusan file tanpa konfirmasi
- -i untuk meminta konfirmasi sebelum penghapusan
#

## rmdir
melakukan perintah :

    rmdir pert1

fungsinya untuk menghapus folder kosong.

- pert1 disini sebagai folder yang akan dihapus
#

## code .
melakukan perintah :

    code .

fungsinya untuk membuka vscode.
#

## touch
melakukan perintah :

    touch samplearray.cpp

fungsinya untuk menambahkan file kosong di dalam folder.

-sampelarray.cpp sebagai nama file
#

## nano
melakukan perintah :

    nano .

fungsinya untuk membuka configurasi dan sebagai text editor.
#

## &&
melakukan perintah :

    cd belajar && mkdir pert1 && cd pert1 && touch samplearray.cpp

fungsinya untuk menjalankan dua command atau lebih

- masuk ke dalam belajar && membuat folder baru pert1 && masuk ke dalam pert1 && membuat file baru di dalam pert1 bernama samplearray.cpp
#

## clear
melakukan perintah :

    clear

fungsinya untuk membersihkan terminal.
#

## exit
melakukan perintah :

    exit

fungsinya untuk keluar dari terminal.
#

## cara membuat folder baru di dalam direktori
membuka terminal ubuntu dan melakukan perintah :

    cd belajar
    mkdir pert1
    mkdir pert2

#

## cara membuka direktori di vscode
membuka terminal ubuntu dan melakukan perintah :

    cd belajar
    code .

#


# PERINTAH DASAR GIT

## git add
melakukan perintah :
    
    git add .

perintah ini juga sebagai menambahkan file ke index pada GIT.
#

## git commit
melakukan perintah :
    
    git commit -m "belajar"

fungsinya untuk menyimpan perubahan versi revisi pada GIT.

- -m disini sebagai sebuah pesan ketika commit di GIT
#

## git push
melakukan perintah :

    git push -u origin main = buat push ke github

fungsinya untuk mngirimkan perubahan ke main branch dari remote repository.

- -u sebagai branch yang sudah diperbarui atau yang sudah berhasil di push
#

## git init
melakukan perintah :

    git init

fungsinya untuk membuat repositori baru.
#


## g++
melakukan perintah :
    
    g++ samplearray.cpp -o samplearray
    ./samplearray

fungsinya untuk running c++ .
#

## git rm
melakukan perintah :

    git rm belajar

fungsinya untuk menghapus file dari index dan direktori kerja.
#

## cara meng-push ke GITHUB
membuka terminal ubuntu dan melakukan perintah :

    git add .
    git commit -m belajar
    git push -u origin main

#