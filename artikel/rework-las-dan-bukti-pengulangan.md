---
article_id: BKL-08-A05
title: "Rework Las: Kapan Diperbolehkan dan Bukti Apa yang Harus Diulang"
slug: "rework-las-dan-bukti-pengulangan"
description: "Describe authorization, defect mapping, removal, material condition, repair procedure, reinspection, repeated repair, and records"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-05"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BKL-08
primary_intent: "Control weld repair cycle"
reader_community: "Bengkel.co.id"
reader_address: "Teman Bengkel.co.id"
final_route: "/artikel/rework-las-dan-bukti-pengulangan.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015"
---

# Rework Las: Kapan Diperbolehkan dan Bukti Apa yang Harus Diulang

Halo, Teman Bengkel.co.id! Rework las diperbolehkan bukan karena hasil las terlihat kurang rapi, melainkan karena ketidaksesuaian sudah dipetakan, ada persetujuan pihak berwenang, dan jalur perbaikannya dapat dibuktikan. Jika pemeriksaan menemukan indikasi cacat, jangan langsung menggerinda lalu mengelas ulang. Hentikan bagian yang terdampak, catat identitas sambungan, dan minta keputusan terhadap NCR (nonconformance report) atau mekanisme proyek yang setara.

Bukti yang perlu diulang biasanya bukan semua kualifikasi dari awal. Yang harus diulang adalah bukti yang berubah atau yang memang diwajibkan oleh prosedur: peta cacat dan batas penghilangan, kondisi material setelah cacat dibuang, prosedur perbaikan yang disetujui, identitas juru las dan bahan tambah, lalu inspeksi ulang dengan kriteria penerimaan yang sama. Kualifikasi prosedur, kualifikasi juru las, dan penerimaan sambungan adalah hal berbeda; abstrak ISO 15614-1, ISO 9606-1, dan ISO 3834-6 membantu menjaga ketiganya tidak tertukar ([ISO 15614-1](https://www.iso.org/standard/51792.html), [ISO 9606-1](https://www.iso.org/standard/54936.html), [ISO 3834-6](https://www.iso.org/standard/83335.html)).

![Ilustrasi bg bengkel](/wp-content/uploads/2024/06/bg-bengkel.jpg)


*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*
*Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.*

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-001`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi bg bengkel](/wp-content/uploads/2024/06/bg-bengkel.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `bg bengkel` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-001]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

## Jawaban singkat dan salah paham utama

Sebuah rework layak dimulai setelah tiga pertanyaan dijawab tertulis: cacat apa yang ditemukan dan di mana batasnya, siapa yang mengizinkan metode perbaikan, dan bukti apa yang akan menunjukkan sambungan kembali memenuhi persyaratan. “Sudah di-NDT” tidak otomatis berarti perbaikan sah; pemeriksaan hanya bermakna bila area, metode, waktu, dan kriteria penerimaannya ditentukan.

Salah paham paling mahal adalah menganggap kartu juru las sebagai izin untuk memperbaiki apa pun. Kartu menunjukkan ruang lingkup kualifikasi pada kondisi tertentu, sedangkan WPS (welding procedure specification) mengarahkan produksi dan prosedur kualifikasi menunjukkan dasar pengujiannya. Sambungan yang sudah selesai tetap memerlukan inspeksi dan keputusan penerimaan proyek. Jika ada ketidakpastian pada rentang kualifikasi atau edisi standar, tandai `[NEEDS COORDINATOR REVIEW: GATE-03/GATE-04]` dan minta teks standar berlisensi serta spesifikasi proyek; jangan mengisi rentang dengan perkiraan.

## Definisi dan batas objek

Dalam artikel ini, rework adalah pekerjaan perbaikan pada sambungan las yang dinyatakan tidak sesuai, bukan sekadar touch-up kosmetik. Siklusnya mencakup otorisasi, pemetaan indikasi, penghilangan bagian yang tidak sesuai, pemeriksaan kondisi tersisa, pelaksanaan las perbaikan, dan pemeriksaan ulang. Repair berulang adalah siklus berikutnya ketika hasil inspeksi ulang masih tidak sesuai; itu bukan alasan untuk menghapus riwayat sebelumnya.

Artikel ini tidak memilih apakah cacat harus digerinda, di-gouging, dipotong, atau memakai metode lain, dan tidak menetapkan acceptance level. NCR serta otoritas kode/proyek yang berkualifikasi yang membuat keputusan tersebut. Bila keputusan itu belum ada, status sambungan tetap tertahan. Pembahasan keselamatan juga bersifat kerangka: pengendalian aktual harus ditinjau penanggung jawab K3 dan kondisi tempat kerja sesuai kewajiban keselamatan kerja Indonesia ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)).

## Cara kerjanya

Mulai dengan mengunci identitas: nomor weld atau spool, lokasi, material, gambar, WPS yang direncanakan, tanggal inspeksi, dan laporan yang memicu rework. Inspektor kemudian menandai indikasi pada sketsa atau foto yang dapat dilacak. Catat metode pemeriksaan, panjang atau koordinat area menurut format proyek, dan siapa yang memverifikasi batas indikasi. Jangan memperluas area penghilangan tanpa mencatat alasan dan persetujuan.

Setelah metode removal disetujui, periksa permukaan dan penampang yang tersisa. Tujuannya memastikan cacat benar-benar terangkat tanpa menciptakan takik, penipisan, retak baru, kontaminasi, atau perubahan bentuk yang tidak diterima. Temuan ini menjadi hold point sebelum pengelasan ulang. Kondisi material, identitas heat atau batch bila dipersyaratkan, serta bahan tambah dan batch-nya harus tertaut ke catatan pekerjaan. Sistem mutu pengelasan memang memisahkan kendali material, peralatan, consumable, pelaksanaan, inspeksi, dan penerimaan; jangan menyatukannya menjadi satu tanda tangan ([ISO 3834-6](https://www.iso.org/standard/83335.html)).

Pengelasan ulang dilakukan oleh juru las yang kualifikasinya masih berlaku untuk pekerjaan tersebut, memakai WPS atau repair procedure yang disetujui. Catatan harus menangkap siapa yang mengelas, sambungan mana, prosedur yang dipakai, bahan tambah, kondisi pemanasan yang diwajibkan prosedur, dan pemeriksaan antar-lapis bila relevan. Kualifikasi juru las tidak boleh dipakai untuk mengklaim prosedur perbaikan telah memenuhi syarat; keduanya adalah bukti berbeda ([ISO 9606-1](https://www.iso.org/standard/54936.html), [ISO 15614-1](https://www.iso.org/standard/51792.html)).

Sesudah selesai, lakukan visual inspection dan metode NDT atau pengujian lain yang ditentukan oleh kode dan ITP. Laporan harus menyebut area rework, tanggal, metode, hasil, evaluator, dan keputusan accept/reject. Jika reject, buka siklus baru dengan referensi ke laporan sebelumnya. Jangan mengganti nomor sambungan atau menimpa laporan agar riwayat tampak bersih.

## Faktor yang mengubah hasil

Pertama, jenis dan kedalaman indikasi menentukan apakah perbaikan lokal masuk akal atau perlu keputusan desain. Kedua, akses dan posisi dapat berubah antara fabrikasi dan pekerjaan lapangan. Pemindahan pekerjaan ke lapangan mengubah fit-up, cuaca, suplai listrik, ventilasi asap, bahaya kebakaran, akses inspeksi, dan pemulihan area; karena itu, kenyamanan transportasi bukan justifikasi teknis untuk field weld. Rencana kerja, izin, dan pengendalian aktual harus disetujui otoritas lokasi.

Ketiga, material dan consumable yang tidak terlacak membuat hasil sulit diselidiki. Tahan pekerjaan bila sertifikat, batch, kondisi penyimpanan, atau substitusi tidak dapat ditautkan. Keempat, riwayat repair count penting. Batas pengulangan, kebutuhan evaluasi engineering, atau pemeriksaan tambahan bergantung pada kode dan spesifikasi yang berlaku. Paket ini tidak memuat angka batas, sehingga `[NEEDS COORDINATOR REVIEW: GATE-06]` harus tetap terbuka sebelum Anda menetapkan angka.

Terakhir, K3 bukan hanya APD. Identifikasi energi, asap, panas, bahan kimia, listrik, benda mudah terbakar, jalur evakuasi, dan pekerjaan di sekitar. Teman Bengkel.co.id, jika pekerjaan berpindah dari shop ke site, lakukan penilaian risiko baru; pengendalian lama tidak otomatis cocok untuk antarmuka publik, penghuni, atau operasi yang sedang berjalan ([Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015)).

## Contoh keputusan praktis

Gunakan urutan keputusan berikut pada rapat singkat:

| Pertanyaan | Jika “ya” | Jika “tidak” |
|---|---|---|
| Ada laporan indikasi dan batas area yang dapat dilacak? | Lanjutkan ke review teknis. | Tahan, lengkapi pemetaan. |
| Otoritas kode/proyek menyetujui removal dan repair procedure? | Terbitkan izin kerja/hold-point. | Jangan menghilangkan atau mengelas. |
| Material, consumable, WPS, dan juru las dapat ditautkan? | Siapkan pelaksanaan terkendali. | Karantina dan verifikasi identitas. |
| Pemeriksaan ulang memakai metode dan acceptance level yang disetujui? | Tutup NCR bila hasil diterima. | Minta revisi rencana inspeksi. |

Contohnya, indikasi pada satu sambungan tidak boleh diperlakukan sebagai izin memperbaiki semua sambungan serupa. Perluas pemeriksaan hanya jika evaluasi teknis menunjukkan alasan. Sebaliknya, hasil “repair selesai” tanpa laporan reinspection belum menjadi bukti penerimaan. Untuk pekerjaan yang memerlukan akses bergerak, lihat konteks layanan [las portable](/las-portable.html), sedangkan sambungan material besi atau baja dapat dibandingkan lewat [layanan las besi dan baja](/las-besi-baja.html); keputusan teknis tetap berada pada spesifikasi dan otoritas proyek.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menghapus bekas cacat sebelum memotret dan mengukur lokasinya. Periksa apakah laporan awal, sketsa, dan identitas sambungan tersimpan sebelum pekerjaan dimulai. Kedua, memakai WPS produksi lama tanpa memastikan revisi dan kesesuaiannya untuk repair. Minta nomor revisi dan persetujuan khusus bila prosedur perbaikan berbeda.

Ketiga, mengulang NDT tetapi tidak memeriksa kondisi setelah removal. Tambahkan hold point setelah penghilangan dan sebelum deposit baru. Keempat, mencampur laporan juru las dengan laporan penerimaan. Pastikan setiap bukti punya fungsi: kualifikasi juru las, prosedur, material, parameter/observasi pekerjaan, NDT, dan keputusan akhir.

Kelima, menganggap satu hasil lulus menutup semua siklus. Audit nomor repair, tanggal, area, dan referensi laporan sebelumnya. Kawan Bengkel.co.id, bila ada pengulangan kedua, minta engineering atau otoritas kode menilai dampaknya sebelum memberi izin berikutnya; jangan menyamarkan repair count.

## Jalan pintas yang tampak praktis tetapi berisiko

Shortcut yang sering dipilih adalah “gerinda sampai bersih, las sedikit, lalu foto hasil akhir”. Ini gagal karena batas cacat, kondisi material tersisa, prosedur, dan bukti inspeksi hilang dari rantai keputusan. Foto akhir tidak membuktikan apa yang dihapus atau siapa yang mengizinkan.

Alternatif yang lebih andal adalah satu lembar kontrol per siklus: identitas sambungan, indikasi awal, otorisasi, metode removal yang disetujui, verifikasi permukaan, WPS/repair procedure, juru las, consumable, catatan pelaksanaan, reinspection, dan status NCR. Formulir boleh sederhana, tetapi setiap kolom harus menunjuk dokumen sumber yang dapat ditemukan.

## Kesimpulan

Rework las diperbolehkan ketika ketidaksesuaian terpetakan, removal dan repair procedure disetujui otoritas proyek, material serta pelaksana tertelusur, dan inspeksi ulang membuktikan penerimaan. Yang diulang bukan otomatis seluruh kualifikasi, melainkan bukti yang berubah atau yang diminta kode/proyek; keputusan itu harus tertulis.

Langkah Anda berikutnya: tahan sambungan, buka atau perbarui NCR, susun peta cacat, lalu minta persetujuan metode dan rencana reinspection sebelum pekerjaan dimulai. Simpan seluruh riwayat jika repair berulang. Level penerimaan, metode removal, dan batas jumlah pengulangan tetap memerlukan tinjauan teknis proyek—`[NEEDS COORDINATOR REVIEW: GATE-08]`—sehingga artikel ini tidak menggantikan approval profesional.
