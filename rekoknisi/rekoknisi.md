# proses "pengerjaan" seluruh kode dibawah

1. membuat sebuah flowchart

![image](https://user-images.githubusercontent.com/92983457/139357752-80e75059-39ce-4e37-a2a7-147fc15fc4f3.png)

2. menjalankan program pada flowgorithm

![image](https://user-images.githubusercontent.com/92983457/139358438-e4b63ab4-bd8a-41eb-9c3d-b2a4594a2f8d.png)


3. mengubah flowchart menjadi source code python

![image](https://user-images.githubusercontent.com/92983457/139357846-2cad005f-0c15-44b6-bd24-8632c30688b3.png)

4. Modifikasi penulisan dan menjalankan program di vscode

![image](https://user-images.githubusercontent.com/92983457/139358151-c4be4036-9c68-4b04-9b32-e2592e977f19.png)


# Jawaban tugas rekoknisi proses run di vscode 

## a. Menghitng keliling dan luas persegi panjang 
Code
```py
print("Masukkan panjang : ")
panjang = int(input("Panjang = "))
print("\nMasukkan lebar :")
lebar = int(input("Lebar = "))
luas = panjang * lebar
keliling = 2 * (panjang + lebar)
print("\nLuas persegi panjang adalah : " + str(luas))
print("Keliling persegi panjang adalah :" + str(keliling) +("\n"))
```
Hasil

![a](https://user-images.githubusercontent.com/92983457/138992449-2f9cc5c2-99a0-42a7-9f2e-6d20c90f3a81.gif)

## b. Reamur ke celcius
Code
```py
r = float(input("Inputkan reamur : "))
c = float(5) / 4 * r
print("Maka suhu dalam Celcius : " + str(c))
```
Hasil

![tugasb](https://user-images.githubusercontent.com/92983457/139060467-653667b2-56ef-4537-b11f-3eaa46bb459c.gif)

## c. Fahrenheit ke celcius
Code
```py
f = float(input("Inputkan suhu fahreinheit : "))
c = (f - 32) * (float(5) / 9)
print("\nMaka suhu dalam Celcius :" + str(c))
```
Hasil

![tugasc](https://user-images.githubusercontent.com/92983457/139061209-fb1a2ab0-39bb-4c53-af71-b485c46e9504.gif)

## d. Celcius ke reamur
Code
```py
c = float(input("Input celcius : "))
r = float(4) / 5 * c
print("Maka suhu dalam Reamur : " + str(r))
```
Hasil

![tugasd](https://user-images.githubusercontent.com/92983457/139061875-c8c295c7-2ee2-41d0-beec-450a76a132f2.gif)

## e. Celcius ke fahrenheit
Code
```py
c = float(input("Masukkan Celcius : "))
f = c * (float(9) / 5) + 32
print("Maka suhu dalam Fahrenheit adalah : " + str(f))
```
Hasil

![tugase](https://user-images.githubusercontent.com/92983457/139062321-bfcf3ac6-24d1-4ac7-90c2-13a14a467598.gif)
