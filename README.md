# tugas-paa
<h2>Ade Sinta_F55121062</h2>

Analisis Final Project PAA
A. Bubble Sort
   <p>&#9679 Worst case: Jika elemen-elemen dalam array sudah dalam urutan terbalik, maka dalam setiap iterasi, elemen terbesar akan dipindahkan ke posisi akhir array. Dalam hal ini, algoritma Bubble Sort akan melakukan (n-1) perbandingan untuk setiap iterasi, dengan n adalah jumlah elemen dalam array. Oleh karena itu, jumlah perbandingan dalam worst case adalah (n-1) + (n-2) + ... + 2 + 1 = (n * (n-1)) / 2. Waktu komputasi dalam worst case adalah O(n^2).</p>
    <p>&#9679 Best case: Jika elemen-elemen dalam array sudah dalam urutan terurut, maka dalam setiap iterasi tidak ada pertukaran elemen yang dilakukan. Namun, algoritma Bubble Sort tetap akan melakukan (n-1) perbandingan untuk setiap iterasi. Waktu komputasi dalam best case juga adalah O(n^2), meskipun tidak ada pertukaran yang dilakukan.</p>
    <P>&#9679 Average case: Rata-rata, algoritma Bubble Sort akan melakukan sekitar (n * (n-1)) / 4 perbandingan. Waktu komputasi dalam average case juga adalah O(n^2).</p>

B. Insertion Sort
   <p>&#9679 Worst case: Jika elemen-elemen dalam array sudah dalam urutan terbalik, maka dalam setiap iterasi, algoritma Insertion Sort akan memindahkan setiap elemen ke posisi yang benar secara berurutan. Jumlah perbandingan dan pemindahan dalam worst case adalah sekitar (n^2) / 2, sehingga waktu komputasi dalam worst case adalah O(n^2).</p>
   <p>&#9679 Best case: Jika elemen-elemen dalam array sudah dalam urutan terurut, maka dalam setiap iterasi, hanya satu perbandingan yang dilakukan untuk memeriksa apakah elemen yang akan dimasukkan sudah berada pada posisi yang benar. Oleh karena itu, waktu komputasi dalam best case adalah O(n).</p>
   <P>&#9679 Average case: Rata-rata, algoritma Insertion Sort akan melakukan sekitar (n^2) / 4 perbandingan dan pemindahan. Waktu komputasi dalam average case juga adalah O(n^2).</p>
