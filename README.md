# Praktikum SI-MVC Pemrograman Berbasis Web Lanjutan 2021/2022
## Buat Folder _db serta file didalamnya
	a. database.sql
## Buat Folder app serta empat folder didalamnya
	a. controllers
	b. core
	c. models
	d. views
## Buat Folder inc serta file didalamnya
	a. config.php
## Buat Folder layouts serta folder dan file didalamnya
	a. assets
		1) css
		2) images
	b. dashboard.php
	c. home.php
## Buat File index.php
## Inisialisasi Composer
## Set PSR-4
## Install filp/whoops untuk memudahkan informasi error
	```
	composer require filp/woops
	```
## Buat File .htaccess
## Bangun teknik MVC mulai dari
	a. app/core/Bootstrap.php
	b. app/core/Controller.php
	c. app/core/Model.php
	d. app/core/Error.php
## Setting Model untuk terhubung dengan Database
	```
	app/models/Namaclass.php
	```
## Setting Controller
	```
	app/controllers/Namaclass.php
	```
## Setting View
	```
	app/view/Namafolder/Namafile.php
	```

## Testing

```
http://localhost/si-mvc/
http://localhost/si-mvc/home/index
http://localhost/si-mvc/home/show
http://localhost/si-mvc/home/detail/1
http://localhost/si-mvc/dashboard
```