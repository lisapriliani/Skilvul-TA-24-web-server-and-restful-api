1. Apa perbedaan antara static web server dan dynamic web server?
2. Jelaskan arsitektur static site dan dynamic site
3. Apa saja yang dapat kita buat pada sisi server?
4. Mohon jelaskan apa itu RESTful?
5. Apa saja jenis HTTP verbs yang ada (jelaskan fungsinya masing-masing)
6. Apa fungsi dari Response Codes?

Jawab

1. Static web server menyimpan data statis atau tetap yang tidak dapat diupdate,
   sedangkan dinamic web server menyimpan dan melayani data yang dapat berubah-ubah atau dapat dimodifikasi
2. Arsitektur static web server :

   - Server side : server side akan menyediakan data yang diminta berupa data html, css, javascript,
   - Web server : webserver akan menjadi penghubung antara serverside dan client side untuk menyimpan dan mengirimkan data
   - Client side : client side merequest data ke webserver, lalu webserver akan mengirimkan respon balik ke client side

   Arsitektur dynamic web server :

   - Server side
   - Web server
   - Client side
   - Web Application
   - Database
     Client side akan mengirimkan request data ke webserver, kemudian web server akan meminta data melalui web application yang terhubung ke database, web application akan merespon dan mengirimkannya kembali ke webserver lalu diteruskan ke client side.

3. Pada server side kita dapat menyimpan dan mengirimkan informasi, dapat melakukan kontrol akses ke konten, menyimpan informasi sesi/status, melakukan analisis data.

4. RESTFUL adalah web services yang menerapkan arsitektur REST(REpresentational State Transfer) adalah standar dalam komunikasi untuk pertukaran data

5. Terdapat 4 basic http verbs di REST sistem :

   - GET : untuk mengirimkan request data berdasarkan id
   - POST : mendeklarasikan sebuah data / mendaftarkan data
   - PUT : memperbarui data berdasarkan id
   - DELETE : menghapus data berdasarkan id

6. Response code berfungsi sebagai tanggapan dari sebuah web server untuk menunjukan status dari request yang dikirimkan
