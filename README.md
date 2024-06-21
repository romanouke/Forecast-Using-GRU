## Final Project Studi Independent di Startup Campus Batch 6
Seluruh dataset & hasil project hanya digunakan sebagai sarana pembelajaran & tidak mencerminkan nilai yang sebenarnya. Mohon tidak menjadikan **hasil** project ini sebagai referensi/rekomendasi.
## BBRI = Bank Bintang Raya Indonesia dan BBTN = Bank Tabungan Nuswantara
## Kenapa menggunakan GRU?
Bayangkan kamu memiliki sebuah buku catatan di mana kamu mencatat informasi penting dari hari ke hari. Setiap halaman dalam buku catatan ini adalah seperti "memori" harianmu. Sekarang, bagaimana kamu memutuskan informasi apa yang perlu dicatat dan informasi apa yang tidak terlalu penting?

Apa itu GRU?
Gated Recurrent Unit (GRU) adalah seperti sebuah buku catatan pintar yang bisa membantu kamu memutuskan informasi apa yang harus disimpan dan informasi apa yang harus dilupakan.

Bagaimana GRU Bekerja?
GRU memiliki dua mekanisme utama, atau "gerbang," yang membantu dalam pengambilan keputusan ini:
Gerbang Pembaruan (Update Gate)
Gerbang Pengaturan Ulang (Reset Gate)
1. Gerbang Pembaruan (Update Gate)
Bayangkan gerbang pembaruan seperti filter yang memutuskan informasi apa dari hari sebelumnya yang perlu kamu bawa ke hari berikutnya. Misalnya, jika kamu belajar sesuatu yang sangat penting kemarin, gerbang ini akan memastikan kamu tidak melupakannya hari ini.

Contoh: Jika kamu belajar cara memasak makanan baru kemarin, kamu ingin memastikan bahwa informasi ini tetap ada di memori kamu hari ini.

2. Gerbang Pengaturan Ulang (Reset Gate)
Gerbang pengaturan ulang adalah seperti tombol reset yang membantu kamu memutuskan seberapa banyak informasi lama yang perlu dilupakan atau digantikan dengan informasi baru. Ini berguna ketika kamu ingin belajar sesuatu yang baru dan mungkin tidak relevan dengan apa yang kamu ketahui sebelumnya.

Contoh: Jika kamu belajar resep baru yang lebih baik hari ini, kamu mungkin ingin melupakan cara lama memasak yang tidak efisien.
Bagaimana Kedua Gerbang Ini Bekerja Bersama?
Setiap hari, ketika informasi baru datang, gerbang pembaruan akan memutuskan apakah informasi lama masih relevan dan harus disimpan. Sementara itu, gerbang pengaturan ulang akan melihat apakah informasi lama perlu diganti dengan yang baru.
Dengan cara ini, GRU bisa belajar dari data urutan (seperti kalimat dalam bahasa, atau kejadian dalam waktu) dengan lebih efisien dan efektif. GRU memastikan bahwa informasi penting dari masa lalu tidak hilang dan informasi yang tidak lagi relevan dapat dilupakan.

Mengapa GRU Penting?
GRU sangat berguna dalam aplikasi seperti penerjemahan bahasa, analisis sentimen, dan prediksi waktu seri (seperti memprediksi harga saham). Mereka membantu komputer memahami dan memproses data yang datang dalam urutan, seperti kata-kata dalam sebuah kalimat atau kejadian-kejadian dalam waktu.
Jadi, secara sederhana, GRU adalah seperti buku catatan pintar yang tahu bagaimana menyimpan informasi penting dan melupakan yang tidak penting, sehingga dapat belajar dan memproses informasi secara lebih efektif.
