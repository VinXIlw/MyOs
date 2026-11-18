# Riwayat Pembaruan (Changelog) - MyOs

Semua informasi pembaruan aplikasi **MyOs** (`MyOs.exe`) dicatat di halaman ini.

---

<!-- CHANGELOG_START -->
## [v1.0.10] - 2026-11-18
- Perbaikan pencarian lirik (LyricsFetcher): menghindari lirik versi sensor/clean ('D-', 'b-', 'f***', dll.) dan otomatis memilih lirik lengkap tersinkron yang sama persis dengan Spotify
- Mendukung pemisahan nama artis kolaborasi dari Spotify saat mencocokkan lirik di LRCLIB

## [v1.0.9] - 2026-11-18
- Perombakan total tampilan Notch minimize ala iPhone Dynamic Island: ukuran tetap ringkas (138-216px) tanpa melebar, hanya menampilkan Live Activity penting (sampul lagu + equalizer warna adaptif, timer, notifikasi belum dibaca, dan baterai lemah <=20%)
- Status seperti Speaker Muted, Mikrofon Mati, Jangan Ganggu (DND), Mode Pesawat, dan Pengisian Daya kini hanya muncul sebagai popup Dynamic Island kompak saat berubah status

## [v1.0.8] - 2026-11-18
- Mengganti nama asisten AI menjadi Myku AI di seluruh antarmuka Notch
- Menambahkan dukungan multi-bahasa (Indonesia, English, Jepang, Mandarin, Korea, Spanyol) melalui tab Bahasa di Pengaturan dengan penyesuaian lebar tombol otomatis untuk setiap bahasa

## [v1.0.7] - 2026-11-18
- Perbaikan auto-resize lebar pil model AI sesuai panjang teks secara presisi agar tidak pernah saling menimpa
- Penyempurnaan tata letak panel Atur API: memindahkan badge penyedia ke status bar bawah, menyelaraskan kolom tombol kanan, dan merapikan tampilan chat

## [v1.0.6] - 2026-11-18
- AI seperti Cline: cukup tempel API Key apa saja, penyedia (Gemini, Claude, OpenAI, OpenRouter, Groq, DeepSeek, Grok, Mistral) terdeteksi otomatis dan daftar model langsung dimuat dari API tanpa memilih penyedia
- Dukungan langsung Anthropic Claude API (Sonnet, Opus, Haiku, dll.) serta OpenAI, xAI Grok, dan Mistral
- Daftar model kini 2 baris dengan halaman (tombol kiri/kanan), nama model ringkas, dan tidak lagi bertumpuk

## [v1.0.5] - 2026-11-18
- Perbaikan pemuatan foto profil pengirim chat dari URL CDN WhatsApp (https://) beserta cache memori per kontak
- Menambahkan tombol Sudah Dibaca pada popup notifikasi (Peek) agar popup bisa langsung ditutup dan ditandai sudah dibaca tanpa menunggu hilang sendiri

## [v1.0.4] - 2026-11-18
- Menampilkan foto profil pengirim chat (WhatsApp, Discord, Telegram, dll.) beserta lencana aplikasi pada kartu notifikasi, popup Peek, dan balas cepat
- Integrasi halaman AI multi-provider (Google AI Studio, OpenRouter, Groq, DeepSeek, Kustom) dengan pemuatan daftar model otomatis dari API
- Integrasi halaman Clipboard langsung dengan riwayat Clipboard Windows (Win + V)
- Akurasi lokasi cuaca ditingkatkan menggunakan Windows Location Service (Wi-Fi/GPS) + reverse geocoding
- Perbaikan crash Access Violation (0xc0000005) pada COM audio dan deteksi fullscreen palsu pada jendela maximize/overlay
- Penyempurnaan tata letak, ukuran teks, kesejajaran jam-tanggal header, dan halaman Pengaturan

## [v1.0.3] - 2026-11-10
- Animasi bersihkan semua notifikasi diperhalus dengan kecepatan proporsional
- Kliping dan batas gestur geser kartu diperketat agar tidak meluber keluar notch
- Jarak teks tindakan geser lebih lega di tengah ruang tersibak
- Seluruh antarmuka Notch kini bersih dari karakter emoji
- Penyempurnaan responsivitas klik mouse dan penanganan fokus Notch
- Popup notifikasi langsung menutup saat tombol Buka ditekan

## [v1.0.2] - 2026-11-10
- Animasi geser saat pindah tab di Pengaturan (Umum / Warna / Tampilan)
- Pemilih warna kustom langsung di dalam notch (kotak warna, Hue, Alfa)
- Perbaikan: notch tidak lagi hilang selamanya setelah lama disembunyikan / setelah kunci layar atau sleep
- Perbaikan: aplikasi tidak lagi menutup sendiri saat terjadi error (dicatat ke %APPDATA%\NotchWin\error.log)
- Popup notifikasi jauh lebih cepat (deteksi tiap 5 ms, sebelumnya 1 detik)
- Auto-hide default 2 detik (pilihan 1 / 2 / 4 dtk)
- Notifikasi otomatis terhapus dari halaman Notifikasi setelah dibuka atau dibalas
- Teks di halaman Notifikasi lebih besar dan mudah dibaca

## [v1.0.1] - 2026-11-10
- Custom Warna Ditambahkan

## [v1.0.0] - 2026-11-09
- Rilis perdana aplikasi **MyOs** (`MyOs.exe`) untuk Windows 10/11.
- 8 halaman interaktif: Beranda (Jam & Cuaca), Musik (+ Lirik tersinkron LRCLIB), Notifikasi Windows (dengan fitur Balas cepat), Kalender, Tray File (Drag & Drop), Monitor Sistem (CPU/RAM/Jaringan/Disk/Baterai), Timer & Stopwatch, serta Clipboard lokal.
- Peek HUD otomatis untuk pergantian lagu, volume, kecerahan layar, status charger/baterai, Caps Lock, bahasa keyboard, jaringan, mode pesawat, Jangan Ganggu, speaker mute, dan mikrofon.
- Kustomisasi penuh warna tema (Solid & Gradasi) serta pengaturan ukuran notch dan sembunyi otomatis (auto-hide).
<!-- CHANGELOG_END -->
