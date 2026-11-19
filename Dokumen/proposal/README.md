# Proposal TASI-2627-106

Versi 19 November 2026 menerapkan sumber dari `Proposal_TASI_2627_106.zip` ke direktori ini.

- Berkas utama: [final-project-proposal.tex](final-project-proposal.tex).
- Hasil kompilasi: [final-project-proposal.pdf](final-project-proposal.pdf), 152 halaman.
- Paket sumber untuk Overleaf: [proposal.zip](proposal.zip).
- Bibliografi: [references.bib](references.bib), 71 entri yang semuanya disitasi.
- Koleksi dan pemetaan PDF: [indeks referensi](../../Referensi/README.md).

## Perubahan

Revisi mencakup Bab I–III, abstrak Indonesia dan Inggris, daftar istilah, serta enam entri bibliografi tambahan. Struktur dokumen dan preamble mengikuti ZIP. Perapian tambahan terbatas pada pemenggalan dua nama atribut dalam tabel dan penampilan DOI enam sumber baru pada gaya `IEEEtran`, termasuk pengamanan karakter garis bawah dalam DOI.

Enam sumber baru adalah `chen2024rgb`, `ke2025rag10llm`, `escudero2026ragamr`, `liu2024lost`, `kurtic2025bf16`, dan `koto2023indommlu`. PDF bernomor [57]–[62] di koleksi aktif. Karena Bland dikutip lebih awal di Bab II, keseluruhan nomor [51]–[71] mengikuti urutan baru hasil BibTeX. Nama PDF, indeks, matriks, dan paket `referensi.zip` telah diselaraskan.

## Kompilasi

Jalankan dari direktori ini dengan pdfLaTeX dan BibTeX, atau pilih `final-project-proposal.tex` sebagai dokumen utama di Overleaf:

```text
pdflatex -interaction=nonstopmode -halt-on-error final-project-proposal.tex
bibtex final-project-proposal
pdflatex -interaction=nonstopmode -halt-on-error final-project-proposal.tex
pdflatex -interaction=nonstopmode -halt-on-error final-project-proposal.tex
```

Kompilasi terakhir dilakukan pada salinan sumber yang bersih agar berkas bantu versi lama tidak memengaruhi hasil. Hasil akhir tidak memuat sitasi atau rujukan silang yang tidak terdefinisi, label ganda, maupun peringatan `Overfull`. Tampilan 17 halaman yang mencakup abstrak, tabel yang berubah, dan daftar pustaka diperiksa secara visual.

Instalasi MiKTeX lokal masih melaporkan pesan nonfatal `Infinite glue shrinkage found in box being split` saat tabel panjang berpindah halaman. Ini merupakan [masalah versi paket longtable](https://github.com/latex3/latex2e/issues/1907); PDF tetap berhasil dibuat. Preamble tidak diubah untuk menutupi pesan tersebut.

## Batas pemeriksaan referensi

Keterlacakan mencakup 173 pemakaian sumber: 18 pada Bab I, 78 pada Bab II, dan 77 pada Bab III. Seluruh 71 kunci cocok antara LaTeX, BibTeX, daftar pustaka, dan PDF lokal. Identitas enam sumber baru dicocokkan dengan PDF serta laman penerbit/DOI yang ditautkan pada indeks.

[Matriks sitasi](../../Referensi/Referensi-Proposal.html#matriks) mempertahankan petikan bukti dari pemeriksaan sebelumnya. Sebanyak 41 baris diberi tanda **Konteks direvisi** karena kalimat atau lokasi penggunaan berubah; bukti lama pada baris tersebut belum dinyatakan sebagai validasi menyeluruh atas rumusan baru. Isi ilmiah dari revisi yang dikirim dipertahankan.
