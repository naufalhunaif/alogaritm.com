# alogaritm.com di Cloudflare Workers

Tiga halaman (`/`, `/privacy-policy`, dan `/terms-of-service`) menggunakan teks yang
diberikan pemilik situs. Desain monokrom responsif dibuat dari deskripsi yang
diberikan dan dipilih pemilik situs.

## Jalankan

```sh
npm install
npm run dev
```

Berkas halaman dan aset berada di `public/`. Jalankan `npm run deploy` untuk
menerbitkan Worker dan menghubungkan custom domain `alogaritm.com` di Cloudflare.
Cloudflare akan mengelola record DNS dan sertifikat untuk custom domain ini.
