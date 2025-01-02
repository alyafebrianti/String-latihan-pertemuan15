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
umur = 18
txt = 'Hello, nama saya alya, dan umur saya adalah {} tahun'

print(txt.format(umur))
```
## Hasil Output Latihan 1

```markdown
Teks dalam huruf besar: HELLO WORLD
Teks dalam huruf kecil: hello world
Teks setelah mengganti H dengan O: Oello World
```
## Hasil Output Latihan 2

```markdown
Hello, nama saya alya, dan umur saya adalah 18 tahun
```
