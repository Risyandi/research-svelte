
---

# svelte app

Ini adalah sebuah proyek riset yang menggunakan template [Svelte](https://svelte.dev) dan disini kita akan membuaut sebuah apps dengan svelte. 
jika anda ingin melihat live demo nya anda bisa mengakses link berikut https://github.com/sveltejs/template.

Untuk membuat sebuah proyek baru berdasarkan templat anda bisa menggunakan template berikut [degit](https://github.com/Rich-Harris/degit), dan untuk perintah berikut :
```bash
npx degit sveltejs/template svelte-app
cd svelte-app
```

*Catatan : Kamu akan membutuhkan [Node.js](https://nodejs.org) yang sudah terinstall*


## Mari Mulai

Instal terlebih dahulu dependencies nya, masukan perintah berikut :

```bash
cd svelte-app
npm install
```

Lalu jalankan [Rollup](https://rollupjs.org), dengan memasukan perintah berikut:

```bash
npm run dev
```

Navigasikan ke link [localhost:5000](http://localhost:5000). Anda akan melihat svelte berjalan. Ubah file komponen di `src`, Lalu simpan, dan lalu perbarui browser anda untuk melihat perubahan.

Sebagai default, Server hanya akan merespon request dari localhos. Untuk mengizinkan koneksi dari komputer lain, Ubahlah perintah `sirv` didalam package.json termasuk pilihan `--host 0.0.0.0`.


## Deploying Web

### Dengan [now](https://zeit.co/now)

Install `now` jika belum terinstall, masukan perintah berikut :

```bash
npm install -g now
```

Lalu, dari folder proyek anda, masukan perintah berikut :

```bash
cd public
now
```

Sebagai salah satu alternatif, gunakan [Now desktop client](https://zeit.co/download) dan sederhana drag folder proyek unzipped ke taskbar icon.

### Dengan [surge](https://surge.sh/)

Install `surge` jika belum terinstall, masukan perintah berikut :

```bash
npm install -g surge
```

Lalu, dari folder proyek anda, masukan perintah berikut :

```bash
npm run build
surge public
```
*Jika anda mencari sebuah template komponen yang sudah ada? pergi kesini --> [sveltejs/component-template](https://github.com/sveltejs/component-template)*