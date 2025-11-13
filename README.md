Pada slide ini ditunjukkan contoh program sederhana yang memperlihatkan bagaimana struktur data stack bekerja. Stack adalah tumpukan data yang memakai konsep LIFO (Last In, First Out), artinya elemen yang dimasukkan paling akhir akan menjadi elemen pertama yang diambil.


1. Membuat Stack
stack = []
______________________________________________________________________
Program memulai dengan membuat sebuah list kosong yang akan digunakan sebagai struktur stack. List ini berfungsi sebagai tempat penyimpanan elemen-elemen.



2. Operasi Push (Menambahkan data)
stack.append('A')
stack.append('B')
stack.append('C')
print("Stack: ", stack)
______________________________________________________________________
Di bagian ini, program memasukkan tiga data: 'A', 'B', dan 'C'.
Setiap elemen ditambahkan ke bagian atas stack dengan append().
Hasil akhirnya adalah stack berisi ['A', 'B', 'C'].



3. Operasi Pop (Mengambil data teratas)
element = stack.pop()
print("Pop: ", element)
______________________________________________________________________
pop() digunakan untuk menghapus elemen paling akhir dari stack.
Karena stack memakai sistem LIFO, elemen 'C' adalah yang pertama keluar.
Setelah di-pop, elemen tersebut dicetak.



4. Operasi Peek (Melihat elemen teratas tanpa menghapus)
topElement = stack[-1]
print("Peek: ", topElement)
______________________________________________________________________
Untuk mengetahui elemen yang sekarang berada di puncak stack, program mengakses indeks terakhir (-1).
Elemen paling atas setelah C terhapus adalah 'B'.



5. Mengecek apakah Stack Kosong
isEmpty = not bool(stack)
print("isEmpty: ", isEmpty)
______________________________________________________________________
Program memeriksa apakah stack masih memiliki isi.
bool(stack) akan bernilai True jika ada elemen.
not bool(stack) menjadi False, artinya stack tidak kosong.



6. Menghitung Jumlah Elemen
print("Size: ", len(stack))
______________________________________________________________________
Bagian ini menampilkan berapa banyak elemen yang tersisa pada stack setelah operasi pop dilakukan.
Karena 'C' sudah dihapus, maka total elemen kini menjadi 2.
