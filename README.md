NAMA : FARDHO ZURRAHMAN
NIM  : 1237050148 / C
TUGAS: UTS MATA KULIAH PENGEMBANGAN APLIKASI MOBILE

![WhatsApp Image 2025-10-31 at 19 47 55_ed01e34c](https://github.com/user-attachments/assets/a276eb6f-6e0d-4831-aada-fa3197fc7f10)
![WhatsApp Image 2025-10-31 at 19 47 55_02e9fab6](https://github.com/user-attachments/assets/49ca47cf-c6d2-44c4-a5d2-664dc798f42a)
![WhatsApp Image 2025-10-31 at 19 47 56_7bc0126c](https://github.com/user-attachments/assets/5ccbd4eb-3db5-41a0-a017-6d8b4f50cd22)
![WhatsApp Image 2025-10-31 at 19 47 56_8a01aad7](https://github.com/user-attachments/assets/bb8b154b-f5e1-4d6b-99e3-27ca556e4fa3)
![WhatsApp Image 2025-10-31 at 19 47 56_626e7685](https://github.com/user-attachments/assets/cddbe15c-2db1-4952-a546-cdf9501356ff)
![WhatsApp Image 2025-10-31 at 19 47 55_da1a8ab2](https://github.com/user-attachments/assets/044a35fc-54ae-4536-b4ea-14e6b1795816)
<img width="543" height="1181" alt="WhatsApp Image 2025-10-31 at 19 47 55_02e9fab69" src="https://github.com/user-attachments/assets/e0a4b332-1e62-430d-ad61-e0d79e7e249e" />
![WhatsApp Image 2025-10-31 at 19 47 54_18a1be15](https://github.com/user-attachments/assets/fca037fb-e45b-4ae7-bc23-07ff18e3bb23)

PENJELASAN PROGRAM APLIKASI KOTLIN :

Halaman 1 – Start Now
Halaman pertama berfungsi sebagai tampilan pembuka aplikasi “MesanMakanan”. Pada halaman ini, pengguna akan disambut dengan desain sederhana yang menampilkan tombol “Start Now” di bagian tengah layar. Tombol ini menjadi pintu masuk utama ke seluruh sistem aplikasi. Konsep halaman ini dibuat agar pengguna langsung memahami bahwa langkah pertama untuk memulai pemesanan makanan adalah dengan menekan tombol tersebut. Dari segi UX (User Experience), halaman ini berfungsi sebagai transisi lembut menuju halaman berikutnya dengan nuansa yang bersih, minimalis, dan mudah digunakan.

Halaman 2 – Sign Up (Register / Login)
Halaman kedua berisi dua tombol utama yaitu “Register” dan “Login”. Tujuan halaman ini adalah memberikan pilihan kepada pengguna apakah ingin membuat akun baru atau masuk menggunakan akun yang sudah ada. Penempatan tombol dibuat sejajar dan terpusat agar navigasi mudah dijangkau. Di atas tombol terdapat teks “Sign up” dan deskripsi singkat aplikasi seperti “Unlock the secrets & predict your cycle with the most intuitive cycle tracking app”, namun disesuaikan untuk konteks aplikasi makanan agar terlihat profesional dan menarik. Halaman ini berperan sebagai gerbang autentikasi sebelum pengguna dapat mengakses fitur utama pemesanan.

Halaman 3 – Login (Input Username dan Password)
Halaman ketiga digunakan untuk proses login pengguna. Pada halaman ini terdapat dua kolom input yaitu Username dan Password, serta tombol Login di bawahnya. Pengguna yang sudah terdaftar dapat mengisi data dengan benar untuk masuk ke akun mereka. Validasi sederhana biasanya diterapkan agar username dan password tidak kosong sebelum menekan tombol login. Desainnya sederhana dan rapi, dengan fokus utama pada fungsionalitas agar pengguna bisa mengakses menu tanpa kebingungan. Setelah berhasil login, pengguna akan diarahkan ke halaman utama pemilihan menu makanan.

Halaman 4 – Register (Input Nama Lengkap, Username, dan Password)
Halaman keempat berfungsi untuk pendaftaran akun baru. Pengguna baru diminta mengisi Nama Lengkap, Username, dan Password di tiga kolom input yang terpisah. Setelah semua data diisi, pengguna menekan tombol Register untuk menyimpan informasi ke dalam database atau sistem penyimpanan lokal. Desain halaman ini dibuat modern dan intuitif agar proses pendaftaran terasa cepat dan nyaman. Tombol register berwarna kontras (misalnya hitam dengan teks putih) untuk menonjolkan fungsi utamanya dan memberikan pengalaman visual yang kuat.

Halaman 5 – Pilihan Menu
Halaman ini menampilkan 10 pilihan menu makanan tradisional Indonesia, yaitu:

Mendoan, Nasi Menggono, Soto Kudus, Lontong Opor, Gudeg Jogja, Rawon, Pecel Madiun, Nasi Liwet Solo, Ayam Geprek, Tahu Campur. Setiap menu ditampilkan dalam bentuk daftar (ListView atau RecyclerView) dengan nama dan mungkin gambar kecil di sampingnya. Pengguna dapat memilih salah satu makanan untuk dipesan. Tujuan halaman ini adalah memberikan pengalaman memilih menu dengan tampilan yang menarik dan informatif. Halaman ini merupakan inti dari aplikasi karena menampilkan produk yang ditawarkan.

Halaman 6 – Info Pesanan Saya
Halaman ini menampilkan informasi pesanan yang dipilih pengguna, misalnya “Pesanan Anda: Mendoan”. Data diambil dari pilihan sebelumnya di halaman menu. Tujuan halaman ini adalah memberikan konfirmasi sementara kepada pengguna mengenai makanan yang telah dipilih sebelum mereka melanjutkan ke proses pengiriman. Desainnya sederhana, berisi teks konfirmasi dan tombol “Lanjutkan” untuk menuju ke halaman pengisian alamat. Dengan adanya halaman ini, pengguna merasa lebih yakin terhadap pesanan yang mereka buat.

Halaman 7 – Alamat Pengiriman
Pada halaman ini, pengguna diminta mengisi Nama Lengkap, Username, dan Patokan Alamat tempat pengiriman makanan. Kolom input disusun vertikal dan rapi agar mudah diisi. Fungsi halaman ini adalah mengumpulkan data pengiriman agar pesanan dapat dikirimkan ke lokasi yang benar. Validasi data dilakukan untuk memastikan alamat tidak kosong. Halaman ini merupakan bagian penting dari proses transaksi karena berhubungan langsung dengan layanan pengantaran makanan ke pelanggan.

Halaman 8 – Ucapan Terima Kasih
Halaman terakhir berisi teks ucapan terima kasih kepada pengguna setelah mereka menyelesaikan pemesanan. Misalnya:
“Terima kasih telah memesan di MesanMakanan! Pesanan Anda sedang diproses dan akan segera dikirim.”
Halaman ini berfungsi sebagai penutup proses pemesanan sekaligus bentuk komunikasi positif dari aplikasi kepada pengguna. Tampilan didesain dengan tone warna lembut dan tulisan tegas agar meninggalkan kesan menyenangkan. Tombol tambahan seperti “Kembali ke Beranda” bisa ditambahkan untuk memudahkan pengguna kembali ke halaman awal jika ingin memesan lagi.
