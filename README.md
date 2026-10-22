# Red Alert: Modern Era

Mod OpenRA untuk Red Alert yang membawa perang modern: 180+ unit dari masa kini, mulai dari infanteri, tank, artileri, MLRS, sampai kapal induk nuklir. Semua sprite dibuat prosedural dengan 8 arah hadap, jadi unit terlihat benar dari segala sudut.

Mod ini dibangun di atas engine [OpenRA](https://www.openra.net), dibundel sebagai fork dengan modifikasi langsung di mod `ra`. EA tidak terlibat dan tidak mendukung proyek ini.

## Isi mod

- **Kendaraan darat**: T-14 Armata, T-15, Boxer, LAV-25, JLTV, BTR-82A, dan puluhan lainnya
- **Artileri**: M109A7 Paladin, PzH 2000, CAESAR, Archer, K9, M142 HIMARS, M270, PHL-16, dan lainnya
- **Pertahanan udara**: Pantsir-M2, HQ-9FE, HQ-16FE, Tunguska-M1, dengan rudal SAM baru
- **Kapal**: kapal induk CVN/LHD/LHA, fregat FREMM/Akizuki/Constellation, korvet, kapal selam
- **Helikopter**: Apache, AH-1Z, Ka-52, Mi-24, Blackhawk dengan animasi rotor
- **Sistem baru**: ekonomi gaya WC4, kapal perang nuklir, serangan udara dari carrier, dinding beton dan parit yang bisa terhubung otomatis, 6 unit hero dengan aura

Ada juga peta showcase berisi seluruh 186 unit modern kalau ingin lihat semuanya sekali jalan.

## Cara main

1. Clone repo ini, atau unduh rilis AppImage/Windows dari halaman releases.
2. Jalankan `./launch-game.sh` (Linux/macOS) atau `launch-game.cmd` (Windows).
3. Pilih mod Red Alert seperti biasa; unit modern sudah ada di dalamnya.

## Dari source

```bash
./configure-system-libraries.sh
./make.cmd dependencies   # Windows, atau: make dependencies
./make.cmd all            # atau: make all
./launch-game.cmd
```

Panduan lengkap compile ada di [INSTALL.md](INSTALL.md).

## Kredit

- Engine dan aset dasar: [OpenRA](https://github.com/OpenRA/OpenRA) (GPL-3.0, lihat [COPYING](COPYING))
- Sprite unit modern: dibuat dengan bantuan AI art lalu dirapikan manual per frame

## Lisensi

Copyright (c) OpenRA Developers and Contributors. Bagian mod mengikuti lisensi yang sama, GPL-3.0. Detail di [COPYING](COPYING).
