# SISTEM UKM-IK

<img src="https://img.shields.io/badge/by-riyanris-blue" /> <img src="https://img.shields.io/badge/license-MIT-green" />

<p align="center">
<img src="https://user-images.githubusercontent.com/28080686/87218775-0a0bd800-c380-11ea-9aba-624918d030cb.jpg" width="80%" alt="UKM-IK"/>
</p>

UKM Informatika dan Komputer adalah unit kegiatan mahasiswa yang memiliki tujuan penalaran ilmiah di bidang informatika dan komputer. Memiliki lebih dari 60 anggota aktif dan ratusan alumni. Bertempat di STMIK Akakom Yogyakarta.

## Memiliki beberapa fitur : 
- Responsive dan adaptive pada semua perangkat, telah di test pada PC, Laptop, Smartphone dan Tablet
- Judul, deskripsi dan konten yang dinamis
- youtube video embed dapat dirubah-rubah(dinamis)
- Multi Login untuk masing-masing halaman
- Kompres gambar sehingga tidak memberatkan sistem
- Export data berupa pdf dan excel
- Keamanan data dengan enkripsi(one way hash + salt)
- Menggunakan API GMap untuk alamat anggota, biar bisa lebih detail

## Menggunakan library : 
- Codeigniter v3.1.10
- Template Portal : Theme-Buskey
- Template Admin : AdminLte v3
- phpoffice/phpspreadsheet v1.10
- Twitter Bootstrap v4.3.1 
- SweetAlert2 v8.11.8
- Datatable v3.2.2
- icheckBootstrap v3.0.1
- Codeigniter RestAPI

## Sitemap Website

### Portal Anggota
  - Dashboard
  - Detail Data
    - Anggota dapat memperbarui data mereka
  - Ubah Password
    - Halaman untuk mengubah password
    
### Poertal Keanggotaan
  - Dashboard
  - Atur Anggota
    - Data anggota dapat dilihat berdasarkan periode masuk
    - Dapat menambah anggota secara manual
    - Ubah mengubah data anggota
    - Melihat detail masing masing anggota
  - Atur Pengurus
    - Data pengurus, baik aktif maupun demis dapat dilihat berdasar periode
    - Dapat Menambah pengurus periode tertentu
    - Dapat Mengubah Pengurus Di periode tertentu
    - Aktif/nonaktifkan pengurus(nonaktif artinya demis)//sistem pecat saya masih bingung

### Portal Rekrutmen
  - Dashboard
    - tombol aktif/non-aktifkan periode rekrutmen
    - menampilkan total rekrutmen baru di periode tersebut
    - menampilkan statistik pie chart(lulus dan tidak lulus)
    - menampilkan statistik line(dari 5 periode sebelumnya) yang daftar, lolos dan tidak lolos
  - Rekrutmen
    - data rekrutmen di periode tersebut, dapat di ubah sesuai periode yang dicari
    - dapat menambah rekrutmen
    - dapat mengubah data rekrutmen
    - tombol lunas dan belum lunas(jika lunas data akan masuk ke penilaian, jika belum lunas data dihapus dari penilaian) note: tidak ada istilah nyicil(mungkin bisa di tambahkan di update berikutnya)
  - Penilaian
    - data rekrutmen yang sudah lunas
    - 3 jenis nilai yaitu lk1, lk2 dan masa 3 bulan(bisa dikembangkan sistem penilaianya, nanti diubah di AD/ART)
    - status lulus dan tidak lulus. jika lulus data akan masuk ke migrasi anggota sekaligus terdaftar NRA yang belum final.
    - catatan keterangan masing2 rekrutmen(biasanya gini : tgl 13 April tidak masuk study club karena sakit, ijin ke siapa gitu. atau tidak mengikuti kegiatan xxx gitu)
  - Migrasi Anggota
    - data rekrutmen yang lulus.
    - disini bakal tercetak NRA(belum final) nomor nra yang tertera adalah urutan nomor berapa dia masuk ke sistem
    - keanggotaan harus check dengan teliti sebelum di kirim ke ketum
    - jika ketum menyetujui, data akan masuk ke table anggota
  - Laporan
    - menetak seluruh data rekrutmen
    - mencetak data rekrutmen per periode
    - mencetak data rekrutmen per periode yang lolos atau yang tidak lolos
    - mencetak statistik line chart dari periode ke periode
    - 

### Portal Website
  - Informasi Dasar
    - Disini dapat mengatur seperti nama organisasi, alamat, email, no telp dan masih banyak lagi
  - Informasi Lanjutan
    - Halaman mengatur pra kata di dalam website, seperti sambutan ketum waketum, tentang organisasi, sejarah dan lainya
  - Atur Gambar
    - Halaman mengatur gambar, seperti gambar ukuran kotak, landscape, background, banner dan lainya.

Contact developer : 
- https://riyanris.my.id#contact
- https://www.instagram.com/calon_imam__
- riyanrisky129@gmail.com 
