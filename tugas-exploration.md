# Tugas Eksplorasi

## 1. & (bitwise and) 
### a. Proses
Menghasilkan 1 pada bit ke n jika pada bit ke-n pada kedua operand bernilai 1, 0 jika tidak.
### b. Contoh
Contoh (5&6) = 4
__101 : 5
__110 : 6
&
__100 : 4


## 2. | (bitwise or)
### a. Proses
Menghasilkan 1 pada bit ke n jika pada bit ke-n pada setidaknya salah satu operand bernilai 1, 0 tidak ada bit 1 pada bit ke-n pada kedua operand.
### b. Contoh
(5|6) = 7
__101 : 5
__110 : 6
|
__111 : 7

## 3. ^ (bitwise xor)
### a. Proses
Menghasilkan 1 pada bit ke n jika pada bit ke-n pada kedua operand hanya satu yang bernilai 1, 0 jika kedua bit bernilai 1 atau 0.
### b. Contoh
(5|6) = 7
__101 : 5
__110 : 6
^
__011 : 3

## 4. \<\< (left shift)
### a. Proses
Menggeser bit ke kiri pada operand kiri sebanyak operand kanan. Bit baru yang berasal dari kanan bernilai 0.
### b. Contoh
(13\<\<2)
0000 0000 0000 1101: 13
0000 0000 0000 0100:  4

## 5. \>\> (right shift)
### a. Proses
Menggeser bit ke kanan pada operand kiri sebanyak operand kanan dengan mengabaikan geser pada most significant bit (bit sign). Bit baru yang berasal dari kanan bernilai 0.
### b. Contoh
(13\>\>2)
1111 1111 1111 1110: -2
1111 1111 1111 1111: -1

## 6. ~ (bitwise NOT)
### a. Proses
Reverse semua bit, bit 0 menjadi 1, bit 1 menjadi 0.
### b. Contoh
~13
1101: 13
0010: 2
