# Mini App Freya (GitHub Pages)

Web menu untuk @freya_maidbot. Di-host gratis di GitHub Pages, dibuka dari Telegram sebagai Mini App.

## Yang bisa dan tidak bisa

Bisa:
- Menu 4 item
- Tampilkan QRIS
- Buka profil X
- Buka chat @fffrreya

Tidak bisa (GitHub Pages hanya file statis):
- Foto bukti otomatis masuk ke bot tanpa server
- Tombol konfirmasi otomatis

Jadi tombol "Kirim bukti" membuka chat @fffrreya. Customer kirim SS di situ.

## 1. Upload ke GitHub

1. Buat akun GitHub dari HP/browser
2. New repository, nama misalnya `freya-maid`
3. Public
4. Upload `index.html` dan `qris.jpg` (ganti qris.jpg dengan QRIS asli)
5. Settings → Pages → Branch `main` → folder `/ (root)` → Save
6. Tunggu 1–2 menit
7. URL jadi: `https://USERNAME.github.io/freya-maid/`

Coba buka URL itu di Chrome. Harus kelihatan menu.

## 2. Pasang di BotFather

1. Chat @BotFather
2. `/newapp`
3. Pilih @freya_maidbot
4. Title: `Freya Maid`
5. Description: `Menu profil, QRIS, dan chat Freya`
6. Upload foto 640x360 (boleh foto profil)
7. GIF demo: Skip
8. Web App URL: `https://USERNAME.github.io/freya-maid/`
9. Short name: `menu` (jadi link `https://t.me/freya_maidbot/menu`)

Menu button:

```
/setmenubutton
```

Pilih @freya_maidbot → judul `Menu Freya` → URL yang sama.

## 3. Tes

Buka @freya_maidbot. Tombol menu kiri bawah harus membuka halaman ini.
Atau buka `https://t.me/freya_maidbot/menu`.

Bot tidak perlu `python bot.py` hanya untuk membuka Mini App.
Bot tetap harus ada di BotFather.
