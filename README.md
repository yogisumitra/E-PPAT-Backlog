# Prototipe Backlog E-PPAT

Kumpulan prototipe tampilan (HTML statis) untuk backlog E-PPAT.
Semua file berdiri sendiri — tidak perlu server, database, atau proses build.

## Isi

| Berkas | Backlog | Isi |
| --- | --- | --- |
| `index.html` | — | Halaman depan, berisi daftar prototipe |
| `Backlog-EPPATPN-2-Object Jual Beli-Prototype.html` | EPPATPN-2 | Modal Tambah Objek (AJB): Input Sertipikat Manual/Elektronik dan form per Jenis Hak |
| `Backlog-EPPATPN-3-Minuta-01-Prototype.html` | EPPATPN-3 | E-Akta Wizard: tab Minuta Pertama / Minuta Kedua (terkunci) / Salinan + simulasi Digital Stamp, E-Signature, E-Materai |

## Cara memasang di GitHub Pages

1. Unggah ketiga berkas di atas ke **root** repository (bukan di dalam subfolder).
2. Buka **Settings → Pages** pada repository tersebut.
3. Bagian **Source** pilih **Deploy from a branch**, lalu pilih branch `main` dan folder `/ (root)`. Simpan.
4. Tunggu 1–2 menit, lalu buka `https://<nama-akun>.github.io/<nama-repo>/`.
   Halaman depan (`index.html`) akan muncul berisi pilihan prototipe; klik salah satu untuk membukanya.

Setiap prototipe juga punya baris pilihan di bagian atas layar, jadi bisa berpindah antar prototipe atau kembali ke daftar tanpa menekan tombol back.

## Menambah prototipe baru

1. Salin berkas HTML-nya ke repository dengan pola nama `Backlog-<kode>-<judul>-Prototype.html`.
2. Buka `index.html`, duplikat satu blok `<a class="card" …> … </a>`, lalu ganti tautan, kode backlog, judul, dan keterangannya.
3. Pada berkas prototipe yang baru, salin baris `<span class="protonav"> … </span>` dari prototipe lain supaya pilihan di atas ikut muncul, dan tambahkan tautannya di prototipe yang sudah ada.

## Catatan

- Prototipe, bukan aplikasi live: tombolnya simulasi dan tidak mengubah data apa pun.
- Nama, e-mail, nomor seri meterai, dan QR yang tampil memakai contoh netral, bukan data asli.
