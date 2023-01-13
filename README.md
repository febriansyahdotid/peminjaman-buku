# Website Peminjaman Buku Perpustakaan

## Persyaratan sistem

PHP minimal 8.0

sudah terinstall composer
<https://getcomposer.org/>

sudah terinstall nodejs
<https://nodejs.org/>

## instalasi

```bash
git clone https://github.com/febriansyahdotid/peminjaman-buku.git
```

```bash
cd peminjaman-buku
```

```bash
cp .env.example .env
```

```bash
composer install
```

```bash
npm install
```

```bash
npm run build
```

```bash
php artisan key:generate
```

```bash
php artisan migrate --seed
```
jika muncul
 WARN  The database 'perpus' does not exist on the 'mysql' connection.

ketik **yes**

```bash
php artisan serve
```

buka <http://127.0.0.1:8000/>


## Login & Register
Login <http://127.0.0.1:8000/login>
Register <http://127.0.0.1:8000/register>
