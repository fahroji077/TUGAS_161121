# TUGAS_161121

1. MENCARI ANGKA TERBESAR

```y
a = int(input('masukkan nilai a : '))
b = int(input('masukkan nilai b : '))



if a > b :
    print('a yang terbesar')
elif b > a :
    print('b yang terbesar')
```
![image](https://user-images.githubusercontent.com/93015185/141986017-789e6c06-d7b2-43d0-977d-a2c871604625.png)

2. MENCARI ANGKA TERBESAR 2

```y
a = int(input('masukkan nilai a : '))
b = int(input('masukkan nilai b : '))
c = int(input('masukkan nilai c : '))


if a > b and a > c :
    print('a yang terbesar')
elif b > a and b > c :
    print('b yang terbesar')
else :
    print('c yang terbesar')
```
![image](https://user-images.githubusercontent.com/93015185/141986224-e9713138-bb06-4751-b696-9a6188f73d94.png)

3. MENENTUKAN BILANGAN YANG SAMA

```y
print("MENENTUKAN BILANGAN YANG SAMA")

a = int(input("MASUKKAN BILANGAN PERTAMA : "))
b = int(input("MASUKKAN BILANGAN KEDUA : "))
c = int(input("MASUKKAN BILANGAN KETIGA : "))

if a == b or a == c:
    sama = a
    print("NILAI YANG SAMA ADALAH ", sama)
elif b == a or b == c:
    sama = b
    print("NILAI YANG SAMA ADALAH ", sama)
else :
    print("TIDAK ADA NILAI YANG SAMA")
    
```
![image](https://user-images.githubusercontent.com/93015185/141986421-a4c05a86-6de4-4f10-815f-ea78c3fbe5e8.png)

4. MENGHITUNG BERAT BADAN

```y
judul = 'MENGHITUNG BERAT BADAN'
print(judul.rjust(50))
print("-"*70)
a = str(input('masukkan nama anda : '))
b = int(input('masukkan tinggi : '))

bb = b-100

print(f"saudara {a}, berat ideal anda adalah : {bb} kg")

```
![image](https://user-images.githubusercontent.com/93015185/141987442-3ad2bc25-0389-4cf3-bd44-7e10d6048196.png)

5. DATA NILAI MAHASISWA

```y
judul = "DATA NILAI MAHASISWA"
print(judul.rjust(50))
print("-"*70) 
tugas = float(input("Masukkan Nilai Tugas = "))
UTS = int(input("Masukkan Nilai UTS = "))
UAS = int(input("Masukkan Nilai UAS = "))

NA = (0.25 * tugas) + (0.35 * UTS)+ (0.40 * UAS)
print("-"*70)
judul = "NILAI AKHIR DAN GRADE"
print(judul.rjust(50))
print("-"*70)
input("Nama = ")
print(f"{NA}")

if NA >= 75:
    grade = 'A'
elif NA >= 60:
    grade = 'B'
elif NA >= 45:
    grade = 'C'
else :
    grade = 'D'
print("Grade = {}".format(grade))

```

![image](https://user-images.githubusercontent.com/93015185/141987842-370b1d06-aec4-4f68-8ed0-84b277b9b265.png)

6. MENGHITUNG GAJI PEGAWAI

```y
while True:
    judul = "DATA PEGAWAI"
    print(judul.center(60))
    print("="*60)
    nama = input("Nama             : ") 
    gol = input("Golongan         : ")
    jm_krj = int(input("Total Jam Kerja  : "))
    print("="*60)

    judul = "PERHITUNGAN GAJI"
    print(judul.center(60))
    print("="*60)
    if gol != "A" and gol != "B" and gol != "C":
        print("Golongan Tidak Ditemukan")
        continue

    if gol == "A":
        gapok = 500000
        tjk = gapok*(10/100)
        if jm_krj >= 200:
            lbr = jm_krj*5000
        elif jm_krj < 200:
                lbr = 0
        else: 
            print("-")
        print(f"Gaji Pokok       : Rp. {gapok}")
        print(f"Tunjangan        : Rp. {tjk}")
        print(f"Uang Lembur      : Rp. {lbr}")

    elif gol == "B":
        gapok = 700000
        tjk = gapok*(15/100)
        if jm_krj >= 200:
            lbr = jm_krj*7500
        elif jm_krj < 200:
                lbr = 0
        else: 
            print("-")
        print(f"Gaji Pokok       : Rp. {gapok}")
        print(f"Tunjangan        : Rp. {tjk}")
        print(f"Uang Lembur      : Rp. {lbr}")

    elif gol == "C":
            gapok = 900000
            tjk = gapok*(20/100)
            if jm_krj >= 200:
                lbr = jm_krj*10000
            elif jm_krj < 200:
                lbr = 0
            else: 
                print("-")
            print(f"Gaji Pokok       : Rp. {gapok}")
            print(f"Tunjangan        : Rp. {tjk}")
            print(f"Uang Lembur      : Rp. {lbr}")
    print("="*60)
    total = gapok + tjk + lbr
    print(f"Total            : Rp. {total}")
    break
    
```
![image](https://user-images.githubusercontent.com/93015185/141988194-0d0ea29a-2360-4105-8e03-5c9aa74cd942.png)
