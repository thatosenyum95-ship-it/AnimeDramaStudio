# AnimeDramaStudio 3D

Studio video anime 3D sederhana yang berjalan di browser, tanpa AI atau API AI. Menggunakan Three.js dari CDN untuk merender karakter dan lingkungan 3D berbasis bentuk geometris.

## Fitur
- Karakter 3D sederhana: Aisyah berhijab, Haru, dan Miko si kucing.
- Lingkungan 3D: taman sakura, ruang kelas, kota malam, dan bukit senja.
- Animasi dasar: gerak lembut, berbicara, melompat kecil, melambaikan tangan, atau diam.
- Adegan multi-scene: tambah, hapus, duplikat, ubah urutan, durasi, dialog, dan subtitle.
- Putar dialog menggunakan Text-to-Speech bawaan browser.
- Unggah musik atau rekaman narasi.
- Ekspor urutan adegan melalui MediaRecorder. Format MP4/WebM tergantung dukungan browser/perangkat.
- Simpan dan buka proyek JSON; putar sudut kamera dengan menyeret pratinjau.

## Buka website
https://thatosenyum95-ship-it.github.io/AnimeDramaStudio/

## Catatan
- Tidak menggunakan AI atau API AI. Model karakter dibangun dari bentuk geometris Three.js; ini merupakan model 3D sederhana, bukan model anime profesional hasil pemodelan/rigging.
- Three.js dimuat dari CDN, sehingga browser perlu terhubung ke internet.
- Perangkat perlu mendukung WebGL. Jika layar 3D kosong, coba Chrome terbaru dan periksa apakah WebGL aktif.
- TTS digunakan untuk pratinjau saja; untuk suara yang masuk ke video, unggah rekaman narasi atau musik.
- Ekspor video bergantung pada dukungan MediaRecorder dan format yang disediakan browser. WebM lebih umum; MP4 tidak tersedia di semua perangkat.
- File proyek JSON menyimpan pengaturan dan dialog, bukan file audio. Pilih kembali file audio setelah membuka proyek.
- Pemrosesan proyek dilakukan di browser; tidak ada AI backend.
