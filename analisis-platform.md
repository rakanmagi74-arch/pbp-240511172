# Analisis Komparatif Platform: Web, Desktop, dan Mobile

## Tabel Perbandingan

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| **Bahasa utama** | HTML, CSS, JavaScript/TypeScript (frontend); backend bisa PHP, Node.js, Python, Java, Go | C++, C#, Java, Python; lintas platform dengan Electron (JavaScript), Qt (C++), atau .NET MAUI/WPF (C#) | Android: Kotlin, Java. iOS: Swift, Objective-C. Lintas platform: Dart (Flutter), JavaScript/TypeScript (React Native) |
| **Arsitektur** | Client-server: browser (client) mengirim request HTTP ke server, lalu server mengirim respons. Umumnya berlapis (frontend, backend/API, database) | Aplikasi berjalan langsung di sistem operasi lokal dan mengakses sumber daya perangkat (file, memori, perangkat keras). Umumnya monolitik/standalone, dapat juga client-server untuk data online | Aplikasi berjalan di OS mobile dalam sandbox, sering berpola client-server dengan backend API (REST/GraphQL). Pola umum: MVC, MVVM, Clean Architecture |
| **Cara distribusi** | Diakses lewat URL di browser tanpa instalasi; deploy cukup ke server/hosting/cloud. Pembaruan langsung berlaku bagi semua pengguna | Diunduh dan dipasang lewat installer (.exe, .msi, .dmg, .deb) atau toko aplikasi (Microsoft Store, Mac App Store); pembaruan lewat auto-update atau instal ulang | Melalui toko aplikasi resmi (Google Play Store, Apple App Store) dengan proses review; dapat juga lewat APK/sideload di Android. Pembaruan lewat toko aplikasi |
| **Keunggulan** | Lintas platform (cukup browser); tidak perlu instalasi; pembaruan terpusat dan instan; jangkauan pengguna luas; biaya distribusi rendah | Performa tinggi; akses penuh ke perangkat keras dan file sistem; dapat berjalan offline; cocok untuk tugas berat (editing, pemrograman, desain) | Mobilitas tinggi; akses sensor (kamera, GPS, akselerometer); notifikasi push; pengalaman pengguna personal; jangkauan pengguna sangat besar |
| **Keterbatasan** | Bergantung pada koneksi internet; performa dan akses perangkat keras terbatas oleh browser; perbedaan perilaku antar browser; risiko keamanan web (XSS, CSRF) | Perlu instalasi dan pembaruan per perangkat; sering harus dibuat per OS (Windows/macOS/Linux); jangkauan terbatas pada pengguna komputer | Layar kecil dan sumber daya terbatas (baterai, memori); fragmentasi perangkat dan versi OS (Android); proses review dan kebijakan toko aplikasi; biaya akun developer |
| **Contoh aplikasi** | Google Docs, Tokopedia (web), Trello, Gmail, Wikipedia | Microsoft Word, Visual Studio Code, Adobe Photoshop, VLC Media Player, Spotify Desktop | WhatsApp, Gojek, Instagram, Google Maps, Duolingo |

## Referensi

1. Mozilla Developer Network. *Learn Web Development* dan *Web Technology for Developers*. MDN Web Docs. https://developer.mozilla.org/
2. Google. *Android Developers: Platform Architecture & App Fundamentals*. https://developer.android.com/guide
3. OpenJS Foundation. *Electron Documentation: Introduction*. https://www.electronjs.org/docs/latest
4. Richards, M. & Ford, N. (2020). *Fundamentals of Software Architecture: An Engineering Approach*. O'Reilly Media.