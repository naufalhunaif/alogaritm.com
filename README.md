# alogaritm.com di Cloudflare Workers

Tiga halaman (`/`, `/privacy-policy`, dan `/terms-of-service`) menggunakan teks yang
diberikan pemilik situs. Desain monokrom responsif dibuat dari deskripsi yang
diberikan dan dipilih pemilik situs.

## Jalankan

```sh
npm install
npm run dev
```

Berkas halaman dan aset berada di `public/`. Setelah tampilan diperiksa, jalankan
`npm run deploy`, lalu sambungkan domain `alogaritm.com` ke Worker di Cloudflare.
Domain belum dicantumkan sebagai custom domain di `wrangler.jsonc`, sehingga
perintah deploy tidak langsung mengambil alih situs yang sedang aktif.
