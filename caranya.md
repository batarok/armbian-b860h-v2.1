## Alat dan bahan
- STB b860h v2.1
- mmc clas 10 4GB dan 8GB (yg 8GB bisa ganti pake flashdisk usb3)
- pc windows
- aplikasi usb burning tools
- aplikasi bootmaker & file uboot hg680p
- usb male to male
- FW android probox 2GB
- FW armbian
- aplikasi balenaetcher
- obeng +- (jika diperlukan untuk bongkar stb)

## Langkah buat STB FW ORI
1. Flash mmc dengan aplikasi bootmaker dan pilih uboot hg680p saat proses flash (tunggu sampai selesai)
2. Masukan mmc yang sudah di flash uboot hg680p ke stb
3. Tancapkan usb male ke pc (tidak tertancap ke stb)
4. Buka aplikasi usb burning tools
5. Tekan tombol power pada stb dan tancapkan usb male ke stb dan nanti akan terdeteksi <b>connection success</b>
   - Jika langkah 5 tidak berhasil berarti perlu bongkar stb untuk jumper pin
6. Setelah langkah 5 berhasil, load FW Probox ke aplikasi usb burning tools dan tunggu proses nya
7. Setelah berhasil load FW, hilangkan semua ceklist yg ada pada aplikasi usb burning tools dan klik start dan tunggu proses burning FW sampa selesai
   - Jika proses di atas mengalami error ram code brarti perlu kembali ke langkah 5 dengan cara jumper pin
