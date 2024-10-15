# Tugas Pertemuan 8 PBO - World of Zuul

## Membuat Code untuk masing-masing Kelas
CommandWords : https://github.com/itozt/tugas8PBO/blob/main/CommandWords.java <br>
Command : https://github.com/itozt/tugas8PBO/blob/main/Command.java <br>
Parser : https://github.com/itozt/tugas8PBO/blob/main/Parser.java <br>
Room : https://github.com/itozt/tugas8PBO/blob/main/Room.java <br>
Game : https://github.com/itozt/tugas8PBO/blob/main/Game.java <br>

## Membuat Diagram Kelas di BlueJ
Buat diagram kelas dengan urutan : CommandWords, Command, Parser, Room, Game
![image](https://github.com/user-attachments/assets/9831e77d-1be7-4a90-83dd-351ee255fde3)

## Menjalankan Aplikasi Game
Tahap untuk menjalankan aplikasi Game sebagai berikut :
1. Klik kanan pada kelas ```Game```
2. Klik ```new Game()``` untuk membuat objek baru
3. Klik ```oke```
4. Klik kanan pada objek ```Game``` pada object bench berwarna merah
5. Klik method ```void play()```
6. Ketika muncul tampilan terminal, kita akan mengecek comand "help". Ketikan ```help```. Maka akan muncul tampilan sebagai berikut :
![image](https://github.com/user-attachments/assets/96291d76-c151-4a6a-af5a-c61c2d12b96a)
7. Cek tempat yang ada di sekitarmu dengan memberikan comand ```go east```, ```go west```. ```go north```. atau ```go south``` sesuai dengan arah yang ada (Exits: ```arah```)
![image](https://github.com/user-attachments/assets/3edb9e39-913d-4f10-a076-809159ddf073)

## Membuat Ruangan Baru
Tahap untuk membuat ruangan sebagai berikut :
1. Klik kanan pada kelas ```Room```
2. Klik ```new Room(String description)``` untuk membuat objek baru
3. Ketikan nama ruangan baru pada ```new Room```
![image](https://github.com/user-attachments/assets/248c3d01-b351-4851-b8e0-07620ffd0484)
4. Klik ```oke```
5. Klik kanan pada objek ```Room``` pada object bench berwarna merah
6. Klik method ```void setExits()``` untuk menambahkan ruangan yang ada di sekitar dari ruangan tersebut
7. Ketikan nama ruangan di sekitar rungan yang kamu pilih. Jika sekitarnya tidak ada ruangan lain, maka masukkan ```null```
![image](https://github.com/user-attachments/assets/c723c53b-99a1-41a3-9569-0a6091a649b9)

## Mengecek Apakah Suatu Command dapat Dipakai
Tahap untuk mengecek apakah suatu command dapat dipakai sebagai berikut :
1. Klik kanan pada kelas ```CommandWords```
2. Klik ```new CommandWords()``` untuk membuat objek baru
3. Klik ```oke```
4. Klik kanan pada objek ```CommandWords``` pada object bench berwarna merah
5. Klik method ```booolean isCommand(String aString)```
6. Ketikkan suatu command dengan diawali dan diakhiri tanda petik "". Jika command tersebut bernilai true, maka command dapat digunakan. Jika command tersebut bernilai false, maka command tidak dapat digunakan.<br>
![image](https://github.com/user-attachments/assets/bf9be623-fbc5-4923-9149-4a0ba4929e5f)
![image](https://github.com/user-attachments/assets/0eabd0a9-f7fa-4fc5-b1cd-d7e8ee281042)


## Mengecek Command Secara Keseluruhan
Tahap untuk mengecek command secara keseluruhan sebagai berikut :
1. Klik kanan pada kelas ```Command```
2. Klik ```new Command(String forstWord, String secondWord)``` untuk membuat objek baru
3. Ketikan 2 comand. Contoh comand pertama adalah ```"go"``` dan comand kedua adalah ```"west"```
4. Klik ```oke```
5. Klik kanan pada objek ```Command``` pada object bench berwarna merah
6. Terdapat 4 method untuk mengecek command<br>
![image](https://github.com/user-attachments/assets/97dcdf08-5c42-465a-beb5-2aff660cd040)

## Mendapatkan Informasi dari Pengguna
Tahap untuk mendapatkan informasi dari pengguna sebagai berikut :
1. Klik kanan pada kelas ```Parser```
2. Klik ```new Parser()``` untuk membuat objek baru
3. Klik ```oke```
4. Klik kanan pada objek ```Parser``` pada object bench berwarna merah
5. Klik method ```Command getCommand()```
6. Ketikan command pada terminal<br>
   ![image](https://github.com/user-attachments/assets/e9739ee9-fa80-4fd7-973d-a8b12f02783e)
   Lalu ```Enter```
7. Klik ```Command```
8. Akan muncul hasil. Kata perintah adalah ```go``` dan kata kedua adalah ```west```. Sedangkan kata yang lain dianggap tidak dimengerti.<br>
![image](https://github.com/user-attachments/assets/05a91c9d-0a26-4770-9055-8b807af6e3b8)


