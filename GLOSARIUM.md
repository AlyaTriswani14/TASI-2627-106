# Glosarium

Glosarium istilah yang kami temui selama pengerjaan proyek, mulai dari kecerdasan buatan (AI), alat kerja (Git/GitHub), sampai istilah UMKM dan pemerintahan daerah yang terkait studi kasus DKUKMPP Kabupaten Toba.

**Cara membaca kolom "Tahun":** tahun ketika istilah pertama kali diperkenalkan atau dipopulerkan, sesuai sumber yang dicantumkan. Untuk dokumen dan peraturan, tahun yang dipakai adalah tahun terbit atau penetapannya.

## Daftar Isi

- [A. Kecerdasan Buatan (AI) dan Model Bahasa](#a-kecerdasan-buatan-ai-dan-model-bahasa)
- [B. AI Agent dan Penggunaan Alat](#b-ai-agent-dan-penggunaan-alat)
- [C. Git dan GitHub](#c-git-dan-github)
- [D. UMKM dan Pemerintahan Daerah](#d-umkm-dan-pemerintahan-daerah)

---

## A. Kecerdasan Buatan (AI) dan Model Bahasa

| Istilah | Arti | Tahun | Sumber |
| --- | --- | --- | --- |
| **Artificial Intelligence (AI) / Kecerdasan Buatan** | Bidang ilmu komputer yang membuat mesin mampu melakukan tugas yang biasanya membutuhkan kecerdasan manusia, seperti memahami bahasa, belajar, dan mengambil keputusan. Istilah ini diciptakan John McCarthy dkk. untuk lokakarya Dartmouth 1956. | 1955 | [McCarthy dkk., *A Proposal for the Dartmouth Summer Research Project on AI*](http://jmc.stanford.edu/articles/dartmouth/dartmouth.pdf) |
| **Turing Test** | Uji untuk menilai apakah mesin dapat "berpikir", yaitu jika manusia tidak bisa membedakan jawaban mesin dari jawaban manusia. | 1950 | [Turing, *Computing Machinery and Intelligence*](https://doi.org/10.1093/mind/LIX.236.433) |
| **Neural Network / Jaringan Saraf Tiruan** | Model komputasi yang meniru cara kerja sel saraf otak: banyak "neuron" sederhana yang saling terhubung dan memproses sinyal. | 1943 | [McCulloch & Pitts, *A Logical Calculus of the Ideas Immanent in Nervous Activity*](https://doi.org/10.1007/BF02478259) |
| **Machine Learning / Pembelajaran Mesin** | Cabang AI di mana komputer belajar dari data dan pengalaman tanpa diprogram secara eksplisit untuk setiap aturan. | 1959 | [Samuel, *Some Studies in Machine Learning Using the Game of Checkers*](https://ieeexplore.ieee.org/document/5392560) |
| **Chatbot** | Program komputer yang dapat bercakap-cakap dengan manusia melalui teks atau suara. Salah satu chatbot pertama adalah ELIZA. | 1966 | [Weizenbaum, *ELIZA*](https://doi.org/10.1145/365153.365168) |
| **Natural Language Processing (NLP)** | Bidang AI yang membuat komputer mampu memahami, mengolah, dan menghasilkan bahasa manusia. | 1950-an | [Wikipedia: Natural language processing](https://en.wikipedia.org/wiki/Natural_language_processing) |
| **Embedding** | Cara mengubah kata atau teks menjadi deretan angka (vektor) sehingga kata yang maknanya mirip letaknya berdekatan. Dipopulerkan oleh word2vec. | 2013 | [Mikolov dkk., *Efficient Estimation of Word Representations in Vector Space*](https://arxiv.org/abs/1301.3781) |
| **Deep Learning / Pembelajaran Mendalam** | Machine learning yang memakai jaringan saraf berlapis-lapis (dalam) untuk mengenali pola rumit, misalnya pada gambar, suara, dan teks. | 2015 | [LeCun, Bengio & Hinton, *Deep Learning* (Nature)](https://www.nature.com/articles/nature14539) |
| **Generative AI / AI Generatif** | AI yang dapat menghasilkan konten baru (teks, gambar, suara, kode), bukan hanya mengklasifikasi data. Salah satu tonggaknya adalah GAN. | 2014 | [Goodfellow dkk., *Generative Adversarial Networks*](https://arxiv.org/abs/1406.2661) |
| **Token** | Potongan kecil teks (bisa satu kata, bagian kata, atau tanda baca) yang menjadi satuan baca dan tulis model bahasa. | 2015 | [Sennrich dkk., *Neural Machine Translation of Rare Words with Subword Units*](https://arxiv.org/abs/1508.07909) |
| **Transformer** | Arsitektur jaringan saraf berbasis mekanisme *attention* yang menjadi dasar hampir semua model bahasa modern. | 2017 | [Vaswani dkk., *Attention Is All You Need*](https://arxiv.org/abs/1706.03762) |
| **GPT (Generative Pre-trained Transformer)** | Jenis model bahasa yang dilatih awal (*pre-trained*) pada teks dalam jumlah besar, lalu dapat dipakai untuk berbagai tugas bahasa. | 2018 | [Radford dkk., *Improving Language Understanding by Generative Pre-Training*](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) |
| **Fine-tuning** | Melatih ulang model yang sudah dilatih awal dengan data khusus agar lebih ahli pada tugas tertentu. | 2018 | [Howard & Ruder, *Universal Language Model Fine-tuning (ULMFiT)*](https://arxiv.org/abs/1801.06146) |
| **Large Language Model (LLM) / Model Bahasa Besar** | Model bahasa berbasis Transformer dengan miliaran parameter, dilatih pada teks sangat besar, sehingga mampu menjawab pertanyaan, menulis, merangkum, dan menerjemahkan. Contoh: GPT, Claude, Gemini, Llama. | 2020 | [Brown dkk., *Language Models are Few-Shot Learners* (GPT-3)](https://arxiv.org/abs/2005.14165); [Zhao dkk., *A Survey of Large Language Models* (2023)](https://arxiv.org/abs/2303.18223) |
| **Prompt / Prompt Engineering** | *Prompt* adalah instruksi atau pertanyaan yang diberikan kepada model AI. *Prompt engineering* adalah teknik menyusun prompt agar hasil jawaban lebih tepat. | 2020 | [Brown dkk. (GPT-3)](https://arxiv.org/abs/2005.14165); [Panduan prompt engineering Anthropic](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview) |
| **Retrieval-Augmented Generation (RAG)** | Teknik di mana model AI terlebih dulu mencari dokumen yang relevan, lalu menyusun jawaban berdasarkan dokumen tersebut agar lebih akurat dan berbasis sumber. | 2020 | [Lewis dkk., *Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks*](https://arxiv.org/abs/2005.11401) |
| **Foundation Model** | Model AI besar yang dilatih pada data sangat luas dan menjadi "fondasi" untuk banyak aplikasi lain. | 2021 | [Bommasani dkk., *On the Opportunities and Risks of Foundation Models*](https://arxiv.org/abs/2108.07258) |
| **Multimodal** | Kemampuan model AI memproses lebih dari satu jenis data sekaligus, misalnya teks dan gambar. | 2021 | [Radford dkk., *CLIP: Learning Transferable Visual Models From Natural Language Supervision*](https://arxiv.org/abs/2103.00020) |
| **RLHF (Reinforcement Learning from Human Feedback)** | Metode melatih model AI menggunakan penilaian manusia agar jawabannya lebih membantu, jujur, dan aman. | 2017 | [Christiano dkk., *Deep RL from Human Preferences*](https://arxiv.org/abs/1706.03741); [Ouyang dkk., *InstructGPT* (2022)](https://arxiv.org/abs/2203.02155) |
| **Chain-of-Thought (CoT)** | Teknik meminta model menuliskan langkah-langkah penalaran sebelum memberi jawaban akhir, sehingga hasilnya lebih akurat pada soal yang rumit. | 2022 | [Wei dkk., *Chain-of-Thought Prompting Elicits Reasoning in LLMs*](https://arxiv.org/abs/2201.11903) |
| **Hallucination / Halusinasi AI** | Kondisi ketika model AI menghasilkan informasi yang terdengar meyakinkan tetapi salah atau tidak ada sumbernya. | 2022 | [Ji dkk., *Survey of Hallucination in Natural Language Generation*](https://arxiv.org/abs/2202.03629) |

---

## B. AI Agent dan Penggunaan Alat

| Istilah | Arti | Tahun | Sumber |
| --- | --- | --- | --- |
| **Agent / Agen (dalam AI)** | Sesuatu yang dapat mengamati lingkungannya lalu bertindak untuk mencapai tujuan. Definisi klasik dari buku teks AI. | 1995 | [Russell & Norvig, *Artificial Intelligence: A Modern Approach*](http://aima.cs.berkeley.edu/) |
| **AI Agent / LLM Agent** | Sistem di mana LLM tidak hanya menjawab, tetapi merencanakan langkah, memakai alat (pencarian, kode, aplikasi), melihat hasilnya, lalu menentukan langkah berikutnya secara mandiri sampai tugas selesai. | 2022 | [Yao dkk., *ReAct: Synergizing Reasoning and Acting in Language Models*](https://arxiv.org/abs/2210.03629); [Anthropic, *Building Effective Agents* (2024)](https://www.anthropic.com/research/building-effective-agents) |
| **Workflow vs Agent** | *Workflow*: LLM dan alat dijalankan mengikuti alur yang sudah ditentukan. *Agent*: LLM sendiri yang menentukan alur dan alat yang dipakai. Keduanya disebut *agentic systems*. | 2024 | [Anthropic, *Building Effective Agents*](https://www.anthropic.com/research/building-effective-agents) |
| **Tool Use / Function Calling** | Kemampuan model AI memanggil alat atau fungsi eksternal (kalkulator, API, basis data) untuk menyelesaikan tugas. | 2023 | [Schick dkk., *Toolformer: Language Models Can Teach Themselves to Use Tools*](https://arxiv.org/abs/2302.04761) |
| **Model Context Protocol (MCP)** | Standar terbuka untuk menghubungkan asisten AI dengan sumber data dan aplikasi (misalnya Google Drive, GitHub, Slack) secara seragam. | 2024 | [Anthropic, *Introducing the Model Context Protocol*](https://www.anthropic.com/news/model-context-protocol) |

---

## C. Git dan GitHub

| Istilah | Arti | Tahun | Sumber |
| --- | --- | --- | --- |
| **Git** | Sistem *version control* untuk mencatat setiap perubahan file, sehingga riwayat pekerjaan tersimpan dan bisa dikerjakan bersama. Dibuat oleh Linus Torvalds. | 2005 | [git-scm.com](https://git-scm.com/) |
| **GitHub** | Layanan daring untuk menyimpan repositori Git, berkolaborasi, dan meninjau perubahan kode atau dokumen. | 2008 | [GitHub Docs: About GitHub and Git](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git) |
| **Repository (Repo)** | Folder proyek yang berisi semua file beserta seluruh riwayat perubahannya. | 2005 | [GitHub Glossary](https://docs.github.com/en/get-started/learning-about-github/github-glossary) |
| **Commit** | "Simpanan" perubahan dengan pesan singkat yang menjelaskan apa yang diubah. | 2005 | [GitHub Glossary](https://docs.github.com/en/get-started/learning-about-github/github-glossary) |
| **Branch** | Cabang kerja terpisah untuk mencoba perubahan tanpa mengganggu versi utama (*main*). | 2005 | [GitHub Glossary](https://docs.github.com/en/get-started/learning-about-github/github-glossary) |
| **Pull Request (PR)** | Usulan untuk menggabungkan perubahan dari satu branch ke branch lain, sekaligus tempat diskusi dan peninjauan. | 2008 | [GitHub Glossary](https://docs.github.com/en/get-started/learning-about-github/github-glossary) |
| **README** | File pengantar di halaman depan repositori yang menjelaskan isi dan cara memakai proyek. | — | [GitHub Docs: About READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) |
| **Markdown** | Format penulisan teks sederhana (misalnya `#` untuk judul, `**tebal**`) yang ditampilkan rapi di GitHub. File ini ditulis dengan Markdown. | 2004 | [John Gruber, *Markdown*](https://daringfireball.net/projects/markdown/) |

---

## D. UMKM dan Pemerintahan Daerah

| Istilah | Arti | Tahun | Sumber |
| --- | --- | --- | --- |
| **UMKM (Usaha Mikro, Kecil, dan Menengah)** | Usaha produktif milik perorangan atau badan usaha yang memenuhi kriteria usaha mikro, kecil, atau menengah sesuai undang-undang. | 2008 | [UU No. 20 Tahun 2008 tentang UMKM](https://peraturan.go.id/files/UU%2020%202008.pdf) |
| **Kriteria UMKM terbaru** | Pengelompokan UMKM berdasarkan modal usaha atau hasil penjualan tahunan, yang diperbarui melalui peraturan pelaksana UU Cipta Kerja. | 2021 | [PP No. 7 Tahun 2021](https://peraturan.bpk.go.id/Home/Details/161837/pp-no-7-tahun-2021) |
| **DKUKMPP** | Dinas Koperasi, Usaha Kecil dan Menengah, Perdagangan dan Perindustrian Kabupaten Toba; perangkat daerah yang mengurus koperasi, UMKM, perdagangan, perindustrian, dan pasar rakyat. | 2020 | [Renstra DKUKMPP Toba 2025–2029](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Ranhir-Renstra-2025-2029-KOPERIN-1.pdf) |
| **Renstra (Rencana Strategis)** | Dokumen perencanaan lima tahunan perangkat daerah yang memuat tujuan, sasaran, strategi, program, dan target kinerja. | 2025 | [Renstra DKUKMPP Toba 2025–2029](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Ranhir-Renstra-2025-2029-KOPERIN-1.pdf) |
| **RPJMD** | Rencana Pembangunan Jangka Menengah Daerah; rencana lima tahun kepala daerah yang menjadi acuan Renstra setiap dinas. | 2025 | [Renstra DKUKMPP Toba 2025–2029](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Ranhir-Renstra-2025-2029-KOPERIN-1.pdf) |
| **SAKIP** | Sistem Akuntabilitas Kinerja Instansi Pemerintah; sistem yang menghubungkan perencanaan, penganggaran, pengukuran, dan pelaporan kinerja instansi. | 2014 | [LKjIP DKUKMPP Toba 2025](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Lakip-2025-ISI-Renstra-Koperin-REV-IKSFin.pdf) |
| **LKjIP / LAKIP** | Laporan Kinerja Instansi Pemerintah; laporan tahunan yang membandingkan target dan realisasi kinerja, sebagai produk akhir SAKIP. | 2026 | [LKjIP DKUKMPP Toba 2025](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Lakip-2025-ISI-Renstra-Koperin-REV-IKSFin.pdf) |
| **IKU (Indikator Kinerja Utama)** | Ukuran keberhasilan utama sebuah instansi, misalnya kontribusi sektor industri dan perdagangan terhadap PDRB. | 2026 | [LKjIP DKUKMPP Toba 2025](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Lakip-2025-ISI-Renstra-Koperin-REV-IKSFin.pdf) |
| **IKM (Industri Kecil dan Menengah)** | Usaha industri pengolahan berskala kecil dan menengah, misalnya tenun ulos, gerabah, dan olahan kolang-kaling di Toba. | 2026 | [LKjIP DKUKMPP Toba 2025](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Lakip-2025-ISI-Renstra-Koperin-REV-IKSFin.pdf) |
| **PDRB** | Produk Domestik Regional Bruto; nilai total barang dan jasa yang dihasilkan suatu daerah dalam satu tahun. | 2026 | [LKjIP DKUKMPP Toba 2025](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Lakip-2025-ISI-Renstra-Koperin-REV-IKSFin.pdf) |
| **Koperasi Desa/Kelurahan Merah Putih (KDMP/KKMP)** | Program koperasi di tingkat desa/kelurahan untuk memperkuat ekonomi desa; pada 2025 pendampingannya banyak menyita tenaga DKUKMPP Toba. | 2025 | [Renstra DKUKMPP Toba 2025–2029](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Ranhir-Renstra-2025-2029-KOPERIN-1.pdf) |
| **UTTP / Tera** | Alat Ukur, Takar, Timbang, dan Perlengkapannya; *tera* adalah pemeriksaan resmi agar alat tersebut akurat dan sah dipakai berdagang. | 2026 | [LKjIP DKUKMPP Toba 2025](https://dkukmpp.tobakab.go.id/wp-content/uploads/sites/94/2026/06/Lakip-2025-ISI-Renstra-Koperin-REV-IKSFin.pdf) |
| **NIB (Nomor Induk Berusaha)** | Identitas resmi pelaku usaha yang diterbitkan melalui sistem OSS (*Online Single Submission*). | 2021 | [PP No. 7 Tahun 2021](https://peraturan.bpk.go.id/Home/Details/161837/pp-no-7-tahun-2021) |

---

*Terakhir diperbarui: 11 Oktober 2026.*
