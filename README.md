<!-- filepath: c:\tutorial9\subscriber\README.md -->
## Tanya Jawab AMQP

**a. Apa itu AMQP?**

Advanced Message Queuing Protocol (AMQP) adalah protokol open standard untuk message-oriented middleware (MOM). Protokol ini dirancang untuk mengirimkan pesan bisnis antar aplikasi atau organisasi. AMQP memungkinkan ekosistem komunikasi multi-vendor yang mumpuni dan terkondisifikasi yang dapat mengubah cara bisnis dilakukan di internet dan cloud. Fitur utama AMQP adalah keamanan, reliability, interoperability, dan merupakan protokol standard dan open.

**b. Apa artinya guest:guest@localhost:5672 , apa itu guest yang pertama, dan apa itu guest yang kedua, dan untuk apa localhost:5672 itu?**

String ini adalah URI koneksi AMQP:
- `guest` (yang pertama): Ini adalah nama pengguna yang digunakan untuk autentikasi dengan broker AMQP.
- `guest` (yang kedua): Ini adalah password yang terkait dengan nama pengguna untuk autentikasi.
- `localhost`: Ini adalah host tempat broker AMQP berjalan. `localhost` biasanya berarti mesin yang sama tempat aplikasi klien berjalan, alias mesin lokal.
- `5672`: Ini adalah nomor port tempat broker AMQP listening koneksi. Port 5672 adalah nomor port yang ditetapkan IANA untuk AMQP.

Jadi, `guest:guest@localhost:5672` berarti klien mencoba terhubung ke broker AMQP yang berjalan di mesin lokal, pada port 5672, menggunakan nama pengguna "guest" dan password "guest".
