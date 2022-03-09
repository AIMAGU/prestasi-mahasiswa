<h1 align="center">
    <a href="https://presma.uny.ac.id" title="PRESMA" target="_blank">
        <img src="https://presma.uny.ac.id/css/presma_2021/assets/images/logo/logo_presma_2021.png" alt="Sipresma"/>
    </a>
    <br>
    Sistem Informasi Prestasi Mahasiswa
    <hr>
    <a href="https://paypal.me/aimagu"
       title="Donate via Paypal" target="_blank">
        <img src="http://kartik-v.github.io/bootstrap-fileinput-samples/samples/donate.png" alt="Donate"/>
    </a>
</h1>

Aplikasi berbasis website menggunakan PHP dengan framework Yii versi 1.1.25 berfungsi untuk bank data Perguruan Tinggi dalam menjaring prestasi mahasiswa berupa Kejuaraan, Kegiatan Mahasiswa, Organisasi Mahasiswa, dan Sertifikat Keahlian.

> NOTE: Pastikan selalu memperbarui apabila terdapat pembaruan sistem.

## Paket Aplikasi

Pada aplikasi ini terdiri dari beberapa modul diantaranya:

- Modul Prestasi Mahasiswa 
- Modul Kegiatan Mahasiswa
- Modul Organisasi Mahasiswa
- Modul Skoring
- Modul Revisi 
- Modul Notifikasi
- Modul Manajemen Pengguna
- Modul Pengunjung

## Kebutuhan Sistem

Adapun kebutuhan sistem untuk menjalankan program ini diantaranya:
- Yii Framework versi 1.1.25 keatas
- Web server
- PostgreSQL / MySQL
- Bootstrap versi 4.0
- PHP versi 7 keatas

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/). Remember to refer to the [composer.json](https://github.com/kartik-v/yii2-widgets/blob/master/composer.json) for 
this extension's requirements and dependencies. 

### Install

Clone master

```
git clone https://github.com/AIMAGU/prestasi-mahasiswa.git
```

### Demo
You can see a [demonstration here](https://presma.uny.ac.id) on usage of these widgets with [documentation](https://presma.uny.ac.id/site-page.html?view=panduan) and examples.
<br>
```
[MAHASISWA]
Username: NIM
Password: NIM

[PETUGAS PRODI]
Username: NIP
Password: NIP

[PETUGAS FAKULTAS]
Username: NIP
Password: NIP

[PETUGAS PEMBINA UKM]
Username: NIP
Password: NIP

[SUPER ADMIN]
Username: admin
Password: admin
```
<br>(Mohon gunakan aplikasi demo ini dengan bijak, kami hanya ingin berbagi)

## Pengaturan

### Database
```php
//Path config/db.php
return [
    'class' => 'yii\db\Connection',
	'dsn' => 'pgsql:host=localhost;port=5433;dbname=db_name', //PostgreSQL
	//'dsn' => 'mysql:host=localhost;dbname=db_name', //MySQL
	'username' => 'username',
	'password' => 'password',
	'charset' => 'utf8',
];
```

## Screenshot Aplikasi
### Tampilan Desktop
<img src="https://github.com/AIMAGU/prestasi-mahasiswa/blob/main/screenshot/Screen%20Shot%202022-03-09%20at%2011.37.59.png" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/prestasi-mahasiswa/blob/main/screenshot/Screen%20Shot%202022-03-09%20at%2011.38.02.png" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/3.jpg" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/4.jpg" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/5.jpg" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/6.jpg" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/7.jpg" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/8.jpg" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/9.jpg" alt="Screenshot"/>

### Tampilan Mobile
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/mobile-1.jpeg" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/mobile-2.jpeg" alt="Screenshot"/>
<img src="https://github.com/AIMAGU/sipax/blob/master/screenshot/mobile-3.jpeg" alt="Screenshot"/>

## Database Installation
```
yii migrate
```

## Kontak
Kontak via [Whatsapp](https://api.whatsapp.com/send?phone=6285742974933&text=Saya%20tertarik%20untuk%20membeli%20aplikasi%20SIPRESMA)

## License
**SIPAX** is released under the BSD-3-Clause License. See the bundled `LICENSE.md` for details.
