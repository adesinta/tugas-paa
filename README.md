<h2>Ade Sinta_F55121062</h2>

#Analisis Final Project PAA
<h3>ALGORITMA BUBBLE SORT &amp; INSERTION SORT</h3>

<h4>A. Bubble Sort</h4>
<ul>
  <li><strong>Worst case:</strong> Jika elemen-elemen dalam array sudah dalam urutan terbalik, maka dalam setiap iterasi, elemen terbesar akan dipindahkan ke posisi akhir array. Dalam hal ini, algoritma Bubble Sort akan melakukan (n-1) perbandingan untuk setiap iterasi, dengan n adalah jumlah elemen dalam array. Oleh karena itu, jumlah perbandingan dalam worst case adalah (n * (n-1)) / 2. Waktu komputasi dalam worst case adalah O(n^2).</li>
  <li><strong>Best case:</strong> Jika elemen-elemen dalam array sudah dalam urutan terurut, maka dalam setiap iterasi tidak ada pertukaran elemen yang dilakukan. Namun, algoritma Bubble Sort tetap akan melakukan (n-1) perbandingan untuk setiap iterasi. Waktu komputasi dalam best case juga adalah O(n^2), meskipun tidak ada pertukaran yang dilakukan.</li>
  <li><strong>Average case:</strong> Rata-rata, algoritma Bubble Sort akan melakukan sekitar (n * (n-1)) / 4 perbandingan. Waktu komputasi dalam average case juga adalah O(n^2).</li>
</ul>

<h4>B. Insertion Sort</h4>
<ul>
  <li><strong>Worst case:</strong> Jika elemen-elemen dalam array sudah dalam urutan terbalik, maka dalam setiap iterasi, algoritma Insertion Sort akan memindahkan setiap elemen ke posisi yang benar secara berurutan. Jumlah perbandingan dan pemindahan dalam worst case adalah sekitar (n^2) / 2, sehingga waktu komputasi dalam worst case adalah O(n^2).</li>
  <li><strong>Best case:</strong> Jika elemen-elemen dalam array sudah dalam urutan terurut, maka dalam setiap iterasi, hanya satu perbandingan yang dilakukan untuk memeriksa apakah elemen yang akan dimasukkan sudah berada pada posisi yang benar. Oleh karena itu, waktu komputasi dalam best case adalah O(n).</li>
  <li><strong>Average case:</strong> Rata-rata, algoritma Insertion Sort akan melakukan sekitar (n^2) / 4 perbandingan dan pemindahan. Waktu komputasi dalam average case juga adalah O(n^2).</li>
</ul>

<h3>ALGORITMA TSP &amp; DJIKSTRA</h3>

<h4>A. Analisis Travelling Salesman Problem (TSP)</h4>
<ul>
  <li><strong>Worst Case:</strong> Jumlah simpul dalam grafik: n. Jumlah permutasi: (n-1)!. Algoritma akan memeriksa setiap permutasi dengan memeriksa semua kemungkinan jalur. Jadi, pada kasus terburuk, jumlah iterasi yang dilakukan adalah (n-1)!. Kompleksitas waktu: O((n-1)!).</li>
  <li><strong>Best Case:</strong> Jika grafik hanya memiliki 2 simpul (misalnya 'a' dan 'b'), maka algoritma hanya memeriksa satu jalur 'a' -> 'b' dengan jarak yang terkait dalam grafik. Jadi, pada kasus terbaik, jumlah iterasi yang dilakukan adalah 1. Kompleksitas waktu: O(1).</li>
  <li><strong>Average Case:</strong> Pada kasus rata-rata, algoritma perlu memeriksa sebagian besar atau semua permutasi yang mungkin. Jumlah iterasi yang dilakukan dapat didekati sebagai faktorial dari jumlah simpul dikurangi dengan faktorial dari jumlah simpul dikurangi 1. Kompleksitas waktu: O((n-1)!).</li>
</ul>

<h4>B. Analisis Dijkstra</h4>
<ul>
  <li><strong>Worst Case:</strong> Jumlah simpul dalam grafik: n. Jumlah tepi (edges) dalam grafik: m. Dalam kasus terburuk, setiap simpul akan terhubung dengan semua simpul lainnya. Algoritma Dijkstra akan memproses setiap simpul dan tepi dalam grafik. Jumlah iterasi yang dilakukan adalah n * m. Kompleksitas waktu: O(n * m).</li>
  <li><strong>Best Case:</strong> Jika grafik hanya memiliki satu simpul, maka algoritma hanya akan memproses simpul tersebut. Jumlah iterasi yang dilakukan adalah 1. Kompleksitas waktu: O(1).</li>
  <li><strong>Average Case:</strong> Pada kasus rata-rata, algoritma Dijkstra memproses sejumlah simpul dan tepi berdasarkan struktur grafik yang diberikan. Jumlah iterasi yang dilakukan dapat bervariasi tergantung pada jumlah simpul dan tepi dalam grafik. Kompleksitas waktu: O(n * m).</li>
</ul>
