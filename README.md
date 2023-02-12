# Python Super Cashier

## Latar Belakang
Super cashier adalah sistem kasir self-service supermarket dimana para customer dapat menginputkan item yang ingin diorder secara mandiri. Item yang dapat diinput berupa nama item, jumlah item, dan harga item yang diorder. Jika terdapat kesalahan input, customer dapat mengedit item yang diinginkan. Customer juga dapat menambahkan item yang ingin diorder maupun menghapus item yang batal untuk diorder. Customer juga dapat menampilkan data order yang telah diinput dan juga total harga dari item yang telah diorder. Selain itu, customer juga akan mendapatkan diskon jika melakukan order dengan kriteria minimum order yang telah ditentukan.

## Requirements / Objectives
1. Customer membuat ID transaksi customer
2. Customer menginput nama item, jumlah item, dan harga barang
3. Jika terdapat kesalahan dalam penginputan, customer dapat melakukan:
    
    a. Update nama item
    
    b. Update jumlah item
    
    c. Update harga item
4. Jika customer batal melakukan order, customer dapat melakukan:

    a. Delete item

    b. Reset transaction
5. Jika customer ingin memeriksa item order yang dipesan apakah sudah benar, customer dapat melakukan check order dengan ketentutan:
    
    a. Pesan “Pemesanan sudah benar” : jika tidak ada kesalahan input
    
    b. Pesan “Terdapat kesalahan input data” : jika terjadi kesalahan input
6. Menampilkan tabel output pemesanan yang telah diorder
7. Customer dapat melihat total belanja yang harus dibayar. Akan mendapatkan diskon jika memenuhi ketentuan:
    
    a. Total belanja > Rp. 200.000 : diskon 5%
    
    b. Total belanja > Rp. 300.000 : diskon 8%
    
    c. Total belanja > Rp. 500.000 : diskon 10%
    
 ## Alur Program / Flowchart
 
 ![image](https://user-images.githubusercontent.com/119796130/218290720-4aebb3a7-a0e4-449d-9995-2c012df00047.png)
 
 
 ## Penjelasan dari Function
1. init()

Fungsi inisialisasi untuk class Transaction

Data_order = dictionary untuk menyimpan data tranasaksi

2. add_item

Method untuk menambahkan item ke dalam dictionary transaksi

3. update_item_name

Method untuk mengubah nama item yang sudah diinput di dictionary transaksi

4. update_item_qty

Method untuk mengubah jumlah item yang sudah diinput di dictionary transaksi

5. update_item_price

Method untuk mengubah harga item yang sudah diinput di dictionary transaksi

6. delete_item

Method untuk menghapus nama item termasuk jumlah dan harga yang sudah diinput di dictionary transaksi

7. reset_transaction

Method untuk menghapus semua data pesanan yang telah terinput

8. check_order

Method untuk menampilkan dan memeriksa semua pesanan yang sudah diinput di dictionary transaksi

9. total_price

Method untuk menampilkan total belanja

## Test Case

**Test Case 1**

Menambahkan item dengan method add_item()

![image](https://user-images.githubusercontent.com/119796130/218289261-8f0a4c32-764f-4e29-96be-e7cf82b9945d.png)

**Test Case 2**

Menghapus item dengan method delete_item()

![image](https://user-images.githubusercontent.com/119796130/218289327-7c24e2b3-6d36-47ee-b7d0-4f04d33d445e.png)

**Test Case 3**

Menghapus semua data transaksi dengan method reset_transaction()

![image](https://user-images.githubusercontent.com/119796130/218289358-a433f3e2-5542-4eac-a227-69b79d843a01.png)

**Test Case 4**

Mengubah nama produk dengan method update_item_name()

![image](https://user-images.githubusercontent.com/119796130/218289383-90e92d93-0e68-42b5-a59f-a3a19b5b5a89.png)

**Test Case 5**

Mengubah kuantitas produk dengan method update_item_qty()

![image](https://user-images.githubusercontent.com/119796130/218289404-c09b031a-42a6-40a3-9cde-4057bce44212.png)

**Test Case 6**

Mengubah harga produk dengan method update_item_price()

![image](https://user-images.githubusercontent.com/119796130/218289444-72c2f80d-0c38-4df5-b903-6cadf65c5a8f.png)

**Test Case 7**

Memeriksa data order dengan method check_order()

![image](https://user-images.githubusercontent.com/119796130/218289463-fe15c38d-6638-46b4-815d-c9dc7542c4aa.png)


**Test Case 8**

Menampilkan total belanja dengan method total_price()

![image](https://user-images.githubusercontent.com/119796130/218289486-bcd8666e-0e10-4efa-9fb7-1a53e837280f.png)

**Test Case 9**

Keluar dari program kasir self-service

![image](https://user-images.githubusercontent.com/119796130/218289545-efbcd352-1f57-446f-843c-6e2da52bce3b.png)

# Kesimpulan
Sistem kasir self-service berfungsi untuk membantu para customer untuk memasukkan pesanan yang diinginkan secara mandiri. Sistem sudah dapat berjalan dengan baik, namun sitem ini dapat diperbaiki dan dikembangkan untuk meningkatkan performa dari sistem ini semakin user friendly.
