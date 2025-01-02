## Nama : Alya Febrianti
## kelas : TI.24.A1

# String-latihan-pertemuan15
## Hasil Input Latihan 1

```python
txt = 'Hello World'

# Hitung jumlah karakternya
jumlah_karakter = len(txt)
print("Jumlah karakter:", jumlah_karakter)

# Ambil karakter terakhir
karakter_terakhir = txt[-1]
print("Karakter terakhir:", karakter_terakhir)

# Ambil karakter index ke-2 sampai index ke-4 (llo)
substring = txt[2:5]
print("Karakter index ke-2 sampai index ke-4:", substring)

# Hilangkan spasi pada teks tersebut (HelloWorld)
tanpa_spasi = txt.replace(" ", "")
print("Teks tanpa spasi:", tanpa_spasi)

# Ubah teks menjadi huruf besar
huruf_besar = txt.upper()
print("Teks dalam huruf besar:", huruf_besar)

# Ubah teks menjadi huruf kecil
huruf_kecil = txt.lower()
print("Teks dalam huruf kecil:", huruf_kecil)

# Ganti karakter H dengan karakter J
ganti_h = txt.replace("H", "O")
print("Teks setelah mengganti H dengan O:", ganti_h)
```

## Hasil Input Latihan 2

```python
Teks setelah mengganti H dengan O: Oello World
```

## Hasil Output Latihan 1
```markdown
Hello, nama saya alya, dan umur saya adalah 18 tahun
```

## Hasil Output Latihan 2

```markdown
Hello, nama saya alya, dan umur saya adalah 18 tahun
```

## Penjelasan Input Latihan 1
Berikut adalah penjelasan untuk hasil dari kode Python yang Anda berikan:

1. **Hitung jumlah karakter**
   ```python
   jumlah_karakter = len(txt)
   ```
   Fungsi `len()` menghitung jumlah karakter dalam string `txt`. String `txt` adalah `"Hello World"`, yang terdiri dari 11 karakter (termasuk spasi).  
   **Output:** `Jumlah karakter: 11`

2. **Ambil karakter terakhir**
   ```python
   karakter_terakhir = txt[-1]
   ```
   Index `-1` merujuk pada karakter terakhir dalam string. Dalam hal ini, karakter terakhir adalah huruf `"d"`.  
   **Output:** `Karakter terakhir: d`

3. **Ambil karakter index ke-2 sampai index ke-4**
   ```python
   substring = txt[2:5]
   ```
   Operasi slicing `[2:5]` mengambil karakter dari index ke-2 hingga sebelum index ke-5. Index ke-2 adalah `"l"`, index ke-3 adalah `"l"`, dan index ke-4 adalah `"o"`.  
   **Output:** `Karakter index ke-2 sampai index ke-4: llo`

4. **Hilangkan spasi pada teks**
   ```python
   tanpa_spasi = txt.replace(" ", "")
   ```
   Fungsi `replace()` menggantikan semua spasi (`" "`) dengan string kosong (`""`). Hasilnya, teks menjadi `"HelloWorld"`.  
   **Output:** `Teks tanpa spasi: HelloWorld`

5. **Ubah teks menjadi huruf besar**
   ```python
   huruf_besar = txt.upper()
   ```
   Metode `upper()` mengubah semua karakter dalam string menjadi huruf besar.  
   **Output:** `Teks dalam huruf besar: HELLO WORLD`

6. **Ubah teks menjadi huruf kecil**
   ```python
   huruf_kecil = txt.lower()
   ```
   Metode `lower()` mengubah semua karakter dalam string menjadi huruf kecil.  
   **Output:** `Teks dalam huruf kecil: hello world`

7. **Ganti karakter `H` dengan karakter `O`**
   ```python
   ganti_h = txt.replace("H", "O")
   ```
   Fungsi `replace()` mengganti semua huruf `H` dengan huruf `O`. Dalam teks `"Hello World"`, hanya huruf pertama (`H`) yang diganti menjadi `O`, sehingga hasilnya menjadi `"Oello World"`.  
   **Output:** `Teks setelah mengganti H dengan O: Oello World`

Semua fungsi ini memodifikasi atau memproses string sesuai dengan kebutuhan, dan hasilnya dicetak dengan perintah `print()`.


## Penjelasan Hasil Output Latihan 1
Berikut adalah penjelasan untuk masing-masing hasil output tersebut:

### **1. Teks dalam huruf besar: `HELLO WORLD`**
   - **Kode:** 
     ```python
     huruf_besar = txt.upper()
     ```
   - **Penjelasan:**  
     Metode `upper()` mengubah semua karakter dalam string menjadi huruf besar (uppercase).  
     Contoh:  
     - `H` tetap menjadi `H` karena sudah besar.  
     - `e` berubah menjadi `E`.  
     - Semua huruf kecil lainnya (`l`, `o`, `w`, `r`, `d`) berubah menjadi huruf besar.  
     Spasi tidak terpengaruh karena bukan karakter huruf.  
     **Output:** `HELLO WORLD`

---

### **2. Teks dalam huruf kecil: `hello world`**
   - **Kode:** 
     ```python
     huruf_kecil = txt.lower()
     ```
   - **Penjelasan:**  
     Metode `lower()` mengubah semua karakter dalam string menjadi huruf kecil (lowercase).  
     Contoh:  
     - `H` berubah menjadi `h`.  
     - Semua huruf besar lainnya (jika ada) akan berubah menjadi huruf kecil.  
     Spasi tidak terpengaruh karena bukan karakter huruf.  
     **Output:** `hello world`

---

### **3. Teks setelah mengganti `H` dengan `O`: `Oello World`**
   - **Kode:** 
     ```python
     ganti_h = txt.replace("H", "O")
     ```
   - **Penjelasan:**  
     Fungsi `replace()` mengganti semua kemunculan huruf `H` dengan huruf `O` dalam string.  
     Dalam teks `"Hello World"`, hanya ada satu huruf `H`, yaitu di awal kata. Maka, huruf `H` berubah menjadi `O`, sementara huruf lainnya dan spasi tetap tidak berubah.  
     **Output:** `Oello World`

---

Hasil ini menunjukkan bagaimana fungsi string bawaan Python dapat digunakan untuk memodifikasi teks dengan berbagai cara.

## Penjelasan Hasil Input Latihan 2


