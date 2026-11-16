# Transaksi-Potion-2.0

Link akses: https://dicarpio212.github.io/Transaksi-Potion-2.0/

Versi terbaru dari website Transaksi Potion

# Apa yang baru?

## Tampilan Pembelian Potion
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/06777da4-cc85-471a-8c2d-46075b408114" />

tampilan Pembelian Potion merupakan tampilan yang memungkinkan user untuk membeli potion berdasarkan ketersediaan potion maupun saldo yang dimiliki user. 

## Filter Potion

Di aplikasi sebelumnya, fitur ini hanya berlaku pada tampilan Inventory. Sekarang muncul juga pada tampilan Pembelian Potion dengan penyesuaian baru yaitu hanya menampilkan informasi yang relevan. Sisanya akan dibuat nonaktif dengan opacity 50%. Contoh tanpa filter akan terlihat seperti:
<img width="1712" height="758" alt="image" src="https://github.com/user-attachments/assets/862d2624-cb93-4e28-a277-781766827072" />

dan terapan salah satu filter potion. Maka akan tampil seperti ini:
<img width="1732" height="747" alt="image" src="https://github.com/user-attachments/assets/775ff15f-0c90-4aa0-820f-3ab1e0de15ac" />

## Keranjang Potion
Keranjang potion digunakan untuk menampung potion yang dipilih user untuk dibeli. Klik keranjang potion:
<img width="1920" height="1080" alt="Screenshot (192)" src="https://github.com/user-attachments/assets/bcd426d1-6ddb-4d59-b13b-e9a3a6748f50" />


dan kita akan dibawa ke tampilan Checkout Potion
<img width="1920" height="1080" alt="Screenshot (193)" src="https://github.com/user-attachments/assets/34a98e09-b32d-4339-88a6-7e21b7dd59a2" />

Angka yang ada pada ikon keranjang potion menunjukkan berapa banyak potion yang kalian beli. Normalnya keranjang potion masih diangka 0 saat memasuki website. Untuk mengisi keranjang tersebut, klik kartu potion apapun yang ada dalam daftar.
<img width="1728" height="767" alt="image" src="https://github.com/user-attachments/assets/43a62a8f-b3cb-443a-834c-e574e11c4e5e" />


Setiap klik akan menambah 1 potion dan memasukkan data tersebut kedalam tampilan checkout potion. Ini contoh sebelum klik "Angry Spell".
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d5199bdd-cf86-4c7b-99e0-0554e19023cc" />

dan Contoh setelah diklik "Angry Spell".
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ffd0d2a9-86b0-4513-89b0-61b6daa8a2d3" />

Tampilan checkout potion setelah "Angry Spell" masuk keranjang potion.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/36baf8a8-63bd-415b-9451-0c95559cb156" />

Jika menekan tombol "checkout", maka potion tersebut akan masuk ke tampilan Inventory kita. Lalu menambah stok potion jika potion yang dibeli sudah ada sebelumnya, mengurangi saldo, dan mengurangi stok potion yang ada dalam tampilan Pembelian Potion.
<img width="1707" height="541" alt="image" src="https://github.com/user-attachments/assets/fbf0ed1c-4f46-4c69-bdbb-33a80f4e7caa" />


Pada tampilan checkout potion, kita bisa menambah, mengurangi, dan menghapus potion sesuai keinginan kita.
<img width="611" height="215" alt="image" src="https://github.com/user-attachments/assets/a32c2168-20ec-4a3c-834d-0fbda0efefd8" />

Jika saldo tidak cukup atau stok yang ditampung lebih besar dari ketersediaan potion, maka keranjang tidak akan memuat barang tersebut. Saat ini belum ada peringatan atau alert dari sistem, Sehingga ini menjadi PR dalam pengembangan website kedepannya.

## Search

Di aplikasi sebelumnya, fitur ini hanya berlaku pada tampilan "Inventory". Sekarang muncul juga pada tampilan "Pembelian Potion"

## Tambah Gold

Di aplikasi sebelumnya, fitur ini hanya menambah 300 gold. Sekarang menjadi 500. 
