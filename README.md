Selamat datang di Project The Eyes, Saya **Hardiyanto**, terima kasih untuk meluangkan waktu datang ke sini.

# The Eyes

---

#### Pengantar

The Eyes adalah sebuah alat sadap yang dapat digunakan oleh para orang tua untuk menyadap **ponsel Android** milik anak anaknya yang dibawah umur (atau tergantung keinginan) dengan tujuan agar orang tua : 

1. Memiliki hak akses penuh monitoring terhadap kegiatan kegiatan anaknya tanpa diketahui. 

2. Jika terjadi hal hal yang tidak diinginkan misalnya anak hilang, terjadi tindakan kriminal terhadap anak ataupun hal sejenisnya orang tua setidaknya sudah memiliki data data aktifitas aktifitas yang mungkin saja dapat membantu menyingkap masalah tersebut.

Walaupun diperuntukan untuk memonitoring lewat belakang (*sebagai trojan payload*), alat sadap ini juga memiliki kapabilitas seperti

1. GPS Logging (mengetahui catatn lokasi dimana keberadaan anak berdasarkan posisi perangat)

2. Melakukan rekaman lewat Mic

3. Melihat daftar kontak

4. Melihat catatan rekam SMS

5. Melihat catatan panggilan ke luar masuk

6. Melihat aplikasi apa saja yang terinstall

7. Melihat semua file termasuk file unduhan, termasuk di dalamnya file file gambar dan backup pesan instan seperti WhatsApp atau Telegram

8. Penyadapan terhadap banyak ponsel pintar sekaligus (karena arsitektur client-server)

#### Teknologi

The Eyes menggunakan basis kode *L3Mon* https://github.com/D3VL/L3MON sebuah alat sadap berbasis cloud yang menggunakan web sebagai antar muka nya yang bersifat client server dan ditulis menggunakan bahas pemprograman Java dan Node.js. 

#### Monitoring

Secara default The Eyes digunakan untuk menyadap ponsel anak yang sama sama terkoneksi dengan internet di rumah (misal terkoneksi ke dalam jaringan Wifi yang sama). The Eyes tidak otomatis melakukan pencatatan pencatatan di dalam ponsel anak, tugas orang tua lah yang harus mengumpulkan data ponsel anak tersebut melalui server dan antar muka web lokal. 

#### Installasi

The Eyes tidak menyediakan paket installasi run out of the box, tetapi untuk pengguna umum, anda dapat mengunduh sistem penuhnya dalam bentuk VirtualBox Image yang dapat dijalankan dalam desktop komputer/laptop dengan sistem operasi Windows, Linux dan Macintosh, untuk ini diperlukan aplikasi VirtualBox yang dapat diunduh di website Oracle VirtualBox,  https://www.virtualbox.org/
