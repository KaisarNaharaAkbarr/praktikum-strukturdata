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

00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000

1. Membuat Queue
queue = []
______________________________________________________________________
Program memulai dengan membuat list kosong yang akan digunakan sebagai antrian.
List ini menjadi tempat seluruh elemen yang masuk ke queue.



2. Operasi Enqueue (Menambahkan Elemen ke Belakang Antrian)
queue.append('A')
queue.append('B')
queue.append('C')
print("Queue: ", queue)
______________________________________________________________________
Bagian ini memasukkan tiga data: 'A', 'B', dan 'C'.
Setiap elemen ditambahkan ke posisi paling belakang antrian menggunakan append().
Pada tahap ini, isi queue menjadi: ['A', 'B', 'C'].



3. Operasi Dequeue (Mengambil Elemen Paling Depan)
element = queue.pop(0)
print("Dequeue: ", element)
______________________________________________________________________
Operasi dequeue menghapus elemen pertama dari antrian, yaitu indeks ke-0.
Karena queue memakai sistem FIFO, maka 'A' adalah elemen pertama yang keluar.



4. Operasi Peek (Melihat Elemen Depan Tanpa Menghapus)
frontElement = queue[0]
print("Peek: ", frontElement)
______________________________________________________________________
Dengan mengakses queue[0], program dapat mengetahui elemen terdepan saat ini.
Setelah 'A' terhapus, elemen berikutnya di depan adalah 'B'.




5. Mengecek Apakah Queue Kosong
isEmpty = not bool(queue)
print("isEmpty: ", isEmpty)
______________________________________________________________________
Program memeriksa apakah antrian masih memiliki elemen.
Jika list tidak kosong, maka queue masih berisi data dan hasilnya adalah False.



6. Menghitung Jumlah Elemen dalam Queue
print("Size: ", len(queue))
______________________________________________________________________
Bagian ini menghitung total elemen di dalam antrian setelah operasi dequeue.
Karena 'A' sudah dihapus, isi queue sekarang tinggal dua elemen.
