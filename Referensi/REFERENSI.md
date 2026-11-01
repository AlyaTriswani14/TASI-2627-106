# Referensi Proposal TASI-2627-106

Disusun ulang 1 November 2026 dari `Dokumen/proposal/references.bib` (52 entri aktif, semuanya disitasi di `Pendahuluan.tex`, `Landasan Teori.tex`, dan/atau `Metode Penelitian.tex`). Menggantikan versi lama dokumen ini, yang hanya memuat 33 entri dari kumpulan unduhan awal dan sebagian sudah tidak lagi dipakai di proposal.

## Petunjuk Membaca

| Butir | Keterangan |
|---|---|
| Struktur | Satu subbab per referensi, dikelompokkan ke dalam 6 kategori (A–F) yang sama dengan pengelompokan di `references.bib`. |
| Kunci BibTeX | Sama dengan kunci `\cite{...}` di berkas `.tex`; dipakai juga sebagai nama berkas PDF. |
| Berkas lokal | Path relatif dari folder `Referensi/`. Lihat [Berkas Entri Aktif](#berkas-entri-aktif) di bawah untuk penjelasan folder. |
| Dikutip di proposal | Daftar subbab tempat kunci ini disitasi, plus jumlah kemunculan `\cite{}` (satu `\cite{a,b}` dihitung 1 kali untuk `a` dan 1 kali untuk `b`). |
| Kegunaan untuk TA | Ditulis berdasarkan pembacaan langsung kalimat tempat referensi itu benar-benar dikutip di proposal (bukan ringkasan umum artikelnya) — menjelaskan peran spesifik referensi tersebut dalam argumen TA, bukan sekadar topik yang dibahasnya. |
| Penanda metadata | `[CEK]` = ada catatan ketidaksesuaian/ketidakpastian metadata, dijelaskan di baris Catatan. Rincian penuh ada di `Dokumen/proposal/references.bib` dan `Referensi/Daftar_Referensi_dan_Checklist_Unduhan.md`. |

**Ringkasan jumlah:** A. Regulasi (9) · B. Wawancara (2) · C. UMKM & transformasi digital (6) · D. Buku & teori SI (5) · E. LLM/RAG/penelitian terdahulu (22) · F. Metodologi & pengukuran (8) = **52 entri**. 50 di antaranya memiliki berkas PDF di `Referensi/entri-aktif/`; 2 transkrip wawancara adalah sumber primer internal tanpa berkas publik.

---

## A. Regulasi, Standar, dan Dokumen Pemerintah

### 1. Peraturan Pemerintah Nomor 7 Tahun 2021 tentang Kemudahan, Pelindungan, dan Pemberdayaan Koperasi dan Usaha Mikro, Kecil, dan Menengah

- **Kunci BibTeX:** `pp7tahun2021`
- **Lembaga:** Pemerintah Republik Indonesia
- **Tahun:** 2021
- **Jenis & Sumber:** Peraturan Pemerintah; Lembaran Negara RI 2021 No. 17, Jakarta
- **Berkas lokal:** [`entri-aktif/pp7tahun2021.pdf`](entri-aktif/pp7tahun2021.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §UMKM, Kewenangan Pembinaan, dan Tata Kelola Data; Metode Penelitian §Rancangan Evaluasi Kualitas Data (RQ3) — 3 sitasi
- **Kegunaan untuk TA:** Sumber definisi resmi kriteria modal/omzet yang membedakan usaha mikro, kecil, dan menengah (Pasal 35), dipakai di Landasan Teori untuk menjelaskan bahwa kesalahan klasifikasi skala usaha berimplikasi langsung pada kewenangan pembinaan dinas, dan di Metode Penelitian sebagai dasar aturan konsistensi atribut skala usaha pada pengukuran kualitas data (RQ3).

### 2. Peraturan Presiden Nomor 39 Tahun 2019 tentang Satu Data Indonesia

- **Kunci BibTeX:** `perpres39tahun2019`
- **Lembaga:** Pemerintah Republik Indonesia · **Tahun:** 2019
- **Jenis & Sumber:** Peraturan Presiden; Lembaran Negara RI 2019 No. 112, Jakarta
- **Berkas lokal:** [`entri-aktif/perpres39tahun2019.pdf`](entri-aktif/perpres39tahun2019.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §UMKM, Kewenangan Pembinaan, dan Tata Kelola Data — 2 sitasi
- **Kegunaan untuk TA:** Dasar kebijakan empat prinsip data pemerintah (standar data, metadata baku, interoperabilitas, kode referensi/data induk) yang dipakai di Landasan Teori sebagai argumen bahwa KBLI 2025 dan kode wilayah administratif berfungsi sebagai kode referensi bagi atribut lapangan usaha dan lokasi pada artefak.

### 3. Undang-Undang Nomor 27 Tahun 2022 tentang Pelindungan Data Pribadi

- **Kunci BibTeX:** `uupdp2022` · *(catatan `.bib`: [CEK] nomor LN belum dibuka dari naskah resmi)*
- **Lembaga:** Pemerintah Republik Indonesia · **Tahun:** 2022
- **Jenis & Sumber:** Undang-Undang; Lembaran Negara RI 2022 No. 196, Jakarta
- **Berkas lokal:** [`entri-aktif/uupdp2022.pdf`](entri-aktif/uupdp2022.pdf)
- **Dikutip di proposal:** Metode Penelitian §Kebutuhan Awal Artefak; §Etika Penelitian dan Pelindungan Data — 2 sitasi
- **Kegunaan untuk TA:** Dasar hukum yang membentuk kebutuhan nonfungsional KNF-02 (atribut data pribadi dipisahkan dan tidak dikirim ke layanan LLM eksternal) serta prosedur etika penelitian saat memproses data pelaku usaha yang memuat informasi pribadi.

### 4. Peraturan Badan Pusat Statistik Nomor 7 Tahun 2025 tentang Klasifikasi Baku Lapangan Usaha Indonesia

- **Kunci BibTeX:** `bps2025perban7`
- **Lembaga:** Badan Pusat Statistik · **Tahun:** 2025 (ditetapkan 17 Des 2025, berlaku 18 Des 2025)
- **Jenis & Sumber:** Peraturan BPS, Jakarta — mencabut Peraturan BPS No. 2 Tahun 2020
- **Berkas lokal:** [`entri-aktif/bps2025perban7.pdf`](entri-aktif/bps2025perban7.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §Klasifikasi Baku Lapangan Usaha Indonesia (2×); Metode Penelitian §Kerangka Berpikir; §Alat dan Bahan Penelitian — 5 sitasi
- **Kegunaan untuk TA:** Sumber taksonomi resmi KBLI 2025 yang menjadi target klasifikasi artefak — dasar penetapan bahwa KBLI 2025 menggantikan KBLI 2020, dan dipakai sebagai kamus kode (basis pengetahuan tahap *retrieval*) pada *pipeline* standardisasi di Metode Penelitian.

### 5. BPS: KBLI 2025 Permudah Klasifikasi Aktivitas Ekonomi Baru

- **Kunci BibTeX:** `bps2025kblisiaran`
- **Lembaga:** Badan Pusat Statistik · **Tahun:** 2025 (siaran pers 26 Des 2025)
- **Jenis & Sumber:** Berita dan Siaran Pers BPS
- **Berkas lokal:** [`entri-aktif/bps2025kblisiaran.pdf`](entri-aktif/bps2025kblisiaran.pdf) *(halaman web disimpan sebagai PDF)*
- **Dikutip di proposal:** Landasan Teori §Klasifikasi Baku Lapangan Usaha Indonesia (2×)
- **Kegunaan untuk TA:** Sumber rujukan ISIC Revisi 5 serta angka resmi struktur KBLI 2025 (22 kategori, 87 golongan pokok, 257 golongan, 519 subgolongan, 1.560 kelompok usaha) yang dipakai di Landasan Teori untuk menjelaskan struktur taksonomi berjenjang lima tingkat yang menjadi target klasifikasi artefak.

### 6. ISO/IEC 25012:2008 — Software Engineering – Software Product Quality Requirements and Evaluation (SQuaRE) – Data Quality Model

- **Kunci BibTeX:** `iso25012`
- **Lembaga:** International Organization for Standardization · **Tahun:** 2008
- **Jenis & Sumber:** Standar internasional ISO/IEC, edisi pertama (2008-12-15)
- **Berkas lokal:** [`entri-aktif/iso25012.pdf`](entri-aktif/iso25012.pdf)
- **Dikutip di proposal:** Pendahuluan §Prinsip Desain dan Hipotesis Penelitian; §Tujuan Penelitian; Landasan Teori §Model Kualitas Data; Metode Penelitian §Kerangka Berpikir; §Rancangan Evaluasi Kualitas Data (RQ3); §Rencana Luaran dan Publikasi — 6 sitasi
- **Kegunaan untuk TA:** Kerangka definisi empat dari enam dimensi kualitas data yang diuji pada H4 — kelengkapan, akurasi, konsistensi, dan kemutakhiran — dan salah satu teori kernel yang menurunkan prinsip desain (DP) penelitian ini bersama `delone2003success` dan `govuk2021dqdimensions`.

### 7. Meet the Data Quality Dimensions

- **Kunci BibTeX:** `govuk2021dqdimensions`
- **Lembaga:** Government Data Quality Hub (GOV.UK) · **Tahun:** 2021 (terbit Juni 2021)
- **Jenis & Sumber:** Artikel/*news story* GOV.UK
- **Berkas lokal:** [`entri-aktif/govuk2021dqdimensions.pdf`](entri-aktif/govuk2021dqdimensions.pdf) *(halaman web disimpan sebagai PDF)*
- **Dikutip di proposal:** sama dengan set subbab `iso25012` di atas — 6 sitasi
- **Kegunaan untuk TA:** Sumber definisi dua dimensi kualitas data tambahan yang tidak dicakup ISO/IEC 25012 — keunikan (ketiadaan duplikasi) dan validitas (kesesuaian terhadap domain nilai/aturan format) — melengkapi keenam dimensi kualitas data yang diuji pada H4.

### 8. Laporan Kinerja Instansi Pemerintah (LKjIP) Tahun Anggaran 2025

- **Kunci BibTeX:** `lkjip2025toba`
- **Lembaga:** Dinas Koperasi, Usaha Kecil Menengah, Perdagangan dan Perindustrian Kabupaten Toba · **Tahun:** 2026 (terbit) untuk TA 2025
- **Jenis & Sumber:** Laporan kinerja instansi; Pemerintah Kabupaten Toba, Balige
- **Berkas lokal:** [`entri-aktif/lkjip2025toba.pdf`](entri-aktif/lkjip2025toba.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang (4×); Metode Penelitian §Data Penelitian — 6 sitasi
- **Kegunaan untuk TA:** Sumber data empiris utama di Latar Belakang yang menunjukkan kesenjangan pembinaan UMKM Kabupaten Toba secara kuantitatif (realisasi 0,65% dari target 4,99%; 0 dari 76 koperasi dan 65 dari 10.032 UMKM terdata, hlm. 50 dan 107); angka 10.032 UMKM dari laporan ini juga dipakai di Metode Penelitian untuk menunjukkan ketidaksesuaian dengan keterangan staf (±12.000 unit) sebagai indikasi awal persoalan konsistensi/keunikan data.

### 9. Rencana Strategis (Renstra) Tahun 2025–2029

- **Kunci BibTeX:** `renstra2025toba`
- **Lembaga:** Dinas Koperasi, UKM, Perdagangan dan Perindustrian Kabupaten Toba · **Tahun:** 2025
- **Jenis & Sumber:** Dokumen rencana strategis; Pemerintah Kabupaten Toba, Balige
- **Berkas lokal:** [`entri-aktif/renstra2025toba.pdf`](entri-aktif/renstra2025toba.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Metode Penelitian §Kajian Awal Lingkungan Penelitian > Temuan Wawancara dan Implikasi Desain — 3 sitasi
- **Kegunaan untuk TA:** Bukti kelembagaan bahwa keterbatasan jumlah dan kapasitas aparat pendamping serta ketimpangan konektivitas internet antardesa diakui dalam dokumen perencanaan resmi, dan dasar arah kebijakan membangun basis data terpadu koperasi dan UMKM yang menjadi konteks kebutuhan artefak.

---

## B. Wawancara / Sumber Primer

### 10. Transkrip Wawancara dengan Kepala Dinas DKUKMPP Kabupaten Toba

- **Kunci BibTeX:** `wawancarakadis2026`
- **Lembaga/Informan:** Kepala Dinas Koperasi, UKM, Perdagangan dan Perindustrian Kabupaten Toba
- **Tahun:** 2026 (wawancara 23 Oktober 2026)
- **Jenis & Sumber:** Wawancara dengan Tim TASI-2627-106 dan TASI-2627-111, Kantor DKUKMPP Kabupaten Toba
- **Berkas lokal:** Tidak ada berkas publik — transkrip internal tim, tidak termasuk dalam unggahan referensi
- **Dikutip di proposal:** Pendahuluan §Latar Belakang (3×); Landasan Teori §Sistem Pendukung Keputusan dan Pemeringkatan Berbobot; Metode Penelitian §Kajian Awal Lingkungan Penelitian > Temuan Wawancara dan Implikasi Desain — 5 sitasi
- **Kegunaan untuk TA:** Sumber primer utama yang memperinci persoalan data UMKM di Kabupaten Toba (jumlah data ±12.000 unit, sumber ketidaksesuaian data) dan sifat semi-terstruktur persoalan seleksi UMKM sasaran pembinaan (kriteria terukur plus pertimbangan kebijakan pemerataan antarkecamatan) yang melandasi rancangan modul pendukung keputusan.

### 11. Transkrip Wawancara dengan Staf Bidang Koperasi dan UMKM DKUKMPP Kabupaten Toba

- **Kunci BibTeX:** `wawancarastaf2026`
- **Lembaga/Informan:** Staf Bidang Koperasi dan UMKM DKUKMPP Kabupaten Toba
- **Tahun:** 2026 (wawancara 23 Oktober 2026)
- **Jenis & Sumber:** Wawancara dengan Tim TASI-2627-106 dan TASI-2627-111, Kantor DKUKMPP Kabupaten Toba
- **Berkas lokal:** Tidak ada berkas publik — transkrip internal tim, tidak termasuk dalam unggahan referensi
- **Dikutip di proposal:** Pendahuluan §Latar Belakang (5×); §Prinsip Desain dan Hipotesis Penelitian; Landasan Teori §UMKM, Kewenangan Pembinaan; §Model Kualitas Data; Metode Penelitian §Kajian Awal Lingkungan Penelitian; §Data Penelitian (2×); §Pemilihan Pendekatan — 16 sitasi (referensi paling sering dikutip di seluruh proposal)
- **Kegunaan untuk TA:** Sumber primer paling banyak dirujuk — memperkuat hampir seluruh klaim empiris tentang kondisi lapangan: jumlah data UMKM ±12.000 unit, atribut jenis usaha berupa teks bebas yang diisi perangkat desa, siklus pemutakhiran data tiga bulanan, kategori "ultra mikro" dalam praktik dinas, penilaian staf bahwa pendampingan langsung lebih terjangkau daripada alat digital mandiri, serta dasar pemilihan aparatur (bukan pelaku UMKM) sebagai pengguna utama artefak.

---

## C. UMKM, Transformasi Digital, dan Adopsi Teknologi

### 12. Toward SMEs Digital Transformation Success: A Systematic Literature Review

- **Kunci BibTeX:** `sagala2024sme`
- **Penulis:** Sagala, Gaffar Hafiz; Őri, Dóra · **Tahun:** 2024
- **Jenis & Sumber:** *Information Systems and e-Business Management*, 22(4), 667–719 · **DOI:** [10.1007/s10257-024-00682-2](https://doi.org/10.1007/s10257-024-00682-2)
- **Berkas lokal:** [`entri-aktif/sagala2024sme.pdf`](entri-aktif/sagala2024sme.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang — 1 sitasi
- **Kegunaan untuk TA:** Dasar klaim di Latar Belakang bahwa digitalisasi UMKM sebaiknya dilaksanakan secara bertahap — argumen tinjauan sistematis ini sejalan dengan pandangan Kepala Dinas bahwa perubahan harus dilakukan pelan-pelan, memperkuat justifikasi pendekatan augmentasi bertahap pada artefak.

### 13. Generative Artificial Intelligence in Small and Medium Enterprises: Navigating its Promises and Challenges

- **Kunci BibTeX:** `rajaram2024genai` · *(catatan `.bib`: [CEK] DOI belum terlihat di ETH Research Collection/HBR)*
- **Penulis:** Rajaram, Kumaran; Tinguely, Patrick Nicolas · **Tahun:** 2024
- **Jenis & Sumber:** *Business Horizons*, 67(5), 629–648 · **DOI:** [10.1016/j.bushor.2024.05.008](https://doi.org/10.1016/j.bushor.2024.05.008)
- **Berkas lokal:** [`entri-aktif/rajaram2024genai.pdf`](entri-aktif/rajaram2024genai.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Metode Penelitian §Pemilihan Pendekatan — 2 sitasi
- **Kegunaan untuk TA:** Dasar argumen pemilihan pengguna artefak di Metode Penelitian — keberhasilan penerapan kecerdasan buatan generatif pada UMKM bergantung pada kompetensi dan kesiapan organisasi penggunanya, sehingga artefak ditujukan untuk memperkuat kapasitas aparatur sebagai pendamping, bukan langsung ke pelaku UMKM.

### 14. Artificial Intelligence and Management: The Automation–Augmentation Paradox

- **Kunci BibTeX:** `raisch2021automation`
- **Penulis:** Raisch, Sebastian; Krakowski, Sebastian · **Tahun:** 2021
- **Jenis & Sumber:** *Academy of Management Review*, 46(1), 192–210 · **DOI:** [10.5465/amr.2018.0072](https://doi.org/10.5465/amr.2018.0072)
- **Berkas lokal:** [`entri-aktif/raisch2021automation.pdf`](entri-aktif/raisch2021automation.pdf) — versi terbit UNIGE, 20 hlm. *(Ada versi naskah penulis 48 hlm. yang tidak dipakai; lihat [Berkas Entri Nonaktif](#berkas-entri-nonaktif).)*
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; §Prinsip Desain dan Hipotesis Penelitian; Metode Penelitian §Pemilihan Pendekatan — 3 sitasi
- **Kegunaan untuk TA:** Teori kernel prinsip augmentasi (bukan otomasi) yang menjadi dasar keputusan desain paling mendasar pada artefak — pembagian peran antara mesin dan manusia dirancang secara sadar, sehingga artefak memperkuat kapasitas aparatur sebagai pendamping dan keputusan akhir tetap di tangan pengguna manusia.

### 15. Leveraging Digital Technology in Micro SMEs to Enhance Indonesia's Economic Prosperity

- **Kunci BibTeX:** `utomo2024digital`
- **Penulis:** Utomo, Bambang; Setiyono, Yoyok Yekti · **Tahun:** 2024
- **Jenis & Sumber:** *Jurnal Lemhannas RI*, 12(3), 391–402 · **DOI:** [10.55960/jlri.v12i3.985](https://doi.org/10.55960/jlri.v12i3.985)
- **Berkas lokal:** [`entri-aktif/utomo2024digital.pdf`](entri-aktif/utomo2024digital.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang — 1 sitasi
- **Kegunaan untuk TA:** Dasar klaim bahwa belum adanya basis data UMKM yang terpadu merupakan salah satu hambatan pemanfaatan teknologi digital pada UMKM mikro di Indonesia — memperkuat argumen bahwa persoalan utamanya bukan hanya pada pelaku UMKM, melainkan juga pada infrastruktur informasi pemerintah daerah.

### 16. Digitalisasi UMKM: Edukasi Strategis dalam Penerapan Digital Marketing dan Legalitas Usaha Online di RW 04 Kelurahan Kejawan Putih Tambak, Surabaya

- **Kunci BibTeX:** `nadhifah2026digitalisasi` · *(catatan `.bib`: [CEK] DOI belum terlihat di halaman artikel)*
- **Penulis:** Nadhifah, Mei Dina Putri; Gani, Syarohbil Syawal Ahmad; Pratiwi, Al Viana Amelia; Rama, M. Atilla; Azizatunnafi'ah, Binti · **Tahun:** 2026
- **Jenis & Sumber:** *Rengganis Jurnal Pengabdian Masyarakat*, 6(1), 443–451 · **DOI (dugaan):** [10.29303/rengganis.v6i1.810](https://doi.org/10.29303/rengganis.v6i1.810)
- **Berkas lokal:** [`entri-aktif/nadhifah2026digitalisasi.pdf`](entri-aktif/nadhifah2026digitalisasi.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang — 1 sitasi
- **Kegunaan untuk TA:** Contoh program pendampingan pemasaran digital yang disertai pendaftaran NIB bagi pelaku UMKM di satu RW di Surabaya (25 UMKM terdata) — dipakai sebagai salah satu bukti bahwa upaya digitalisasi yang ada selama ini berfokus pada pelaku UMKM dan belum menyentuh persoalan data pada sisi pemerintah daerah.

### 17. Pemanfaatan Digital Marketing sebagai Media Pemasaran Tenun Ulos di Desa Sigaol Timur

- **Kunci BibTeX:** `naibaho2025ulos`
- **Penulis:** Naibaho, Krismanto Erick Tobush; Sianipar, Gloria J. M. · **Tahun:** 2025
- **Jenis & Sumber:** *Cakrawala: Jurnal Pengabdian Masyarakat Global*, 4(1), 137–143 · **DOI:** [10.30640/cakrawala.v4i1.3825](https://doi.org/10.30640/cakrawala.v4i1.3825) *(lihat catatan di bawah)*
- **Berkas lokal:** [`entri-aktif/naibaho2025ulos.pdf`](entri-aktif/naibaho2025ulos.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang — 1 sitasi
- **Catatan:** Pengecekan isi berkas (29 Okt 2026) menemukan DOI tercetak `...v4i1.3825`, berbeda dari `...v4i1.3852` yang tertulis di `references.bib` saat ini — perlu diperbaiki di `.bib` sebelum pengumpulan.
- **Kegunaan untuk TA:** Contoh program pendampingan pemasaran digital bagi penenun ulos di Kabupaten Toba sendiri — dipakai bersama `nadhifah2026digitalisasi` sebagai bukti bahwa upaya digitalisasi UMKM yang ada berfokus pada pelaku usaha, belum pada basis data pemerintah daerah.

---

## D. Buku dan Teori Sistem Informasi

### 18. Management Information Systems: Managing the Digital Firm

- **Kunci BibTeX:** `laudon2022mis` · ⚠️ **metadata `.bib` tidak sesuai berkas**
- **Penulis:** Laudon, Kenneth C.; Laudon, Jane P. · **Tahun (`.bib`):** 2022, edisi ke-17
- **Jenis & Sumber:** Buku ajar; Pearson, Harlow (Global Edition)
- **Berkas lokal:** [`entri-aktif/laudon2022mis.pdf`](entri-aktif/laudon2022mis.pdf) — **berkas yang tersedia adalah edisi ke-15 (© Pearson Education Limited 2018), bukan edisi ke-17/2022 yang tercatat di `.bib`.** Perbaiki salah satu sebelum pengumpulan.
- **Dikutip di proposal:** Landasan Teori §UMKM, Kewenangan Pembinaan, dan Tata Kelola Data; §Sistem Pendukung Keputusan dan Pemeringkatan Berbobot — 2 sitasi
- **Kegunaan untuk TA:** Sumber dua definisi inti di Landasan Teori: (1) nilai sistem informasi bagi pengambilan keputusan bergantung pada kualitas data di dalamnya, dan data yang tidak akurat/tepat waktu/konsisten menyebabkan keputusan keliru; (2) definisi sistem pendukung keputusan (SPK) sebagai dasar pembingkaian persoalan seleksi UMKM sasaran pembinaan sebagai persoalan semi-terstruktur.

### 19. The DeLone and McLean Model of Information Systems Success: A Ten-Year Update

- **Kunci BibTeX:** `delone2003success`
- **Penulis:** DeLone, William H.; McLean, Ephraim R. · **Tahun:** 2003
- **Jenis & Sumber:** *Journal of Management Information Systems*, 19(4), 9–30 · **DOI:** [10.1080/07421222.2003.11045748](https://doi.org/10.1080/07421222.2003.11045748)
- **Berkas lokal:** [`entri-aktif/delone2003success.pdf`](entri-aktif/delone2003success.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; §Prinsip Desain dan Hipotesis Penelitian; §Kontribusi Penelitian; Landasan Teori §Model Kesuksesan Sistem Informasi dan Kualitas Informasi — 4 sitasi
- **Kegunaan untuk TA:** **Teori kernel utama penelitian.** Model DeLone–McLean memosisikan komponen LLM terpandu *retrieval* sebagai mekanisme peningkatan kualitas informasi (diuji H1–H4) dan kinerja tugas/beban kerja pengguna sebagai indikator manfaat bersih tingkat individu (diuji H5) — kerangka inilah yang menjadi tulang punggung kontribusi teoretis TA ini.

### 20. Generative AI

- **Kunci BibTeX:** `feuerriegel2024genai`
- **Penulis:** Feuerriegel, Stefan; Hartmann, Jochen; Janiesch, Christian; Zschech, Patrick · **Tahun:** 2024
- **Jenis & Sumber:** *Business & Information Systems Engineering*, 66(1), 111–126 · **DOI:** [10.1007/s12599-023-00834-7](https://doi.org/10.1007/s12599-023-00834-7)
- **Berkas lokal:** [`entri-aktif/feuerriegel2024genai.pdf`](entri-aktif/feuerriegel2024genai.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §Model Kesuksesan Sistem Informasi — 2 sitasi
- **Kegunaan untuk TA:** Dasar pandangan bahwa kecerdasan buatan generatif perlu dianalisis sebagai entitas dalam sistem sosioteknis pada tingkat model, sistem, dan aplikasi — sehingga kualitas keluarannya dievaluasi bersama interaksinya dengan pengguna dan proses organisasi, bukan dari kinerja model saja (risiko halusinasi dan bias disebut eksplisit di sini).

### 21. "So What if ChatGPT Wrote It?" Multidisciplinary Perspectives on Opportunities, Challenges and Implications of Generative Conversational AI for Research, Practice and Policy

- **Kunci BibTeX:** `dwivedi2023chatgpt`
- **Penulis:** Dwivedi, Yogesh K.; Kshetri, Nir; Hughes, Laurie; dkk. · **Tahun:** 2023
- **Jenis & Sumber:** *International Journal of Information Management*, 71, 102642 · **DOI:** [10.1016/j.ijinfomgt.2023.102642](https://doi.org/10.1016/j.ijinfomgt.2023.102642)
- **Berkas lokal:** [`entri-aktif/dwivedi2023chatgpt.pdf`](entri-aktif/dwivedi2023chatgpt.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang (2×); Landasan Teori §Model Kesuksesan Sistem Informasi — 3 sitasi
- **Kegunaan untuk TA:** Kajian multidisiplin pendukung yang menekankan perlunya bukti empiris mengenai peluang dan risiko (halusinasi, bias, akuntabilitas) kecerdasan buatan generatif bagi praktik dan kebijakan — memperkuat posisi TA ini sebagai pengujian empiris, bukan klaim normatif.

### 22. The Uneven Impact of Generative Artificial Intelligence on Entrepreneurial Performance: Evidence from a Field Experiment in Kenya

- **Kunci BibTeX:** `otis2026uneven` · *(catatan `.bib`: [TERVERIFIKASI] DOI INFORMS; volume/halaman "Articles in Advance" belum final)*
- **Penulis:** Otis, Nicholas G.; Clarke, Rowan; Delecourt, Solène; Holtz, David; Koning, Rembrand · **Tahun:** 2026
- **Jenis & Sumber:** *Management Science* · **DOI:** [10.1287/mnsc.2024.06909](https://doi.org/10.1287/mnsc.2024.06909)
- **Berkas lokal:** [`entri-aktif/otis2026uneven.pdf`](entri-aktif/otis2026uneven.pdf) — versi *preprint* eScholarship, 37 hlm. *(Ada versi INFORMS Articles in Advance 18 hlm. yang tidak dipakai; lihat [Berkas Entri Nonaktif](#berkas-entri-nonaktif).)*
- **Dikutip di proposal:** Pendahuluan §Latar Belakang — 1 sitasi
- **Kegunaan untuk TA:** Bukti lapangan kuat bahwa manfaat kecerdasan buatan generatif tidak seragam — uji lapangan acak pada 640 wirausaha Kenya tidak menemukan dampak rata-rata signifikan dari asisten GPT-4, dengan kinerja menurun pada wirausaha berkinerja rendah dan meningkat pada yang berkinerja tinggi — argumen inti bahwa efektivitas komponen LLM harus diuji empiris dalam konteksnya, tidak dapat disimpulkan dari tolok ukur umum.

---

## E. LLM, Anotasi, RAG, dan Penelitian Terdahulu

### 23. Large Language Models to Analyze Business Intelligence User Narratives

- **Kunci BibTeX:** `lotfipoor2026llm`
- **Penulis:** Lotfipoor, Ashkan; Fakhimi, Masoud; Hagen-Zanker, Alex; Showell, David · **Tahun:** 2026 (terbit daring 3 Feb 2026)
- **Jenis & Sumber:** *Journal of Computer Information Systems* · **DOI:** [10.1080/08874417.2026.2613938](https://doi.org/10.1080/08874417.2026.2613938)
- **Berkas lokal:** [`entri-aktif/lotfipoor2026llm.pdf`](entri-aktif/lotfipoor2026llm.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; §Kontribusi Penelitian; Landasan Teori §Klasifikasi Baku Lapangan Usaha Indonesia; §Penelitian Terdahulu (Tabel, No. 1); Metode Penelitian §Kerangka Berpikir; §Rencana Luaran dan Publikasi — 6 sitasi
- **Hasil (tabel Penelitian Terdahulu):** GPT-4 untuk ekstraksi variabel dan klasifikasi 2.865 narasi *business intelligence* ke UK SIC; kesepakatan dengan konsensus manusia κ = 0,63–0,74; instruksi eksplisit menurunkan halusinasi dari 12% menjadi 4%. **Kekurangan:** narasi berbahasa Inggris yang dikurasi vendor; validasi klasifikasi industri hanya melalui inspeksi manual.
- **Kegunaan untuk TA:** **Pembanding metodologis terdekat dari sisi teknik.** Penelitian ini secara eksplisit disebut sebagai yang diperluas kajiannya (Kontribusi Penelitian) — TA ini menggantikan validasi manual Lotfipoor dkk. dengan data acuan beranotasi dan pengukuran halusinasi yang lebih sistematis, serta beralih dari klasifikasi industri UK SIC ke taksonomi KBLI berjenjang Indonesia. Catatan bahwa skema klasifikasi baku tidak selalu menangkap nuansa sektor hibrida juga dirujuk di Landasan Teori.

### 24. Business Description Categorization to the Five-Digit Indonesian Standard Classification of Business Field (KBLI) Using Machine Learning and Transfer Learning

- **Kunci BibTeX:** `amnur2025kbli`
- **Penulis:** Amnur, M. A.; Gazali, L. O. M.; Siregar, A. M.; dkk. (15 penulis) · **Tahun:** 2025
- **Jenis & Sumber:** *Proceedings of the International Conference on Data Science and Official Statistics (ICDSOS)* 2025(1), 558–575 · **DOI:** [10.34123/icdsos.v2025i1.719](https://doi.org/10.34123/icdsos.v2025i1.719)
- **Berkas lokal:** [`entri-aktif/amnur2025kbli.pdf`](entri-aktif/amnur2025kbli.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §Klasifikasi Baku Lapangan Usaha Indonesia; §Penelitian Terdahulu (Tabel, No. 2); Metode Penelitian §Pemilihan Pendekatan; §Rancangan Eksperimen Standardisasi (RQ2) — 5 sitasi
- **Hasil (tabel Penelitian Terdahulu):** SVM, *Random Forest*, dan IndoBERT untuk klasifikasi deskripsi usaha ke KBLI lima digit; F1-*score* 92,99% pada data sintetis, tetapi akurasi *top-1* hanya 32,93% dan *top-10* 63,24% pada data riil. **Kekurangan:** kesenjangan besar sintetis–riil; disusun atas KBLI sebelum 2025; belum memanfaatkan LLM generatif dengan *retrieval*.
- **Kegunaan untuk TA:** **Bukti celah pengetahuan utama yang memotivasi TA ini.** Penurunan kinerja tajam dari data sintetis ke data riil pada pendekatan pembelajaran mesin terawasi menjadi alasan langsung pemilihan LLM terpandu *retrieval* (bukan ML klasik) di Metode Penelitian, dan kesulitan utama klasifikasi KBLI (jumlah kelas besar, kemiripan uraian antarkelas, beda bahasa resmi vs bahasa pelaku usaha) dirujuk di Landasan Teori.

### 25. ChatGPT Outperforms Crowd Workers for Text-Annotation Tasks

- **Kunci BibTeX:** `gilardi2023chatgpt`
- **Penulis:** Gilardi, Fabrizio; Alizadeh, Meysam; Kubli, Maël · **Tahun:** 2023
- **Jenis & Sumber:** *Proceedings of the National Academy of Sciences*, 120(30), e2305016120 · **DOI:** [10.1073/pnas.2305016120](https://doi.org/10.1073/pnas.2305016120)
- **Berkas lokal:** [`entri-aktif/gilardi2023chatgpt.pdf`](entri-aktif/gilardi2023chatgpt.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §*Large Language Model*; §Penelitian Terdahulu (Tabel, No. 5); Metode Penelitian §Pemilihan Pendekatan — 4 sitasi
- **Hasil (tabel Penelitian Terdahulu):** LLM *zero-shot* sebagai anotator teks dengan akurasi ~25 poin persentase melampaui pekerja *crowdsourcing*, dengan biaya jauh lebih rendah. **Kekurangan:** teks berbahasa Inggris; tidak menggunakan taksonomi resmi bertingkat.
- **Kegunaan untuk TA:** Bukti awal kelayakan LLM sebagai anotator/pengode teks — menjadi salah satu dasar argumen bahwa LLM tidak memerlukan data latih berlabel dalam jumlah besar dan mampu memahami parafrasa (dipakai langsung di Metode Penelitian §Pemilihan Pendekatan), meski keterbatasannya pada bahasa Inggris dan absennya taksonomi berjenjang menjadi celah yang diisi TA ini.

### 26. Can Large Language Models Transform Computational Social Science?

- **Kunci BibTeX:** `ziems2024css`
- **Penulis:** Ziems, Caleb; Held, William; Shaikh, Omar; Chen, Jiaao; Zhang, Zhehao; Yang, Diyi · **Tahun:** 2024
- **Jenis & Sumber:** *Computational Linguistics*, 50(1), 237–291 · **DOI:** [10.1162/coli_a_00502](https://doi.org/10.1162/coli_a_00502)
- **Berkas lokal:** [`entri-aktif/ziems2024css.pdf`](entri-aktif/ziems2024css.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §*Large Language Model*; §Penelitian Terdahulu (Tabel, No. 6); Metode Penelitian §Pemilihan Pendekatan — 4 sitasi
- **Hasil (tabel Penelitian Terdahulu):** Evaluasi 13 model pada ~25 tolok ukur ilmu sosial komputasional; LLM belum melampaui model terlatih khusus pada tugas klasifikasi, tetapi kesepakatan dengan anotator manusia cukup memadai untuk dipakai berdampingan dengan tim anotator manusia. **Kekurangan:** teks berbahasa Inggris; tidak menggunakan taksonomi resmi bertingkat.
- **Kegunaan untuk TA:** Penyeimbang klaim optimistis `gilardi2023chatgpt` — menunjukkan bahwa LLM layak sebagai alat bantu klasifikasi, bukan pengganti penuh model terlatih khusus; dipakai bersama `gilardi2023chatgpt` di Metode Penelitian sebagai dasar klaim bahwa LLM mampu memahami parafrasa tanpa data latih besar.

### 27. Can Foundation Models Wrangle Your Data?

- **Kunci BibTeX:** `narayan2022wrangle` · *(catatan `.bib`: [TERVERIFIKASI] PVLDB 16(4):738–746; tahun diperbaiki 2022→2023, kunci dipertahankan)*
- **Penulis:** Narayan, Avanika; Chami, Ines; Orr, Laurel; Ré, Christopher · **Tahun:** 2023
- **Jenis & Sumber:** *Proceedings of the VLDB Endowment*, 16(4), 738–746 · **DOI:** [10.14778/3574245.3574258](https://doi.org/10.14778/3574245.3574258)
- **Berkas lokal:** [`entri-aktif/narayan2022wrangle.pdf`](entri-aktif/narayan2022wrangle.pdf) — berkas yang tersedia adalah *preprint* arXiv:2205.09911v2 (5 penulis, termasuk Simran Arora), bukan versi terbit PVLDB (4 penulis) yang dicatat `.bib`; isi inti sama.
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §LLM untuk Pembersihan dan Integrasi Data; §Penelitian Terdahulu (Tabel, No. 7) — 3 sitasi
- **Hasil (tabel Penelitian Terdahulu):** Tugas pembersihan dan integrasi data (termasuk pencocokan entitas dan koreksi kesalahan) dibingkai sebagai tugas *prompting*; LLM mencapai kinerja kompetitif tanpa pelatihan khusus. **Kekurangan:** tantangan pada data privat dan domain khusus.
- **Kegunaan untuk TA:** Dasar preseden bahwa tugas pengelolaan data administratif (sejenis standardisasi KBLI) dapat dibingkai sebagai tugas *prompting* LLM tanpa pelatihan ulang — memperkuat kelayakan pendekatan LLM terpandu *retrieval* yang dipilih TA ini, dengan catatan tantangan pada data domain khusus yang relevan dengan data UMKM.

### 28. Entity Matching using Large Language Models

- **Kunci BibTeX:** `peeters2025entity`
- **Penulis:** Peeters, Ralph; Steiner, Aaron; Bizer, Christian · **Tahun:** 2025
- **Jenis & Sumber:** *Proceedings of the 28th International Conference on Extending Database Technology (EDBT)*, 529–541 · **DOI:** [10.48786/edbt.2025.42](https://doi.org/10.48786/edbt.2025.42)
- **Berkas lokal:** [`entri-aktif/peeters2025entity.pdf`](entri-aktif/peeters2025entity.pdf)
- **Dikutip di proposal:** Landasan Teori §LLM untuk Pembersihan dan Integrasi Data; §Penelitian Terdahulu (Tabel, No. 8) — 2 sitasi
- **Hasil (tabel Penelitian Terdahulu):** LLM untuk pencocokan entitas; tidak ada satu *prompt* terbaik untuk seluruh model dan data. **Kekurangan:** menggunakan data tolok ukur publik, bukan data administratif riil.
- **Kegunaan untuk TA:** Peringatan metodologis bahwa rancangan *prompt* perlu disesuaikan dan dievaluasi per model dan per data — relevan sebagai dasar keputusan TA ini untuk menguji beberapa model LLM (bukan berasumsi satu *prompt* optimal untuk semuanya) pada eksperimen standardisasi (RQ2).

### 29. Enhancing Small and Medium Enterprises: A Hybrid Clustering and AHP-TOPSIS Decision Support Framework

- **Kunci BibTeX:** `khotimah2024hybrid`
- **Penulis:** Khotimah, B. K.; Anamisa, D. R.; Kustiyahningsih, Y.; Fauziah, A. N.; Setiawan, E. · **Tahun:** 2024
- **Jenis & Sumber:** *Ingénierie des Systèmes d'Information*, 29(1), 313–321 · **DOI:** [10.18280/isi.290131](https://doi.org/10.18280/isi.290131)
- **Berkas lokal:** [`entri-aktif/khotimah2024hybrid.pdf`](entri-aktif/khotimah2024hybrid.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §Sistem Pendukung Keputusan dan Pemeringkatan Berbobot; §Penelitian Terdahulu (Tabel, No. 9); Metode Penelitian §Pemilihan Pendekatan — 4 sitasi
- **Hasil (tabel Penelitian Terdahulu):** Klasterisasi dan AHP-TOPSIS untuk stratifikasi dan penetapan prioritas UMKM. **Kekurangan:** mengasumsikan data UMKM telah tersedia dan bersih — tidak membahas standardisasi data mentah.
- **Kegunaan untuk TA:** **Alasan langsung pembatasan cakupan modul pendukung keputusan TA ini.** Karena pendekatan Khotimah dkk. bekerja pada data yang sudah bersih dan tidak membahas standardisasinya, TA ini sengaja membatasi pemeringkatan pada penjumlahan terbobot sederhana (bukan AHP-TOPSIS) dan memfokuskan kontribusi pada penghimpunan serta standardisasi data mentah, bukan pada metode pemeringkatannya.

### 30. Adaptive Retrieval-Augmented Generation with Domain Specific Fine Tuning for Smart MSME Digital Transformation

- **Kunci BibTeX:** `hardiyanti2026adaptive`
- **Penulis:** Hardiyanti, M.; Wijono, S. H.; Sedjati, D. P. · **Tahun:** 2026
- **Jenis & Sumber:** *Journal of Applied Informatics and Computing*, 10(3), 2648–2654 · **DOI:** [10.30871/jaic.v10i3.12924](https://doi.org/10.30871/jaic.v10i3.12924)
- **Berkas lokal:** [`entri-aktif/hardiyanti2026adaptive.pdf`](entri-aktif/hardiyanti2026adaptive.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §Penelitian Terdahulu (Tabel, No. 10) — 2 sitasi
- **Hasil (tabel Penelitian Terdahulu):** *Adaptive* RAG dan IndoBERT via WhatsApp untuk pelaku UMKM; akurasi jawaban 86,8%, skor SUS 84,6 pada validasi lapangan 200 UMKM. **Kekurangan:** berorientasi swalayan pelaku UMKM; tidak menangani data pada sisi pemerintah.
- **Kegunaan untuk TA:** **Pembanding terdekat di Indonesia.** Satu-satunya pembanding yang juga memakai RAG untuk UMKM Indonesia — TA ini secara eksplisit memposisikan diri sebagai pelengkap, bukan pengulang: Hardiyanti dkk. melayani pelaku UMKM langsung sebagai asisten konsultasi, sedangkan TA ini menyasar aparatur dinas untuk menstandardisasi data administratif sisi pemerintah yang belum disentuh penelitian ini.

### 31. Enhancing E-Government Services through State-of-the-Art, Modular, and Reproducible Architecture over Large Language Models

- **Kunci BibTeX:** `papageorgiou2024egov`
- **Penulis:** Papageorgiou, G.; Sarlis, V.; Maragoudakis, M.; Tjortjis, C. · **Tahun:** 2024
- **Jenis & Sumber:** *Applied Sciences*, 14(18), 8259 · **DOI:** [10.3390/app14188259](https://doi.org/10.3390/app14188259)
- **Berkas lokal:** [`entri-aktif/papageorgiou2024egov.pdf`](entri-aktif/papageorgiou2024egov.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §Penelitian Terdahulu (Tabel, No. 11) — 2 sitasi
- **Hasil (tabel Penelitian Terdahulu):** Arsitektur modular berbasis RAG untuk layanan pemerintahan elektronik yang dapat direproduksi. **Kekurangan:** penulis sendiri menyatakan perlunya validasi empiris.
- **Kegunaan untuk TA:** Bukti celah pengetahuan kedua yang memotivasi TA ini — arsitektur RAG modular untuk e-*government* sudah diusulkan secara konseptual, tetapi belum divalidasi empiris; TA ini mengisi celah itu dengan pengujian empiris pada konteks data administratif UMKM di pemerintah daerah.

### 32. Evaluasi Metode Retrieval pada Chatbot Domain Khusus Berbasis Retrieval-Augmented Generation

- **Kunci BibTeX:** `asmaidin2026retrieval` · *(catatan `.bib`: [TERVERIFIKASI] 29 Okt 2026)*
- **Penulis:** Asmaidin; Santoso, Cahyono Budy · **Tahun:** 2026 (terbit 23 Jan 2026)
- **Jenis & Sumber:** *JSAI: Journal Scientific and Applied Informatics*, 9(1), 105–111 · **DOI:** [10.36085/jsai.v9i1.9897](https://doi.org/10.36085/jsai.v9i1.9897)
- **Berkas lokal:** [`entri-aktif/asmaidin2026retrieval.pdf`](entri-aktif/asmaidin2026retrieval.pdf)
- **Dikutip di proposal:** Landasan Teori §*Retrieval-Augmented Generation*; §Penelitian Terdahulu (Tabel, No. 12) — 2 sitasi
- **Hasil (tabel Penelitian Terdahulu):** Perbandingan *retrieval* leksikal, semantik, dan hibrida pada RAG; leksikal unggul pada peringkat teratas, hibrida meningkatkan cakupan pada peringkat menengah. **Kekurangan:** domain dokumen teknis, tidak terkait klasifikasi taksonomi.
- **Kegunaan untuk TA:** **Dasar langsung pemilihan strategi *retrieval* hibrida.** Temuan bahwa *retrieval* leksikal unggul di peringkat atas sementara hibrida memperluas cakupan di peringkat menengah dipakai persis sebagai alasan desain komponen *retriever* hibrida TA ini — relevan karena uraian resmi KBLI memuat istilah baku, sedangkan deskripsi usaha di lapangan memuat sinonim dan istilah lokal.

### 33. A Multi-Stage Framework with Taxonomy-Guided Reasoning for Occupation Classification Using Large Language Models

- **Kunci BibTeX:** `achananuparp2025occupation` · *(catatan `.bib`: [TERVERIFIKASI] 29 Okt 2026, ICWSM 2026)*
- **Penulis:** Achananuparp, Palakorn; Lim, Ee-Peng · **Tahun:** 2026
- **Jenis & Sumber:** *Proceedings of the International AAAI Conference on Web and Social Media (ICWSM)*, 20(1), 2–30 · **DOI:** [10.1609/icwsm.v20i1.42622](https://doi.org/10.1609/icwsm.v20i1.42622)
- **Berkas lokal:** [`entri-aktif/achananuparp2025occupation.pdf`](entri-aktif/achananuparp2025occupation.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §*Retrieval-Augmented Generation*; §Penelitian Terdahulu (Tabel, No. 4); Metode Penelitian §Pemilihan Pendekatan — 4 sitasi
- **Hasil (tabel Penelitian Terdahulu):** Kerangka bertahap inferensi, *retrieval*, dan pemeringkatan ulang LLM pada taksonomi O\*NET-SOC; penalaran berpanduan taksonomi menyelaraskan keluaran LLM dengan taksonomi berjenjang. **Kekurangan:** domain pekerjaan berbahasa Inggris; belum diuji pada data administratif pemerintah daerah.
- **Kegunaan untuk TA:** **Pola rancangan utama yang diadaptasi langsung.** Pola "inferensi LLM → *retrieval* → pemeringkatan ulang" pada taksonomi berjenjang inilah yang diterapkan TA ini untuk klasifikasi KBLI (*retriever* hibrida mengambil kandidat, LLM memilih satu kode atau menyatakan informasi tidak cukup) — bedanya, TA ini menguji pola tersebut pada domain berbahasa Indonesia dan data administratif pemerintah daerah yang belum pernah diuji Achananuparp & Lim.

### 34. Survey of Hallucination in Natural Language Generation

- **Kunci BibTeX:** `ji2023hallucination` · ⚠️ **daftar penulis `.bib` tidak sesuai berkas versi terbit** *(lihat [Daftar_Referensi_dan_Checklist_Unduhan.md](Daftar_Referensi_dan_Checklist_Unduhan.md) untuk rincian 10 vs 13 penulis)*
- **Penulis:** Ji, Ziwei; Lee, Nayeon; Frieske, Rita; dkk. · **Tahun:** 2023
- **Jenis & Sumber:** *ACM Computing Surveys*, 55(12), Artikel 248, 1–38 · **DOI:** [10.1145/3571730](https://doi.org/10.1145/3571730)
- **Berkas lokal:** [`entri-aktif/ji2023hallucination.pdf`](entri-aktif/ji2023hallucination.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; §Prinsip Desain dan Hipotesis Penelitian; Landasan Teori §*Large Language Model*; Metode Penelitian §Pemilihan Pendekatan — 4 sitasi
- **Kegunaan untuk TA:** Sumber definisi risiko utama penggunaan LLM — halusinasi — yang menjadi salah satu dari dua literatur LLM/RAG yang menurunkan prinsip desain (DP) penelitian ini (bersama `gao2023ragsurvey`), dan alasan langsung pembatasan LLM hanya memilih dari kandidat hasil *retrieval* kamus KBLI resmi (bukan menghasilkan kode dari ingatan parametriknya).

### 35. Large Legal Fictions: Profiling Legal Hallucinations in Large Language Models

- **Kunci BibTeX:** `dahl2024legal`
- **Penulis:** Dahl, Matthew; Magesh, Varun; Suzgun, Mirac; Ho, Daniel E. · **Tahun:** 2024
- **Jenis & Sumber:** *Journal of Legal Analysis*, 16(1), 64–93 · **DOI:** [10.1093/jla/laae003](https://doi.org/10.1093/jla/laae003)
- **Berkas lokal:** [`entri-aktif/dahl2024legal.pdf`](entri-aktif/dahl2024legal.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §*Large Language Model*; Metode Penelitian §Pemilihan Pendekatan — 3 sitasi
- **Kegunaan untuk TA:** Bukti kuantitatif tingkat halusinasi tinggi (58%–88% respons, bergantung model) pada domain yang menuntut rujukan sumber resmi (putusan pengadilan AS) — dipakai sebagai analogi langsung bahwa kondisi ini serupa dengan pengodean KBLI, memperkuat alasan membatasi pilihan LLM pada kandidat hasil *retrieval* dari kamus resmi.

### 36. Retrieval-Augmented Generation for Large Language Models: A Survey

- **Kunci BibTeX:** `gao2023ragsurvey`
- **Penulis:** Gao, Yunfan; Xiong, Yun; Gao, Xinyu; dkk. (10 penulis) · **Tahun:** 2023 (berkas: arXiv:2312.10997v5, 27 Mar 2024)
- **Jenis & Sumber:** arXiv *preprint* · **arXiv:** [2312.10997](https://arxiv.org/abs/2312.10997)
- **Berkas lokal:** [`entri-aktif/gao2023ragsurvey.pdf`](entri-aktif/gao2023ragsurvey.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; §Prinsip Desain dan Hipotesis Penelitian; Landasan Teori §*Retrieval-Augmented Generation*; Metode Penelitian §Pemilihan Pendekatan; §Kerangka Berpikir — 5 sitasi
- **Kegunaan untuk TA:** **Definisi dasar arsitektur RAG yang dipakai TA ini** (komponen *retriever* + generator LLM) dan sumber klaim bahwa RAG mengurangi kesalahan faktual serta memungkinkan pembaruan pengetahuan tanpa pelatihan ulang — salah satu dari dua literatur LLM/RAG yang menurunkan prinsip desain (DP) penelitian bersama `ji2023hallucination`.

### 37. A Systematic Review of Key Retrieval-Augmented Generation (RAG) Systems: Progress, Gaps, and Future Directions

- **Kunci BibTeX:** `oche2025rag`
- **Penulis:** Oche, Agada Joseph; Folashade, Ademola Glory; Ghosal, Tirthankar; Biswas, Arpan · **Tahun:** 2025
- **Jenis & Sumber:** arXiv *preprint* (v1, 25 Jul 2025) · **arXiv:** [2507.18910](https://arxiv.org/abs/2507.18910)
- **Berkas lokal:** [`entri-aktif/oche2025rag.pdf`](entri-aktif/oche2025rag.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; Landasan Teori §*Retrieval-Augmented Generation* — 2 sitasi
- **Kegunaan untuk TA:** Sumber klaim bahwa kualitas tahap *retrieval* merupakan penentu utama kualitas keluaran akhir sistem RAG — dasar argumen di Landasan Teori mengapa TA ini mengukur kualitas tahap *retrieval* secara terpisah (metrik *Recall@k*) dari kualitas keluaran akhir LLM.

### 38. Agentic Retrieval-Augmented Generation: A Survey on Agentic RAG

- **Kunci BibTeX:** `singh2025agentic`
- **Penulis:** Singh, Aditi; Ehtesham, Abul; Kumar, Saket; Khoei, Tala Talaei; Vasilakos, Athanasios V. · **Tahun:** 2025
- **Jenis & Sumber:** arXiv *preprint* (v4, 1 Apr 2026) · **arXiv:** [2501.09136](https://arxiv.org/abs/2501.09136)
- **Berkas lokal:** [`entri-aktif/singh2025agentic.pdf`](entri-aktif/singh2025agentic.pdf)
- **Dikutip di proposal:** Landasan Teori §*Retrieval-Augmented Generation* — 1 sitasi
- **Kegunaan untuk TA:** **Secara eksplisit ditempatkan sebagai pekerjaan lanjutan, bukan bagian cakupan TA ini** — arsitektur RAG agentik disebut sebagai arah pengembangan berikutnya yang dipertimbangkan tetapi tidak termasuk dalam cakupan penelitian ini (lihat Subbab Ruang Lingkup).

### 39. Large Language Models for Data Annotation and Synthesis: A Survey

- **Kunci BibTeX:** `tan2024annotation`
- **Penulis:** Tan, Zhen; Li, Dawei; Wang, Song; dkk. (10 penulis) · **Tahun:** 2024
- **Jenis & Sumber:** *Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing (EMNLP)*, 930–957 · **DOI:** [10.18653/v1/2024.emnlp-main.54](https://doi.org/10.18653/v1/2024.emnlp-main.54)
- **Berkas lokal:** [`entri-aktif/tan2024annotation.pdf`](entri-aktif/tan2024annotation.pdf)
- **Dikutip di proposal:** Landasan Teori §*Large Language Model* — 1 sitasi
- **Kegunaan untuk TA:** Sumber penegasan bahwa kualitas anotasi LLM bergantung pada rancangan *prompt*, ketersediaan contoh, dan mekanisme verifikasi manusia — melandasi keputusan TA ini untuk memvalidasi keluaran LLM terhadap data acuan beranotasi manusia, bukan menerima keluaran model begitu saja.

### 40. Chain-of-Thought Prompting Elicits Reasoning in Large Language Models

- **Kunci BibTeX:** `wei2022cot`
- **Penulis:** Wei, Jason; Wang, Xuezhi; Schuurmans, Dale; dkk. (9 penulis) · **Tahun:** 2022
- **Jenis & Sumber:** *Advances in Neural Information Processing Systems*, 35, 24824–24837
- **Berkas lokal:** [`entri-aktif/wei2022cot.pdf`](entri-aktif/wei2022cot.pdf)
- **Dikutip di proposal:** Landasan Teori §*Large Language Model* — 1 sitasi
- **Kegunaan untuk TA:** Dasar teknik permintaan penjelasan singkat atas keputusan model (*chain-of-thought*) yang dapat meningkatkan kualitas penalaran sekaligus menyediakan jejak alasan yang dapat diperiksa verifikator manusia — relevan untuk merancang *prompt* standardisasi KBLI yang dapat diaudit.

### 41. Cendol: Open Instruction-tuned Generative Large Language Models for Indonesian Languages

- **Kunci BibTeX:** `cahyawijaya2024cendol`
- **Penulis:** Cahyawijaya, Samuel; Lovenia, Holy; Koto, Fajri; dkk. (16 penulis) · **Tahun:** 2024
- **Jenis & Sumber:** *Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)*, 14899–14914
- **Berkas lokal:** [`entri-aktif/cahyawijaya2024cendol.pdf`](entri-aktif/cahyawijaya2024cendol.pdf)
- **Dikutip di proposal:** Landasan Teori §*Large Language Model* — 1 sitasi
- **Kegunaan untuk TA:** Dasar klaim bahwa kinerja LLM pada bahasa Indonesia dan bahasa daerah masih lebih rendah dibandingkan bahasa Inggris — argumen penting mengapa TA ini perlu menguji LLM secara empiris pada data UMKM berbahasa Indonesia, bukan berasumsi hasil penelitian berbahasa Inggris berlaku langsung.

### 42. Why Johnny Can't Prompt: How Non-AI Experts Try (and Fail) to Design LLM Prompts

- **Kunci BibTeX:** `zamfirescu2023johnny`
- **Penulis:** Zamfirescu-Pereira, J. D.; Wong, Richmond Y.; Hartmann, Björn; Yang, Qian · **Tahun:** 2023
- **Jenis & Sumber:** *Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems*, Artikel 437 · **DOI:** [10.1145/3544548.3581388](https://doi.org/10.1145/3544548.3581388)
- **Berkas lokal:** [`entri-aktif/zamfirescu2023johnny.pdf`](entri-aktif/zamfirescu2023johnny.pdf)
- **Dikutip di proposal:** Landasan Teori §*Large Language Model* — 1 sitasi
- **Kegunaan untuk TA:** Dasar keputusan desain antarmuka artefak — pengguna non-ahli cenderung menyusun *prompt* secara coba-coba dan tidak sistematis, sehingga interaksi LLM bagi aparatur desa dan dinas sebaiknya dibungkus dalam alur kerja terstruktur, bukan antarmuka percakapan bebas.

### 43. RAGAs: Automated Evaluation of Retrieval Augmented Generation

- **Kunci BibTeX:** `es2024ragas`
- **Penulis:** Es, Shahul; James, Jithin; Espinosa-Anke, Luis; Schockaert, Steven · **Tahun:** 2024
- **Jenis & Sumber:** *Proceedings of the 18th Conference of the European Chapter of the ACL: System Demonstrations*, 150–158
- **Berkas lokal:** [`entri-aktif/es2024ragas.pdf`](entri-aktif/es2024ragas.pdf)
- **Dikutip di proposal:** Landasan Teori §*Retrieval-Augmented Generation* — 1 sitasi
- **Kegunaan untuk TA:** Sumber pembanding metrik evaluasi — metrik *Recall@k* yang dipakai TA ini untuk mengukur kualitas tahap *retrieval* disebut sejalan dengan metrik *context recall* pada kerangka evaluasi RAGAS, memberi TA ini rujukan standar industri untuk metrik yang dipilih.

### 44. BEACON: A Tool for Industry Self-Classification in the Economic Census

- **Kunci BibTeX:** `dumbacher2025beacon`
- **Penulis:** Dumbacher, Brian; Whitehead, Daniel; Jeong, Jiseok; Pfeiff, Sarah · **Tahun:** 2025
- **Jenis & Sumber:** *Journal of Data Science*, 23(2), 429–448 · **DOI:** [10.6339/25-JDS1180](https://doi.org/10.6339/25-JDS1180)
- **Berkas lokal:** [`entri-aktif/dumbacher2025beacon.pdf`](entri-aktif/dumbacher2025beacon.pdf)
- **Dikutip di proposal:** Landasan Teori §Klasifikasi Baku Lapangan Usaha Indonesia; §Penelitian Terdahulu (Tabel, No. 3) — 2 sitasi
- **Hasil (tabel Penelitian Terdahulu):** Alat swa-klasifikasi yang memetakan uraian usaha singkat ke kode NAICS enam digit melalui pencarian informasi bertingkat (sektor, lalu kode); peluang swa-klasifikasi berhasil 0,755 pada uji awal 2021. **Kekurangan:** berbasis pencarian informasi, bukan LLM generatif; taksonomi NAICS Amerika Serikat berbahasa Inggris.
- **Kegunaan untuk TA:** Bukti bahwa pemetaan uraian usaha ke klasifikasi baku berjenjang dapat dibantu alat otomatis pada skala sensus nasional — preseden penting dari sisi skala dan keberhasilan praktik, meski pendekatannya berbasis pencarian informasi (bukan LLM generatif) dan untuk taksonomi berbahasa Inggris, sehingga TA ini memperluasnya ke LLM generatif dan taksonomi KBLI berbahasa Indonesia.

---

## F. Metodologi dan Pengukuran

### 45. Design Science in Information Systems Research

- **Kunci BibTeX:** `hevner2004design`
- **Penulis:** Hevner, Alan R.; March, Salvatore T.; Park, Jinsoo; Ram, Sudha · **Tahun:** 2004
- **Jenis & Sumber:** *MIS Quarterly*, 28(1), 75–105
- **Berkas lokal:** [`entri-aktif/hevner2004design.pdf`](entri-aktif/hevner2004design.pdf) — naskah penerimaan ("*Accepted for Publication in MIS Quarterly*"), bukan versi terbit penerbit
- **Dikutip di proposal:** Landasan Teori §*Design Science Research*; Metode Penelitian §Pendekatan Penelitian; §Kerangka Berpikir — 3 sitasi
- **Kegunaan untuk TA:** **Definisi paradigma penelitian yang dipakai seluruh TA ini.** Design science research (DSR) didefinisikan sebagai paradigma yang menghasilkan dan mengevaluasi artefak untuk memecahkan persoalan organisasi nyata dengan kontribusi pengetahuan yang diperoleh secara ketat (*rigor*) — definisi inilah yang membuka Metode Penelitian §Pendekatan Penelitian.

### 46. A Design Science Research Methodology for Information Systems Research

- **Kunci BibTeX:** `peffers2007dsrm`
- **Penulis:** Peffers, Ken; Tuunanen, Tuure; Rothenberger, Marcus A.; Chatterjee, Samir · **Tahun:** 2007
- **Jenis & Sumber:** *Journal of Management Information Systems*, 24(3), 45–77
- **Berkas lokal:** [`entri-aktif/peffers2007dsrm.pdf`](entri-aktif/peffers2007dsrm.pdf)
- **Dikutip di proposal:** Landasan Teori §*Design Science Research*; Metode Penelitian §Pendekatan Penelitian; §Kerangka Berpikir — 3 sitasi
- **Kegunaan untuk TA:** **Metodologi (DSRM) yang diikuti langsung dalam penyusunan tahapan penelitian** — enam aktivitas DSRM (identifikasi masalah dan motivasi, penetapan tujuan solusi, perancangan dan pengembangan, demonstrasi, evaluasi, serta komunikasi) menjadi struktur Metode Penelitian §Tahapan Penelitian.

### 47. Positioning and Presenting Design Science Research for Maximum Impact

- **Kunci BibTeX:** `gregor2013positioning`
- **Penulis:** Gregor, Shirley; Hevner, Alan R. · **Tahun:** 2013
- **Jenis & Sumber:** *MIS Quarterly*, 37(2), 337–355 · **DOI:** [10.25300/MISQ/2013/37.2.01](https://doi.org/10.25300/MISQ/2013/37.2.01)
- **Berkas lokal:** [`entri-aktif/gregor2013positioning.pdf`](entri-aktif/gregor2013positioning.pdf)
- **Dikutip di proposal:** Pendahuluan §Latar Belakang; §Kontribusi Penelitian; Landasan Teori §*Design Science Research*; Metode Penelitian §Pendekatan Penelitian — 4 sitasi
- **Kegunaan untuk TA:** **Kerangka untuk memosisikan tingkat kontribusi pengetahuan TA ini.** Klasifikasi empat kuadran kontribusi DSR (penemuan, peningkatan, eksaptasi, desain rutin) dipakai untuk menjelaskan bahwa purwarupa TA ini merupakan instansiasi prinsip desain DP1–DP4 yang diuji secara empiris, dengan klaim pengetahuan diajukan pada tingkat prinsip desain, bukan pada tingkat purwarupa semata.

### 48. A Coefficient of Agreement for Nominal Scales

- **Kunci BibTeX:** `cohen1960kappa`
- **Penulis:** Cohen, Jacob · **Tahun:** 1960
- **Jenis & Sumber:** *Educational and Psychological Measurement*, 20(1), 37–46
- **Berkas lokal:** [`entri-aktif/cohen1960kappa.pdf`](entri-aktif/cohen1960kappa.pdf)
- **Dikutip di proposal:** Landasan Teori §Evaluasi Klasifikasi dan Reliabilitas — 1 sitasi
- **Kegunaan untuk TA:** Sumber rumus koefisien kappa Cohen yang dipakai TA ini untuk mengukur kesepakatan antara dua pengode — baik antara dua anotator manusia maupun antara LLM dan data acuan — pada evaluasi reliabilitas anotasi standardisasi KBLI.

### 49. The Measurement of Observer Agreement for Categorical Data

- **Kunci BibTeX:** `landis1977kappa`
- **Penulis:** Landis, J. Richard; Koch, Gary G. · **Tahun:** 1977
- **Jenis & Sumber:** *Biometrics*, 33(1), 159–174
- **Berkas lokal:** [`entri-aktif/landis1977kappa.pdf`](entri-aktif/landis1977kappa.pdf)
- **Dikutip di proposal:** Landasan Teori §Evaluasi Klasifikasi dan Reliabilitas; Metode Penelitian §Rancangan Eksperimen Standardisasi (RQ2) — 2 sitasi
- **Kegunaan untuk TA:** **Dasar ambang kriteria penerimaan kuantitatif TA ini.** Skala interpretasi kappa Landis–Koch (0,41–0,60 sedang; 0,61–0,80 substansial; 0,81–1,00 hampir sempurna) dipakai langsung sebagai kriteria penerimaan komponen standardisasi pada RQ2 — layak digunakan dalam artefak apabila kondisi terbaik mencapai kappa minimal 0,61 (kesepakatan substansial).

### 50. SUS: A "Quick and Dirty" Usability Scale

- **Kunci BibTeX:** `brooke1996sus` · *(catatan `.bib`: [CEK] penyunting dan halaman buku dari naskah tim)*
- **Penulis:** Brooke, John · **Tahun:** 1996
- **Jenis & Sumber:** Bab dalam *Usability Evaluation in Industry* (ed. Jordan, Thomas, Weerdmeester, McClelland), Taylor & Francis, London, hlm. 189–194
- **Berkas lokal:** [`entri-aktif/brooke1996sus.pdf`](entri-aktif/brooke1996sus.pdf) — cetak ulang bab mandiri; nama buku/penyunting/penerbit tidak tercetak di berkas ini
- **Dikutip di proposal:** Landasan Teori §Evaluasi Pengguna; Metode Penelitian §Kerangka Berpikir; §Rancangan Evaluasi Pengguna dan Modul Keputusan (RQ4) — 3 sitasi
- **Kegunaan untuk TA:** Sumber instrumen *System Usability Scale* (SUS, 10 butir skala Likert lima poin) yang dipakai TA ini untuk mengukur kebergunaan purwarupa pada RQ4 — termasuk rumus skor SUS dan rentang nilai 0–100 yang dipakai langsung pada contoh perhitungan di Landasan Teori.

### 51. Validation of the National Aeronautics and Space Administration Task Load Index (NASA-TLX) Adapted for the Whole Day Repeated Measures Context

- **Kunci BibTeX:** `hernandez2022nasatlx`
- **Penulis:** Hernandez, Raymond; Roll, Shawn C.; Jin, Haomiao; Schneider, Stefan; Pyatak, Elizabeth A. · **Tahun:** 2022
- **Jenis & Sumber:** *Ergonomics*, 65(7), 960–975 · **DOI:** [10.1080/00140139.2021.2006317](https://doi.org/10.1080/00140139.2021.2006317)
- **Berkas lokal:** [`entri-aktif/hernandez2022nasatlx.pdf`](entri-aktif/hernandez2022nasatlx.pdf) — naskah penulis (HHS Public Access/PMC)
- **Dikutip di proposal:** Landasan Teori §Evaluasi Pengguna; Metode Penelitian §Kerangka Berpikir; §Rancangan Evaluasi Pengguna dan Modul Keputusan (RQ4) — 3 sitasi
- **Kegunaan untuk TA:** Dasar validasi varian *raw* TLX (NASA-TLX tanpa pembobotan berpasangan) yang dipakai TA ini untuk mengukur beban kerja subjektif enam dimensi (mental, fisik, waktu, performa, usaha, frustrasi) pada evaluasi pengguna RQ4 — memberi justifikasi bahwa varian yang lebih ringkas ini tetap valid untuk pengukuran berulang.

### 52. Individual Comparisons by Ranking Methods

- **Kunci BibTeX:** `wilcoxon1945individual`
- **Penulis:** Wilcoxon, Frank · **Tahun:** 1945
- **Jenis & Sumber:** *Biometrics Bulletin*, 1(6), 80–83
- **Berkas lokal:** [`entri-aktif/wilcoxon1945individual.pdf`](entri-aktif/wilcoxon1945individual.pdf)
- **Dikutip di proposal:** Landasan Teori §Evaluasi Pengguna; Metode Penelitian §Rancangan Evaluasi Pengguna dan Modul Keputusan (RQ4) — 2 sitasi
- **Kegunaan untuk TA:** **Uji statistik yang dipakai langsung untuk menguji H5.** Karena jumlah partisipan kecil dan sebaran selisih skor tidak diasumsikan normal, H5 (perbandingan waktu penyelesaian tugas dan beban kerja antara kondisi lembar kerja dan purwarupa) diuji menggunakan uji peringkat bertanda Wilcoxon satu arah pada selisih berpasangan setiap partisipan.

---

## Berkas Entri Aktif

Folder [`Referensi/entri-aktif/`](entri-aktif/) memuat **50 berkas PDF**, masing-masing diberi nama `<kunci-bibtex>.pdf` — sama persis dengan kunci `\cite{}` di `Dokumen/proposal/references.bib` dan di berkas `.tex`, sehingga satu referensi dapat ditemukan dari teks proposal maupun dari nama berkasnya tanpa perlu tabel pencarian terpisah. 2 dari 52 entri aktif (`wawancarakadis2026`, `wawancarastaf2026`) adalah transkrip wawancara internal tim tanpa berkas publik.

Untuk dua referensi yang isinya punya dua versi berbeda, berkas di `entri-aktif/` adalah versi yang sudah tercatat lebih dahulu dalam riwayat berkas proyek ini (`git`):
- `otis2026uneven.pdf` → versi *preprint* eScholarship (37 hlm.)
- `raisch2021automation.pdf` → versi terbit UNIGE (20 hlm.)

Versi alternatif keduanya tetap disimpan di `entri-nonaktif/` (lihat di bawah) agar tidak hilang, kalau-kalau ingin ditukar.

## Berkas Entri Nonaktif

Folder [`Referensi/entri-nonaktif/`](entri-nonaktif/) memuat **26 berkas** yang **tidak** menjadi entri aktif di `references.bib` saat ini, dikelompokkan sebagai berikut.

### Di luar cakupan `.bib` (15 berkas)

PDF hasil penelitian terdahulu yang pernah diunduh untuk eksplorasi topik tetapi tidak (atau belum) disitasi di proposal: `selem-2026-genai-tourism-interface.pdf`, `rosalina-2026-rag-sme-communication.pdf`, `besrour-2025-squai.pdf`, `gupta-2024-genai-adoption.pdf`, `sankar-2026-prompt-formulation.pdf` *(nama berkas lama "pawni" diperbaiki — penulis sebenarnya Sankar, B. dkk.)*, `wang-2024-llm-agents-survey.pdf`, `guo-2024-multi-agent-survey.pdf`, `lewis-2020-rag.pdf`, `ghonisyah-2025-genai-content-marketing.pdf`, `yafie-2026-academic-chatbot-rag.pdf`, `aziz-2025-service-standardization.pdf`, `abaiyan-2026-fault-of-our-stars.pdf`, `gorter-2025-absa-google-maps-mismatch.pdf`, `zuhir-2025-beyond-stars.pdf`, `singh-2025-nek-minit-sarcasm.pdf` *(bukan `singh2025agentic`; penulis dan topik berbeda — ditambah akhiran "-sarcasm" agar tidak tertukar)*.

### Draf lampiran belum masuk `.bib` (2 berkas)

`rivani-2025-pelatihan-umkm-tangerang.pdf` dan `yulianti-2026-legalitas-guesthouse-mulyaharja.pdf` — draf kunci BibTeX untuk keduanya (`rivani2025pelatihan`, `yulianti2026legalitas`) sudah disiapkan di `Daftar_Referensi_dan_Checklist_Unduhan.md` §Draf BibTeX, menunggu keputusan apakah akan ditambahkan ke `.bib` dan disitasi di Bab II/III.

### Berkas salah (1 berkas)

`BUKAN-iso25012_dunkelman-2017-fse-slide.pdf` — ini **bukan** ISO/IEC 25012:2008; isinya slide "A Statement on Standardization" (Dunkelman, Luykx, Perrin; FSE 2017). Berkas ISO/IEC 25012:2008 yang benar ada di `entri-aktif/iso25012.pdf`.

### Versi alternatif referensi yang dipakai (2 berkas)

`otis2026uneven_versi-informs-18hlm.pdf` (versi INFORMS *Articles in Advance*, 18 hlm.) dan `raisch2021automation_versi-naskah-penulis-48hlm.pdf` (naskah penulis, 48 hlm.) — isinya sama secara substansi dengan `entri-aktif/otis2026uneven.pdf` dan `entri-aktif/raisch2021automation.pdf`, hanya edisi/format terbitan yang berbeda.

### Salinan identik 100% (5 berkas + 1 arsip)

`hardiyanti2026adaptive_duplikat.pdf`, `nadhifah2026digitalisasi_duplikat.pdf`, `naibaho2025ulos_duplikat.pdf`, `papageorgiou2024egov_duplikat.pdf`, `sagala2024sme_duplikat.pdf` — salinan berkas yang hash-nya identik byte-per-byte dengan berkas yang sudah ada di `entri-aktif/`; dipindahkan ke sini alih-alih dihapus, agar tidak ada data yang hilang. `ARSIP_referensi-lama-17entri-tidak-dipakai.bib` adalah berkas BibTeX lama (subset 17 entri) yang sudah digantikan total oleh `Dokumen/proposal/references.bib` (52 entri).

---

## Berkas Lain di Folder `Referensi/`

- [`Daftar_Referensi_dan_Checklist_Unduhan.md`](Daftar_Referensi_dan_Checklist_Unduhan.md) — status unduhan dan hasil verifikasi isi tiap PDF terhadap `references.bib` (kolom "Hasil Cek Berkas" dan "Kesesuaian metadata .bib vs isi PDF"); rujukan lebih rinci untuk catatan `[CEK]` dan `[TERVERIFIKASI]` yang disebut singkat di dokumen ini. Kolom "Asal" pada dokumen itu (`Ref BIB`, `ref.zip`, `Lampiran chat`) mencatat dari mana setiap berkas pertama kali diunduh — folder `Ref BIB` dan `pdf` itu sendiri sudah tidak ada lagi karena isinya telah dipindahkan ke `entri-aktif/`/`entri-nonaktif/`.
