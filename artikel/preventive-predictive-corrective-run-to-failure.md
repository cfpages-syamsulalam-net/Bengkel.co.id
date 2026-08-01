---
article_id: BKL-16-A04
title: "Preventive, Predictive, Corrective, dan Run-to-Failure: Memilih Strategi"
slug: "preventive-predictive-corrective-run-to-failure"
description: "Panduan memilih strategi perawatan berdasarkan konsekuensi, gejala, data, waktu henti, dan sumber daya aset."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-04-10"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BKL-16
primary_intent: "Choose maintenance strategy"
reader_community: "Bengkel.co.id"
reader_address: "Teman Bengkel.co.id"
final_route: "/artikel/preventive-predictive-corrective-run-to-failure.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
---

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

# Preventive, Predictive, Corrective, dan Run-to-Failure: Memilih Strategi

Halo, Teman Bengkel.co.id! Memilih strategi perawatan bukan soal mencari satu metode yang paling modern. Mulailah dari akibat bila aset gagal, seberapa cepat gejalanya bisa ditemukan, data yang tersedia, dan apakah penghentian terencana lebih murah daripada gangguan mendadak. Aset dengan konsekuensi keselamatan atau kepatuhan tidak boleh otomatis dimasukkan ke run-to-failure.

Secara praktis, preventive (berdasarkan waktu atau jam operasi) cocok ketika pola aus cukup dapat diperkirakan; predictive (berdasarkan kondisi) cocok ketika ada indikator yang bisa diukur dan ditindaklanjuti; corrective dipilih saat ditemukan penyimpangan atau kerusakan; run-to-failure hanya masuk akal untuk aset berkonsekuensi rendah, mudah diganti, dan tidak menimbulkan bahaya lanjutan. Keputusan dapat berubah setelah riwayat work order, mode kegagalan, kewajiban pemeriksaan, manual OEM, dan persetujuan pemilik aset ditinjau. Jangan menetapkan interval, ambang alarm, jumlah spare, atau janji uptime tanpa data tersebut.

![Ilustrasi bg bengkel](/wp-content/uploads/2024/06/bg-bengkel.jpg)

*Ilustrasi umum dari aset lokal Bengkel.co.id; bukan dokumentasi proyek tertentu.*

## Tentukan objek, kondisi, dan tahap siklus hidup

Buat daftar aset pada tingkat yang berguna untuk keputusan: mesin lengkap, subsistem, atau komponen yang punya mode kegagalan berbeda. Catat fungsi, kondisi awal, lingkungan, pola beban, akses inspeksi, dan tahap siklus hidupnya. Unit baru mungkin memerlukan verifikasi pemasangan dan baseline; unit menua mungkin memerlukan keputusan penggantian, bukan sekadar menambah jadwal.

Untuk setiap aset, jawab empat pertanyaan: apa fungsi yang hilang ketika gagal, siapa yang terdampak, apakah ada energi berbahaya, dan berapa lama pemulihan realistis berdasarkan sumber daya yang tersedia? Aturan keselamatan kerja dan pengendalian energi harus mengikuti ketentuan Indonesia yang berlaku serta prosedur lokasi; OSHA 1910.147 dapat menjadi rujukan umum tentang pengendalian energi berbahaya, bukan pengganti persyaratan setempat ([OSHA 1910.147](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147)).

Jika jawabannya menyentuh cedera, pelepasan energi, kebakaran, containment, atau fungsi proteksi, tandai sebagai aset safety-critical. Teman Bengkel.co.id, klasifikasi ini adalah rem keputusan: run-to-failure tidak boleh disahkan hanya karena biaya preventive terlihat lebih tinggi.

## Mekanisme perubahan atau penurunan kinerja

Hubungkan cara aset dipakai dengan cara ia gagal. Beban berulang, kontaminasi, korosi, misalignment, pelumasan yang tidak sesuai, panas, getaran, dan perubahan proses dapat mengubah laju penurunan kinerja. Hindari menganggap umur kalender sebagai bukti umur sisa. Preventive mengurangi peluang kegagalan tertentu melalui pekerjaan terjadwal, tetapi pekerjaan terlalu sering juga dapat menambah kesalahan perakitan atau downtime.

Predictive baru bernilai jika sinyal kondisi memiliki metode ukur, kualitas data, dan tindakan yang jelas. Satu pembacaan atau gejala visual bukan diagnosis lengkap. ISO 17635 menjelaskan bahwa metode, cakupan, teknik, personel, peralatan, kondisi permukaan, verifikasi, pelaporan, dan dasar penerimaan adalah bukti terpisah; abstraknya juga mengingatkan bahwa level penerimaan NDT tidak diterjemahkan satu banding satu dari ISO 5817 ([ISO 17635:2025](https://www.iso.org/standard/85705.html)).

Corrective dapat bersifat terencana setelah anomali ditemukan, atau tidak terencana setelah fungsi hilang. Bedakan keduanya di sistem work order agar biaya, waktu tunggu spare, dan kesempatan perbaikan akar masalah dapat dibandingkan. Run-to-failure berarti menerima kegagalan fungsional sebagai titik intervensi yang direncanakan—bukan mengabaikan inspeksi, guarding, atau kewajiban hukum.

## Inspeksi dan data yang perlu dicatat

Tetapkan baseline sebelum membandingkan tren: identitas aset dan komponen, kondisi operasi saat ukur, instrumen, metode, lokasi pengukuran, hasil, foto atau sketsa yang relevan, serta nama pemeriksa. Catat juga failure code, penyebab yang diduga, parts identity, pekerjaan tertunda, dan hasil uji setelah pekerjaan. Personel NDT harus memiliki kompetensi yang sesuai dengan metode dan tugasnya; ISO 9712 mendeskripsikan skema kualifikasi dan sertifikasi personel NDT, bukan nilai penerimaan untuk aset tertentu ([ISO 9712:2021](https://www.iso.org/standard/75614.html)).

Gunakan tabel keputusan sederhana berikut sebagai penyaring awal, bukan skor otomatis:

| Pertanyaan | Jika “ya” | Arah awal |
|---|---|---|
| Kegagalan membahayakan orang, lingkungan, atau fungsi proteksi? | Konsekuensi tinggi | Preventive/predictive dengan otoritas kompeten; jangan run-to-failure |
| Gejala berkembang dapat diukur sebelum fungsi hilang? | Detectability ada | Predictive, bila metode dan tindak lanjut tervalidasi |
| Pola aus cukup konsisten dan downtime bisa dijadwalkan? | Predictability ada | Preventive berbasis waktu atau jam operasi |
| Dampak rendah, komponen modular, dan penggantian siap? | Failure opportunity dapat diterima | Run-to-failure dengan inspeksi dasar dan spare yang disetujui |
| Ada penyimpangan atau kerusakan yang sudah ditemukan? | Kondisi aktual berubah | Corrective terencana, lalu evaluasi akar penyebab |

Kawan Bengkel.co.id, “data ada” tidak sama dengan “data siap dipakai”. Periksa konsistensi satuan, kalibrasi atau verifikasi, cakupan, dan siapa yang berwenang menetapkan penerimaan. [NEEDS SITE REVIEW: interval, ambang kondisi, remaining-life estimate, dan jumlah spare harus ditetapkan dari manual OEM, riwayat aset, konteks operasi, serta persyaratan statutory yang berlaku.]

## Pilihan perawatan atau intervensi

Untuk aset berkonsekuensi tinggi, gabungkan pemantauan kondisi dengan preventive yang memang diwajibkan dan pemeriksaan fungsional. Tetapkan siapa yang boleh menunda pekerjaan, siapa yang mengisolasi energi, dan siapa yang mengizinkan kembali beroperasi. Permenaker yang berlaku dan persyaratan pengawasan alat harus diverifikasi pada versi terkini ([Permenaker No. 38 Tahun 2016](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016); [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026)).

Untuk aset menengah, pilih kombinasi yang menyeimbangkan planned downtime, keterampilan, dan biaya siklus hidup. Inspeksi kondisi dapat memicu corrective terencana ketika akses shutdown tersedia, sementara komponen consumable mengikuti penggantian terjadwal bila pola pemakaiannya cukup stabil. Jangan mengganti komponen hanya karena jadwal tiba jika inspeksi, fungsi, dan manual tidak mendukung keputusan itu.

Run-to-failure memerlukan rencana sebelum gagal: identitas spare yang benar, waktu pengadaan yang masuk akal, alat dan kompetensi, cara menangani energi, serta batas kapan operasi harus dihentikan. Strategi ini tidak cocok untuk guard, interlock, perangkat proteksi, containment, atau aset yang kegagalannya dapat memicu kerusakan berantai. OSHA 1910.212 menempatkan machine guarding sebagai perlindungan terhadap bahaya mesin; detail guard dan restart tetap harus berasal dari desain serta prosedur spesifik lokasi ([OSHA 1910.212](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212)).

## Cara menentukan prioritas

Susun prioritas dengan urutan: konsekuensi, kemampuan mendeteksi, peluang kegagalan, waktu pemulihan, dan sumber daya. Konsekuensi keselamatan mengalahkan penghematan jangka pendek. Setelah itu bandingkan downtime terencana dengan downtime darurat, ketersediaan spare, kebutuhan keahlian, akses inspeksi, dan dampak ke aset lain. Pemilik aset yang ditunjuk harus menyetujui trade-off; teknisi tidak seharusnya mengubah klasifikasi sendirian.

Saat sumber daya terbatas, mulai dari failure mode yang paling merugikan, bukan dari mesin yang paling mudah diinspeksi. Tinjau backlog deferred defect setiap rapat perencanaan. Jika mode kegagalan berulang setelah corrective, hentikan pola “ganti bagian yang rusak” dan minta analisis penyebab, verifikasi alignment atau guarding, serta pemeriksaan independen yang relevan sebelum mengembalikan fungsi.

## Rekaman, serah terima, dan pemicu pemeriksaan ulang

Satu rekaman minimum harus menjawab: aset mana, masalah apa, kondisi dan data apa yang mendasari keputusan, pekerjaan apa yang dilakukan, parts mana yang terpasang, hasil verifikasi, siapa yang menyetujui, dan kapan pemeriksaan ulang dipicu. Handover juga perlu menyebut perubahan konfigurasi, batas operasi, pekerjaan tertunda, serta dokumen OEM atau statutory yang dipakai.

Picu peninjauan kembali ketika terjadi perubahan beban atau proses, relokasi, modifikasi, kegagalan berulang, perubahan personel, hasil inspeksi yang tidak konsisten, atau perubahan peraturan. Catatan lengkap membuat strategi dapat dikoreksi tanpa mengarang tren dari ingatan.

## Jalan pintas yang sering menggoda

Jalan pintasnya adalah memberi satu interval preventive untuk semua mesin, lalu menyebut aset lain “biarkan sampai rusak”. Ini gagal karena konsekuensi dan detectability tiap aset berbeda; pekerjaan terjadwal bisa tidak efektif, sedangkan kegagalan yang tampak murah dapat merusak sistem atau membuka energi berbahaya. Alternatif lebih aman adalah membuat klasifikasi aset, menautkan tiap keputusan pada bukti kondisi dan fungsi, lalu meminta tinjauan pemilik aset yang kompeten. Sobat Bengkel.co.id, bila bukti belum cukup, keputusan yang jujur adalah menahan persetujuan dan menandai kebutuhan pemeriksaan—bukan mengisi angka dengan tebakan.

## Kesimpulan

Preventive, predictive, corrective, dan run-to-failure bukan empat tingkat kematangan yang harus diterapkan seragam. Pilih berdasarkan konsekuensi kegagalan, kemampuan mendeteksi, kualitas data, peluang menjadwalkan downtime, spare, keterampilan, dan biaya siklus hidup. Untuk konteks tambahan tentang penanganan aset industri, lihat [perbaikan mesin dan komponen industri](/perbaikan-mesin-komponen-industri.html). Run-to-failure hanya dapat dipertimbangkan untuk aset non-kritis dengan pemulihan terkendali; aset safety-critical memerlukan persetujuan dan kontrol lebih ketat.

Langkah berikutnya: buat register aset, isi failure mode dan konsekuensinya, kumpulkan riwayat work order serta baseline inspeksi, lalu minta pemilik aset dan peninjau keselamatan memeriksa rancangan strategi. Anda dapat mulai dari [beranda Bengkel.co.id](/) untuk menata konteks pekerjaan, lalu kembali ke register aset sebelum rapat persetujuan. Jangan menetapkan interval, ambang alarm, keputusan restart, atau klaim kelayakan sebelum manual OEM, persyaratan Indonesia yang berlaku, prosedur tertulis, dan bukti aset-spesifik tersedia. Gunakan halaman utama Bengkel.co.id sebagai titik handover dokumen, bukan sebagai pengganti tinjauan teknis. Aturan operasinya sederhana: strategi boleh berubah mengikuti bukti, tetapi batas keselamatan tidak boleh dinegosiasikan.
