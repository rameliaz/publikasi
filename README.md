# Workshop Publikasi Ilmiah

Materi workshop **Publikasi Ilmiah** untuk mahasiswa doktoral Program Studi S3 Psikologi, Universitas Airlangga. Difasilitasi oleh **Rizqy Amelia Zein** (Departemen Psikologi, Universitas Airlangga), atas inisiatif komunitas **Airlangga Doctoral Enrichment Community (Psy-ADEC)**.

🗓️ **Jumat–Sabtu, 22–23 Mei 2026, pukul 13.00–15.00 WIB** — daring via Microsoft Teams

🌐 **Website**: [rameliaz.github.io/penerbitan](https://rameliaz.github.io/penerbitan)

---

## Struktur Workshop

Workshop terdiri dari dua blok masing-masing 2 jam.

### Blok 1 — Ekosistem Publikasi Ilmiah

> `slides/bagian-1.qmd`

- Tujuan dan peran publikasi ilmiah
- Moda komunikasi kesarjanaan & jenis artikel (*original research*, *systematic/scoping review*, dll.)
- Lanskap jurnal: penerbit, pangkalan data (Scopus, WoS, SINTA), *open access* vs. *paywalled*
- Mengenali jurnal/penerbit pemangsa (*predatory*)
- Proses editorial: *submission*, *desk rejection*, *peer-review*, revisi, hingga terbit
- Struktur naskah IMRAD dan panduan PRISMA untuk *meta studies*
- Menulis *Introduction*, *Discussion*, dan *Abstract* yang efektif
- **Latihan**: *elevator pitch* (3–4 kalimat)

### Blok 2 — Strategi Publikasi & Latihan Menulis

> `slides/bagian-2.qmd`

- Strategi memilih jurnal: 4R (*relevance, reach, reputation, realism*)
- Menulis *cover letter* dan menjawab komentar *reviewer*
- Etika publikasi: kepengarangan, plagiarisme, peran promotor
- Krisis replikasi dan prinsip *open science*
- Manajemen data penelitian (RDM): prinsip FAIR, *open data policy*, deposit di OSF/Zenodo
- **Latihan**: *scientific sell* (1 paragraf, 150–200 kata)

---

## Cara Menggunakan Repositori

### Prasyarat

```bash
quarto add rameliaz/quarto-unair-theme
quarto add quarto-ext/fontawesome
quarto add mcanouil/iconify
```

### Render

```bash
# Render seluruh website
quarto render

# Preview per slide
quarto preview slides/bagian-1.qmd
quarto preview slides/bagian-2.qmd
```

Output ditempatkan di folder `docs/` dan di-deploy via GitHub Pages.

---

## Struktur Repositori

```
penerbitan/
├── _quarto.yml              # konfigurasi website & format
├── index.qmd                # halaman utama website
├── slides/
│   ├── bagian-1.qmd         # slide Blok 1
│   ├── bagian-2.qmd         # slide Blok 2
│   └── libs/                # aset lokal (gambar, contoh response letter)
├── examples/                # materi referensi (jangan diubah)
├── _extensions/             # Quarto extensions (UNAIR theme, FontAwesome, Iconify)
└── docs/                    # output render — di-deploy ke GitHub Pages
```

---

## Lisensi

Materi ini dilisensikan di bawah **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

Anda bebas berbagi dan mengadaptasi materi ini untuk keperluan apapun, termasuk komersial, **selama mencantumkan atribusi yang sesuai**.

© 2025–2026 Rizqy Amelia Zein, Departemen Psikologi, Universitas Airlangga.
Lisensi lengkap: [creativecommons.org/licenses/by/4.0](https://creativecommons.org/licenses/by/4.0/)