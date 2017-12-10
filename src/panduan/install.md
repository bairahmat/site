---
title: Instalasi BantOS
type: panduan
order: 102
---


## Panduan Instalasi BantOS
Ada 2 cara yang bisa kita lakukan untuk instalisasi BantOS pada perangkat PC dan Laptop,yaitu:
Untuk menginstall BantOS pada perangkat kita dapat mengikuti 2 cara yaitu :
- Melalui _bootable_ flashdisk
- Melalui _bootable_ CD
Jika kita menggunakan CD, kita dapat melewatkan bagian **Unduh ISO BantOS** dan **Membuat bootable ISO BantOS ke Flashdisk**.

### Unduh BantOS
ISO BantOS dapat diunduh [Belum dapat di Unduh](http://linux.dev.bantenprov/iso/BantOS/).

### Proses Instalasi BantOS
1. Setelah Anda memiliki CD/DVD instaler atau _bootable_ BantOS, pastikan kita  menghubungkan media tersebut ke perangkat kita.
2. Restart perangkat Anda untuk memulai proses instalasi BantOS.
3. Arahkan _booting option_ ke perangkat _bootable_. Anda dapat masuk ke BIOS kemudian ubah mode BIOS ke `Legacy` (jika sebelumnya menggunakan mode `UEFI/EFI`).
4. Selanjutnya ubah boot priority ke urutan pertama jika anda menggunakan flashdisk atau ubah boot priority CD(): ke urutan pertama jika Anda menggunakan CD.
5. Simpan pengaturan pada BIOS Anda kemudian restart.
6. Tunggu beberapa saat sampai muncul menu seperti berikut :
   ![menu-install](/src/images/install-id.png)
7. Pilih `Coba BantOS` untuk mencoba atau `Pasang BantOS` untuk langsung menginstall. Apabila Anda memilih Install BantOS Anda dapat melewati langkah ke 6 dan 7.
   Anda dapat mencoba terlebih dahulu fitur-fitur yang terdapat pada BantOS sebelum menginstallnya. Tetapi jika Anda langsung ingin memasang BantOS, klik icon _Pasang BantOS_ pada desktop.
8. Selanjutnya Anda diminta untuk memilih untuk mendownload _software third party_ atau tidak. Klik ok untuk lanjut.
    ![preparing](/src/images/install-bantos-2.png)
12. Selanjutnya anda diminta untuk memilih Jenis Instalasi sebagai berikut :
    - _Hapus disk dan Install BantOS_
      Pilihan ini menghapus semua Disk Anda. Pilihan ini dikhususkan bagi Anda yang tidak ingin dualboot, karena pilihan ini akan menghapus semua OS dan data yang ada.
    - _Sesuatu yang lain_
      Pilihan ini dikhususkan bagi anda yang ingin dualboot. Karena didalam pilihan ini Anda dapat mengatur partisi yang telah kita buat diawal tadi.
    ![instalaltion](/src/images/install-bantos-3.png)
    Pilih something else lalu klik ok.
13. Anda akan mendapatkan antarmuka seperti berikut :
    ![partiton_1](/src/images/install-bantos-4.png)
    Seperti yang anda lihat pada antarmuka tersebut, terdapat satu buah partisi yang anda telah buat pada langkah sebelumnya yaitu `/dev/sda` yang berukuran 90GB. Sebagai informasi nama partisi dapat berbeda antara tutorial ini dan perangkat anda.
14. Selanjutnya ubah tipe partisi `/dev/sda` dengan cara klik tombol change. Atur menjadi `ext4`, format partisi dan juga arahkan mount point ke `/`. Klik OK untuk lanjut.
    ![Partition_2](https://cloud.githubusercontent.com/assets/22718275/23686049/f5030230-03d9-11e7-8834-7ecac4b9b6bb.png)
    ![partition_3](https://cloud.githubusercontent.com/assets/22718275/23686061/03f969f0-03da-11e7-8bda-eb56c7c8cf04.png)
15. Selanjutnya ubah tipe partisi `/dev/sda5` dengan cara klik tombol change. Atur menjadi `swap area`. Klik OK untuk lanjut.
    ![Partition_4](https://cloud.githubusercontent.com/assets/22718275/23686081/1fbf6266-03da-11e7-8daa-4a60c06703e5.png)
    ![partition_5](https://cloud.githubusercontent.com/assets/22718275/23686146/6dbf052a-03da-11e7-85e3-e844b273f694.png)
16. Selanjutnya akan tampil persetujuan sebagai berikut :
    ![Partition_6](https://cloud.githubusercontent.com/assets/22718275/23686161/857a51e2-03da-11e7-8011-a9fb063761b4.png)
    Klik continue untuk lanjut.
17. Selanjutnya Anda diminta untuk memilih waktu dan tempat.
    ![time-and-region](https://cloud.githubusercontent.com/assets/22718275/23686187/a58ca03e-03da-11e7-827a-01f86abe8ec3.png)
18. Selanjutnya Anda diminta untuk memilih tipe keyboard.
    ![keyboard](https://cloud.githubusercontent.com/assets/22718275/23686208/b682f4ce-03da-11e7-8dcb-85c8ef2cbbad.png)
19. Selanjutnya Anda diminta untuk mengisi data diri.
    ![whoru](https://cloud.githubusercontent.com/assets/22718275/23686238/d5fdd5e4-03da-11e7-8387-626587c4ede8.png)
20. Tunggu beberapa saat proses sampai proses instalasi tealinuxos selesai.
    ![installaltion](https://cloud.githubusercontent.com/assets/22718275/23686286/31ab73ec-03db-11e7-8292-173401c6851a.png)
21. Restart dan nikmati tealinuxos.
    ![success](https://cloud.githubusercontent.com/assets/22718275/23686381/df3fda20-03db-11e7-9ee1-a811f1646f36.png)
