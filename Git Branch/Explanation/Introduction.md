Pengenalan Branching

- Saat hampir semua Version Control Sistem pasti memiliki fitur branching
- Branching artinya kita membuat timeline baru yang berbeda dari timeline utama
- Biasanya timeline utama atau branch utama disebut dengan master atau main
- Saat kita membuat timeline branch baru, semua perubahan yang kita lakukan tidak akan merusak timeline branch utama
- Oleh karena itu fitur branching itu sangat cocok digunakan misal ketika akan menambah fitur di
  Repository, sehingga jika ternyata bermasalah, kita tinggal mudah pindah ke timeline utama
- Tidak ada batasan berapa banyak branch yang bisa kita buat di Git, kita bisa bebas membuat
  branch dari branch manapun

Kapan Branch Digunakan ?
- Dalam pengembangan perangkat lunak, Branch biasanya dibuat ketika kita akan menambah fitur baru
- Fitur baru akan ditambahkan di branch baru, sehingga kita bisa bebas menambah fitur tanpa takut
  melakukan kesalahan di branch utama
- Ketika fitur sudah siap, kita bisa melakukan merge(menggabungakan) branch fitur baru tersebut 
  ke branch utama