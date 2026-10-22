# Praktikum AR/VR - Pertemuan 1
- Nama : Ridho Adinda Kusman
- NIM : 2309020108
- Link demo : https://github.com/ridoadinda855-coder/arvr-prak-2309020108
Project ini berisi scene WebXR pertama menggunakan A-Frame 1.7.1.
Jawaban 3 soal:
1. Alasan objek menggunakan nilai Z negatif agar berada di depan kamera dan langsung terlihat oleh pengguna saat scene dimuat. Jika menggunakan Z positif, objek akan berada di belakang kamera.
2. WebXR memerlukan HTTPS atau localhost demi keamanan privasi dan data pengguna.
Alasannya karena WebXR mengakses perangkat keras sensitif seperti kamera, mikrofon, sensor gerak, dan data spasial/lokasi secara real-time. Jika berjalan pada HTTP biasa, data tersebut rentan disadap atau dicuri oleh peretas melalui serangan Man-in-the-Middle (MitM).
Oleh karena itu, browser modern menetapkan standar keamanan di mana fitur WebXR hanya diizinkan pada koneksi terenkripsi (HTTPS) atau lingkungan pengembangan lokal (localhost).
3. Perbedaan ketiganya dianalogikan seperti membangun rumah:
-WebXR Device API: Sebagai pondasi & instalasi listrik/air (menghubungkan hardware VR/AR ke browser secara aman).
-Three.js: Sebagai kerangka & furnitur (pustaka JavaScript untuk membuat grafis 3D secara detail).
-A-Frame: Sebagai rumah siap huni (framework berbasis HTML yang membuat pembuatan 3D/VR menjadi sangat mudah tanpa koding JavaScript yang rumit).
