---
article_id: BKL-08-A03
writing_contract_version: "native-id-v2"
title: "Fit-Up, Tack, Sequence, dan Catatan Parameter saat Produksi"
slug: "fit-up-tack-sequence-dan-catatan-las"
description: "Cover preparation, alignment, tack acceptance, WPS availability, consumable control, preheat/interpass concepts, sequence, weather, and logs"
status: draft
publication_date: "2025-09-25"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BKL-08
primary_intent: "Understand in-process welding control"
reader_community: "Bengkel.co.id"
reader_address: "Kawan Bengkel.co.id"
final_route: "/artikel/fit-up-tack-sequence-dan-catatan-las.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
  - "https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015"
---

# Fit-Up, Tack, Sequence, dan Catatan Parameter saat Produksi

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

Halo, Kawan Bengkel.co.id! Pada produksi las, hasil yang dapat diulang tidak dimulai dari menekan tombol mesin, melainkan dari fit-up (penyetelan dan penjajaran sambungan), tack (las titik penahan), urutan pengelasan, serta catatan yang membuat setiap keputusan bisa ditelusuri. Jalan pintas seperti “asal rapat lalu las penuh” dapat menyembunyikan celah, salah posisi, atau perubahan material yang baru terlihat saat inspeksi.

Jawaban singkatnya: tetapkan dahulu gambar kerja dan batas penerimaan, cocokkan material serta WPS (Welding Procedure Specification atau spesifikasi prosedur pengelasan) yang disetujui, verifikasi fit-up dan tack sebelum pengelasan penuh, lalu ikuti sequence dan rentang parameter yang berlaku. WPS, kualifikasi prosedur, kualifikasi welder, inspeksi, dan penerimaan sambungan adalah bukti yang berbeda; satu kartu welder tidak menggantikan dokumen lainnya. Kerangka pembedaan ini selaras dengan penjelasan resmi ISO 15614-1, ISO 9606-1, dan ISO 3834-6, tetapi rentang kualifikasi dan persyaratan uji tetap harus dibaca dari edisi standar berlisensi serta spesifikasi proyek ([ISO 15614-1](https://www.iso.org/standard/51792.html), [ISO 9606-1](https://www.iso.org/standard/54936.html), [ISO 3834-6](https://www.iso.org/standard/83335.html)).

[NEEDS IMAGE REVIEW: LOCAL-001]

Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.

## Hasil akhir dan prasyarat

Hasil akhir yang dicari supervisor bukan hanya manik las yang tampak rapi, melainkan paket bukti: komponen teridentifikasi, sambungan terpasang sesuai gambar, tack diterima, pengelasan mengikuti WPS, material dan consumable dapat ditelusuri, inspeksi tercatat, dan setiap penyimpangan memiliki keputusan. Orang yang menyetujui fit-up, orang yang mengelas, serta pemeriksa tidak otomatis memiliki kewenangan yang sama. Tetapkan peran itu di awal.

Sebelum pekerjaan dibuka, siapkan revisi gambar, detail sambungan, WPS yang relevan, rekaman kualifikasi prosedur dan welder yang masih berlaku untuk lingkup pekerjaan, alat ukur yang layak, formulir inspeksi, serta identitas material dan bahan tambah. Bila salah satu dokumen inti belum tersedia, status yang jujur adalah “tahan untuk klarifikasi”, bukan mengisi angka dari kebiasaan bengkel. [NEEDS REVIEW: edisi standar dan rentang kualifikasi proyek harus dikonfirmasi dari dokumen berlisensi dan spesifikasi yang berlaku.]

Kawan Bengkel.co.id, anggap catatan sebagai bagian dari produk. Catat nomor komponen, nomor sambungan, tanggal, welder, WPS, material, consumable, pemeriksa, dan keputusan hold point. Dengan begitu, ketika ada pertanyaan tentang satu sambungan, tim tidak perlu menebak dari ingatan.

## Langkah 1 — tetapkan ruang lingkup

Mulailah dari batas fisik dan batas keputusan. Tandai sambungan mana yang dibuat di workshop, mana yang mungkin berpindah ke lapangan, antarmuka dengan komponen lain, area yang harus tetap dapat diinspeksi, serta pekerjaan yang tidak termasuk dalam lembar kerja. Jangan menyamakan “bisa dipindahkan” dengan “boleh dilas di lapangan”. Perpindahan lokasi dapat mengubah akses, posisi, cuaca, pasokan listrik, ventilasi asap, bahaya kebakaran, lalu lintas orang, dan rencana inspeksi. UU Keselamatan Kerja Indonesia dan ketentuan K3 yang relevan menuntut pengendalian berdasarkan kondisi pekerjaan yang nyata; panduan OSHA tentang pengelasan hanya ilustrasi bahaya, bukan pengganti persetujuan K3 Indonesia ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [OSHA 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252)).

Tentukan juga apa yang menjadi syarat berhenti: gambar tidak jelas, material tidak cocok, WPS tidak tersedia, tack retak, celah di luar batas dokumen, atau lingkungan tidak aman. Nilai penerimaan harus diambil dari gambar, WPS, spesifikasi, dan rencana inspeksi proyek—bukan dari angka universal.

## Langkah 2 — kumpulkan dan cocokkan bukti

Pada pemeriksaan material, cocokkan penandaan komponen dengan daftar material dan sertifikat atau laporan yang diwajibkan proyek. Simpan identitas heat atau batch bila diminta, dimensi, dan lokasi pemakaian. Untuk consumable, periksa klasifikasi, batch, kondisi kemasan, penyimpanan, serta rekaman pengeluaran atau pengeringan sesuai instruksi produk dan WPS. Jangan menebak kompatibilitas, masa simpan, atau kondisi pengeringan dari label generik. ISO 3834-6 menempatkan pengendalian sumber daya dan rekaman sebagai bagian dari sistem mutu pengelasan, bukan pekerjaan administrasi yang boleh dilewati ([ISO 3834-6](https://www.iso.org/standard/83335.html)).

Lembar fit-up sebaiknya memuat identitas sambungan, orientasi, jenis dan ukuran material, kebersihan permukaan, root opening atau celah akar, alignment atau mismatch, panjang dan lokasi tack, serta alat ukur yang digunakan. Angka penerimaan hanya boleh diisi jika memang ditentukan dokumen proyek. Foto dapat membantu konteks, tetapi tidak menggantikan pengukuran dan tanda tangan pemeriksa.

Bedakan empat pertanyaan berikut: apakah prosedurnya memenuhi syarat, apakah welder berwenang mengerjakan lingkup itu, apakah pelaksanaan mengikuti prosedur, dan apakah hasil akhirnya diterima. Sobat Bengkel.co.id, empat jawaban tersebut perlu empat jejak bukti yang dapat dirujuk silang; mencampurnya membuat rework sulit dianalisis.

## Langkah 3 — jalankan urutan kerja

Urutan konseptualnya sederhana, tetapi disiplin di setiap gerbang penting. Pertama, bersihkan permukaan dan pastikan orientasi komponen sesuai gambar. Kedua, lakukan fit-up dengan jig atau penahan yang tidak merusak material, ukur celah dan alignment, lalu minta pemeriksaan. Ketiga, buat tack sesuai WPS atau instruksi kerja: lokasi, jumlah, ukuran, dan siapa yang memeriksa harus tercatat. Tack yang retak, berpori, terlepas, atau mengganggu jalur las tidak boleh ditutup begitu saja; bersihkan dan putuskan perbaikannya sebelum lanjut.

Keempat, pastikan identitas WPS, proses, posisi, material, dan rentang ketebalan sesuai sambungan. Kelima, kendalikan consumable dan peralatan: jenis bahan tambah, polaritas atau mode mesin bila tercantum, kabel, massa, dan kondisi alat. Keenam, ikuti sequence yang dirancang untuk mengelola penyusutan dan distorsi—misalnya urutan seimbang atau berpindah antarbagian sesuai instruksi yang disetujui—tanpa mengarang pola baru di tengah pekerjaan.

Preheat dan interpass bukan angka hafalan. Keduanya adalah konsep pengendalian temperatur yang harus mengikuti WPS, material, ketebalan, metode ukur, dan keputusan personel berwenang. Catat kondisi aktual dan alat ukurnya; jika temperatur di luar rentang, hentikan dan minta keputusan. Parameter arus, tegangan, kecepatan, atau heat input juga dicatat sebagai nilai aktual bila formulir proyek memintanya, bukan diisi ulang dari angka rencana setelah pekerjaan selesai.

Jika pekerjaan berpindah ke lapangan, lakukan penilaian ulang. Angin, hujan, permukaan basah, akses sempit, sumber listrik, material mudah terbakar, dan orang di sekitar dapat mengubah pengendalian. Ketentuan K3 Indonesia dan rencana kerja setempat harus menentukan izin, penghalang, ventilasi, pemadam, pengawasan api, serta prosedur darurat; artikel ini tidak menyediakan jarak atau durasi universal.

## Titik tahan dan kondisi berhenti

Tahan pekerjaan sebelum las penuh jika identitas material tidak cocok, WPS atau kualifikasi tidak dapat ditunjukkan, fit-up di luar batas, tack belum diterima, alat ukur atau mesin bermasalah, consumable tidak terlacak, atau kondisi lingkungan berubah. Tahan juga saat ditemukan retak, indikasi cacat, distorsi yang mengubah geometri, atau kehilangan catatan parameter. Beri status jelas—menunggu pemeriksaan, menunggu engineering, atau menunggu keputusan K3—dan jangan menghapus jejak perubahan.

Keputusan membuka kembali pekerjaan harus datang dari fungsi yang ditetapkan proyek. Untuk persoalan keselamatan, gunakan pengendalian berjenjang: hilangkan atau ubah bahaya bila mungkin, gunakan pengendalian teknis dan administratif, lalu pilih PPE yang sesuai. [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015) dan kerangka K3 nasional perlu dibaca bersama kondisi aktual; [NEEDS REVIEW: detail ventilasi, perlindungan listrik, pemisahan tabung, fire watch, dan rencana penyelamatan belum disediakan dalam paket ini.]

## Verifikasi hasil dan serah terima

Sebelum handover, cocokkan daftar sambungan dengan status fit-up, tack, pengelasan, inspeksi visual, dan pemeriksaan tambahan yang diwajibkan proyek. Pastikan setiap reparasi memiliki referensi sambungan, alasan, metode yang disetujui, pemeriksaan ulang, dan persetujuan penutupan. Satukan log welder, WPS, consumable, temperatur bila diwajibkan, kondisi cuaca untuk pekerjaan lapangan, nomor alat, serta nama pemeriksa.

Buat ringkasan penyimpangan yang mudah dibaca: apa yang berubah, kapan ditemukan, siapa yang memutuskan, bukti apa yang mendukung, dan apakah dampaknya sudah diverifikasi. Handover yang baik memungkinkan tim berikutnya memahami batas pekerjaan tanpa mengandalkan cerita lisan. Untuk kebutuhan pembaca yang sedang menyiapkan pekerjaan khusus, rujukan layanan seperti [las besi dan baja](/las-besi-baja.html) dapat menjadi langkah awal memahami jenis pekerjaan. Jika koordinasi perlu dilakukan di lokasi dengan akses berubah, penjelasan tentang [layanan las portable](/las-portable.html) membantu membedakan kebutuhan mobilitas dari persetujuan teknis; keputusan akhir tetap mengikuti spesifikasi dan pemeriksaan proyek.

## Jalan pintas yang sering menggoda

“Tack saja dulu, dokumen menyusul” terdengar cepat, tetapi mengunci kesalahan geometri ke dalam sambungan dan menghilangkan konteks siapa yang menyetujui. Jalan pintas lain adalah menyalin parameter dari pekerjaan lama karena material terlihat sama. Perbedaan ketebalan, posisi, proses, batch consumable, atau kondisi lingkungan dapat membuat salinan itu tidak berlaku. Alternatif yang lebih andal adalah menghentikan di hold point, melengkapi bukti, lalu meminta penyesuaian WPS atau keputusan engineering yang tercatat.

## Kesimpulan dan tindakan berikutnya

Fit-up, tack, sequence, dan catatan parameter membentuk satu rantai pengendalian: geometri diverifikasi, penahan diterima, prosedur dan welder cocok, bahan serta alat terlacak, urutan dijalankan, kondisi dicatat, dan hasil diperiksa. Tidak ada setelan universal yang dapat menggantikan WPS yang disetujui dan personel berkualifikasi.

Teman Bengkel.co.id, sebelum membuka busur berikutnya, minta supervisor menandatangani lembar fit-up dan tack, tunjukkan WPS serta bukti kualifikasi yang relevan, lalu pastikan log aktual dan rencana inspeksi tersedia. Jika salah satu gerbang belum jelas, berhenti dan minta review teknis/K3. Aturan operasinya: pekerjaan boleh maju hanya ketika bukti untuk tahap sebelumnya lengkap dan kondisi aktual masih berada dalam batas yang disetujui.
