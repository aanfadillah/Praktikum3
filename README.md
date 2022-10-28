### Nama = Aan Fadillah Putra
### Nim = 312210327 
### Kelas = TI.22.A.3

# Latihan 1 
## Penggunaan end

  Gunakan Parameter akhir dalam fungsi cetak-cetak untuk menambahkan string apa pun. Hasil akhir output dari pernyataan print dengan python.
  Secara default, fungsi adalah cetak diakhiri dengan baris baru.
  Melewati spasi putih ke parameter akhir (end=' ') menunjukkan bahwa karakter akhir harus diidentifikasi oleh spasi dan bukan baris baru.
```
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')
```
<img width="125" alt="aan1" src="https://user-images.githubusercontent.com/115763475/198224750-e09a84ec-9920-4d19-add9-081467e70d98.png">


## Penggunaan Seperator
```
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
<img width="179" alt="aan2" src="https://user-images.githubusercontent.com/115763475/198225229-59bb3ad3-a674-49db-a501-1ade21362176.png">

## String Format 
String Formatting atau Pemformatan string memungkinkan kita memasukan item ke dalam string dari pada kita mencoba untuk menggabungkan string menggunakan koma atau string concatenation. 
```
# string format
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
```
<img width="118" alt="aan3" src="https://user-images.githubusercontent.com/115763475/198225484-fce47374-6acf-4a70-bd1b-f566234dad90.png">

## String Format 2
```
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(0, 10**1))
print('{0:>3} {1:>16}'.format(0, 10**2))
print('{0:>3} {1:>16}'.format(0, 10**3))
print('{0:>3} {1:>16}'.format(0, 10**4))
print('{0:>3} {1:>16}'.format(0, 10**5))
print('{0:>3} {1:>16}'.format(0, 10**6))
print('{0:>3} {1:>16}'.format(0, 10**7))
print('{0:>3} {1:>16}'.format(0, 10**8))
print('{0:>3} {1:>16}'.format(0, 10**9))
print('{0:>3} {1:>16}'.format(0, 10**10))
```
<img width="275" alt="aan4" src="https://user-images.githubusercontent.com/115763475/198226035-ccc542d5-eef0-4060-b531-c9a401e1fea7.png">

## Hasil Latihan 1

![Hasil1](https://user-images.githubusercontent.com/115763475/198227429-f668fd64-0ba9-4ba4-9f3c-2ae45781fc04.png)

# Latihan 2

## Input Variable
Penggunaan python untuk menginput nilai variabel dengan cara,
```
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
```
<img width="181" alt="aan5" src="https://user-images.githubusercontent.com/115763475/198228809-0e8141fe-cf0f-4f43-a99c-9ab8c2e2d435.png">

## Cetak Variable
Mencetak nilai kedua variabel ketika sudah di input, 
```
print("variable a=",a)
print("variable b=",b)
```
<img width="143" alt="aan6" src="https://user-images.githubusercontent.com/115763475/198229038-3ed96157-27ab-4f84-9032-d5b9a5ba90e5.png">

## Penggabungan Variable
Penggabungan kedua nilai Variable, 
```
print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))
```
<img width="355" alt="aan7" src="https://user-images.githubusercontent.com/115763475/198229373-c8239bfd-8318-4aa4-a204-48b70d30eefb.png">

## Input Variable 2
Penggunaan python untuk menginput kedua variable, 
```
a=int(a)
b=int(b)
```
<img width="65" alt="aan8" src="https://user-images.githubusercontent.com/115763475/198229452-7c65ce32-3a5e-452e-a38f-7ca7b5baa9bd.png">

## Konversi Nilai Variable
Mencetak kembali hasil mengkonversi nilai kedua variabel,  
```
print("hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}+{0}=%d".format(a,b) %(a/b))
```
<img width="382" alt="aan9" src="https://user-images.githubusercontent.com/115763475/198229495-57afd1de-6ba6-4361-a611-2be201472580.png">

## Hasil Latihan 2

<img width="170" alt="aan10" src="https://user-images.githubusercontent.com/115763475/198229678-17a1c4e5-ade5-4fcb-8cf5-e106f60bd63f.png">

# Latihan 3 Menggunakan String Format untuk membuat Belah Ketupat

<img width="629" alt="aan11" src="https://user-images.githubusercontent.com/115763475/198229848-6e12a2f2-65b9-4516-b0d8-59d4454b2e37.png">

# Latihan 4 Luas dan Keliling Lingkaran
## Flowchart untuk mencari Luas dan Keliling Lingkaran 

![Flowchart-menghitung-luas-keliling-lingkaran-1](https://user-images.githubusercontent.com/115763475/198231868-8d08d703-453f-4fb2-8887-b59299df7579.png)

## Membuat Program untuk Mencari Luas dan Keliling Lingkaran
Rumus Luas Lingkaran adalah phi * (r * r) atau phi * r² 

Rumus Keliling Lingkaran adalah 2 * phi * r
```
print('Menghitung luas dan keliling lingakaran')
print('==============================')
```
## Menginput Nilai Jari-Jari
Menginput jari jari untuk mencari luas dan keliling lingkaran,
```
r = int(input('masukan jari-jari lingkaran: '))
```
## Mendeklarasikan Nilai Phi
Nilai Phi adalah 3,14 atau 22/7
```
phi = 3.14
L = phi * (r * r)
K = 2 * phi * r
```
## Mencetak Hasil Luas dan keliling Lingkaran
```
print('Luas lingkaran dengan jari-jari {} adalah {}'.format(r, L))

print('Keliling lingkaran dengan jari-jari {} adalah {}'.format(r, K))
```
<img width="435" alt="aan12" src="https://user-images.githubusercontent.com/115763475/198231998-08ba51ee-6404-4b83-a999-cf1fc6e3f186.png">

## Hasil Latihan 4 Luas dan Keliling Lingkaran

<img width="325" alt="aan13" src="https://user-images.githubusercontent.com/115763475/198232100-a81e77ec-6aaf-4c52-961c-902551e943c0.png">

# ================SELESAI================
