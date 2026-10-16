# AnimeDramaStudio

Studio pembuat video anime 2D sederhana yang berjalan di browser, tanpa AI atau API AI.

## Fitur saat ini
- Pilih karakter vektor bawaan: Aisyah berhijab, Haru, atau Miko si kucing.
- Pilih empat latar ilustratif: taman sakura, ruang kelas, kota malam, dan senja.
- Susun beberapa adegan, pilih karakter/latar/gerakan, atur durasi dan dialog setiap adegan.
- Putar pratinjau cerita dan subtitle.
- Putar dialog menggunakan Text-to-Speech bawaan browser (tersedia sesuai perangkat/bahasa).
- Unggah musik atau rekaman narasi.
- Ekspor urutan adegan menjadi video melalui MediaRecorder; format MP4 atau WebM bergantung pada dukungan browser.
- Simpan satu adegan sebagai PNG.
- Simpan dan buka susunan adegan melalui file proyek JSON.

## Jalankan
Buka `index.html` di browser atau gunakan GitHub Pages:
https://thatosenyum95-ship-it.github.io/AnimeDramaStudio/

## Catatan dan batasan
- Tidak menggunakan AI atau API AI. Karakter dan latar bawaan digambar sebagai ilustrasi vektor sederhana; pengguna belum dapat membuat gambar karakter baru secara otomatis.
- TTS dipakai untuk pratinjau dialog. Browser umumnya tidak menyediakan cara untuk merekam keluaran TTS ke file video, jadi unggah rekaman narasi jika suara dialog harus masuk ke hasil ekspor.
- Ekspor video memerlukan browser yang mendukung `canvas.captureStream` dan `MediaRecorder`. Format serta perekaman audio berbeda-beda menurut browser/perangkat. Coba Google Chrome terbaru jika ekspor tidak tersedia.
- Proyek JSON menyimpan teks dan pengaturan adegan, bukan file audio yang diunggah. Pilih kembali audio setelah membuka proyek.
- Data proyek tidak dikirim ke server; pemrosesan berlangsung di browser.
