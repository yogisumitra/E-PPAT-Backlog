# Prototipe Backlog E-PPAT

Kumpulan prototipe tampilan (HTML statis) untuk backlog E-PPAT. Semua berkas berdiri sendiri —
cukup dibuka di peramban, tidak perlu server atau pemasangan apa pun.

## Isi

| Berkas | Backlog | Isi |
|---|---|---|
| `index.html` | — | Halaman depan: daftar seluruh prototipe |
| `Backlog-EPPATPN-2-Object Jual Beli-Prototype.html` | EPPATPN-2 | Modal Tambah Objek (AJB): Status Sertipikat · Jenis Hak · Format Sertipikat · Status Objek menentukan isian butir 14/15/16/17, letak objek butir 18, dan meliputi pula butir 19 |
| `Backlog-EPPATPN-3-Minuta-01-Prototype.html` | EPPATPN-3 | E-Akta Wizard: tab Minuta Pertama / Minuta Kedua / Salinan yang terbuka bertahap — Minuta Kedua terbuka setelah Minuta Pertama selesai sampai E-Materai, Salinan terbuka setelah Minuta Kedua selesai sampai E-Materai — simulasi Digital Stamp, E-Signature, E-Materai, dan konfirmasi Mulai Ulang |
| `Backlog-EPPATPN-17-Profil-Kantor-Prototype.html` | EPPATPN-17 | Halaman Profil Kantor PPAT dengan tambahan Gelar Disingkat dan Gelar Tidak Disingkat |
| `Backlog-EPPATPN-19-Pemilihan-Para-Pihak-Prototype.html` | EPPATPN-19 | Order AJB tab Para Pihak: tabel pihak beserta baris turunan, pencarian user klien berlencana CA aktif / NIK kosong (tombol Ubah Data KTP nonaktif bila CA aktif), dan modal Tambah Pihak dengan kondisi per tipe (perorangan, badan hukum PT, pasangan, saksi, kuasa, ahli waris) |
| `Backlog-EPPATPN-20-Registrasi-CA-Melalui-AsistenPPAT-Prototype.html` | EPPATPN-20 | Halaman Daftar User berkolom Sertifikat CA (aktif / tidak aktif), modal Tambah dan Ubah User, alur pendaftaran ke Registrasi CA beserta masa berlaku tautan dan Buat Ulang Link, serta Cek Status CA dengan Data KTP terkunci untuk user yang sertifikatnya sudah aktif |
| `Backlog-EPPATPN-21-Editor-Template-Prototype.html` | EPPATPN-21 | Template Akta Kantor: 8 bagian (catatan, pasal, dan bagian otomatis), penyunting naskah beserta penyisip variabel, potongan redaksi bersyarat yang bisa disunting dan di-reset, tab Lampiran, Impor dari Word, serta Preview Akta per halaman. |
| `Backlog-EPPATPN-Drafting-Minuta-Prototype.html` | Drafting Minuta | Drafting minuta order: bagian yang disusun sistem dari kondisi order, lampiran naskah & berkas unggahan, penyunting naskah beserta variabel, tab Renvoi, dan alat Preview Akta / Cek Ejaan / Beritahu PPAT / Finalisasi Akta. |
| `Backlog-EPPATPN-25-Menu-Repository-Prototype.html` | EPPATPN-25 | Menu Akta Repository: daftar entri akta beserta status dan versi terbaru, detail riwayat versi, dokumen per versi, riwayat pengiriman, Unduh Draft Akta, dan modal Kirim Akta (pilih dokumen & penerima). |
| `Spesifikasi-Redaksi-Bersyarat-Akta-PPAT.html` | Dokumen | Pemetaan pilihan field pada layar Order ke redaksi yang terbentuk pada naskah akta |

Tiap prototipe punya baris navigasi di atas layar untuk berpindah antar prototipe dan kembali ke daftar;
dokumen spesifikasi punya tautan kembali di kaki sidebarnya.

## Menayangkan lewat GitHub Pages

1. Unggah seluruh berkas ini ke repositori (boleh di akar repo atau di dalam satu folder).
2. Buka **Settings → Pages**.
3. Bagian **Source** pilih **Deploy from a branch**.
4. Branch: **main**, folder: **/(root)** — lalu **Save**.
5. Tunggu satu sampai dua menit, alamatnya muncul di halaman yang sama:
   `https://<nama-akun>.github.io/<nama-repo>/`

Bila berkas ditaruh di dalam folder, alamatnya menjadi
`https://<nama-akun>.github.io/<nama-repo>/<nama-folder>/`.

## Menambah prototipe baru

1. Salin salah satu berkas prototipe sebagai titik awal.
2. Tambahkan satu kartu baru di `index.html` (tiru blok `<a class="card">` yang sudah ada).
3. Tambahkan tautannya di baris navigasi atas pada setiap berkas prototipe.

## Catatan

- Semua tombol bersifat simulasi — tidak ada data yang benar-benar tersimpan atau terkirim.
- Nama, e-mail, NIK, nama berkas, dan nomor pada contoh memakai data netral, bukan data asli.
- Semua konfirmasi memakai modal di dalam halaman, bukan dialog bawaan peramban.
