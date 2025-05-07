# Tutorial Modul Pemrograman Lanjut (2024/2025)

<details> <summary>a. What is AMQP?</summary>
AMQP (Advanced Message Queuing Protocol) adalah protokol open standard berbasis wire-level yang digunakan untuk komunikasi message-oriented middleware. AMQP memungkinkan sistem yang berbeda untuk saling bertukar pesan secara andal, aman, dan terstruktur melalui message broker seperti RabbitMQ. Dengan AMQP, kita bisa membangun sistem terdistribusi yang loosely-coupled, di mana produsen dan konsumen pesan tidak perlu saling mengetahui secara langsung satu sama lain. Hal ini sangat mendukung pola arsitektur Event-Driven karena komunikasi dilakukan melalui event yang dikirim sebagai pesan ke message broker.

</details> <details> <summary>b. Apa arti dari guest:guest@localhost:5672?</summary>
guest:guest@localhost:5672 adalah URI (Uniform Resource Identifier) untuk koneksi ke server RabbitMQ menggunakan protokol AMQP. Kata pertama guest adalah username, dan guest kedua adalah password. Bagian localhost menunjukkan bahwa RabbitMQ dijalankan secara lokal di komputer pengguna, dan 5672 adalah port default yang digunakan RabbitMQ untuk komunikasi AMQP. Jadi, string ini artinya kita mencoba mengakses broker RabbitMQ yang berjalan di komputer lokal, menggunakan kredensial default guest untuk otentikasi.

</details>