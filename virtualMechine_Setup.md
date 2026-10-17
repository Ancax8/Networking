<h1>VirtualMechine Setup</h1>
<p> Sekarang masuk ketahap installasi dan konfigurasi VirtualMechine, pada kali ini saya akan menggunakan virtualbox</p>

1. setalah melakukan installasi di tahap [awal](README.md) maka sekarang lanjut ke konfigurasinya
2. klik menu "New" untuk menabahkan file server yang akan kita buat
3. Tambahkan nama file kalian, disini sifatnya pembuatan namanya itu server apa yang kalian buat contoh debian maka nama yang dibuat ada unsur "deb"
4. vmFolder -> Lewat
5. ISO Image tambahkan dengan file yang sudah dibuat pada tahap [awal](README.md), klik yang "other" untuk membrowse di device masing masing
6. kemudian finish
   
<p>tahapan menambahkan file sudah, sekarang kita setting file yang sudah kita buat</p>

1. klik file yang kita buat kemudian klik menu "setting"
2. "general" -> buat ganti nama dll
3. "system" :
   - naikkan hardisk keatas dan optical kedua fungsinya agar bisa nge save setiap kita konfigurasi
   - base memory == penyimpanan, jika windows maka akan membutuhkan yang besar jika linux kecil cukup
   - processor, terkadang ada beberapa server yang meminta kita menggunakan beberapa fungsi cpu contoh default 1 sedangkan servernya minta 2
4. display - > buat ngubah tampilan display, contoh: scale dll
5. storage -> disini tempat kita menambahkan atau mengubah vdi
6. audio -> skip
7. network -> tempat ngatur interface (colokan):
   - bridge = auto nyambung ke perangkat device
   - internal network = dapat terhubung ke vm lain jika satu adapter
   - hostOnly = vm dan device berbeda ip
   - Nat = merubah network device kita menjadi ip public 
