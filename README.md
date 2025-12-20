# HomeHero — Laporan Manajemen Proyek (Tugas Besar)
**Platform Layanan dan Manajemen Rumah Terpadu**

Dokumen ini merupakan laporan manajemen proyek untuk HomeHero yang disusun secara formal sebagai landasan perencanaan, pengendalian, dan evaluasi proyek. Struktur laporan mengikuti praktik standar manajemen proyek: scope, jadwal, biaya, kualitas, risiko, pengadaan, komunikasi, pemangku kepentingan, dan SDM. Seluruh bagian dirancang agar “berdaging” (punya metode, metrik, ambang kontrol, serta mekanisme tata kelola yang dapat diaudit).

---

## Daftar Isi
1. [Ringkasan Eksekutif](#ringkasan-eksekutif)  
2. [Profil Proyek](#profil-proyek)  
3. [Manajemen Ruang Lingkup](#manajemen-ruang-lingkup)  
4. [Manajemen Waktu/Jadwal](#manajemen-waktujadwal)  
5. [Manajemen Biaya](#manajemen-biaya)  
6. [Manajemen Kualitas](#manajemen-kualitas)  
7. [Manajemen Risiko (Negatif & Positif)](#manajemen-risiko-negatif--positif)  
8. [Manajemen Pengadaan](#manajemen-pengadaan)  
9. [Manajemen Komunikasi](#manajemen-komunikasi)  
10. [Manajemen Stakeholder](#manajemen-stakeholder)  
11. [Manajemen SDM (HR)](#manajemen-sdm-hr)  
12. [Governance & Change Control](#governance--change-control)  
13. [Kesimpulan dan Saran](#kesimpulan-dan-saran)  
14. [Dokumentasi Prototype](#dokumentasi-prototype)  
15. [Daftar Pustaka](#daftar-pustaka)  

---

## Ringkasan Eksekutif
HomeHero adalah platform layanan dan manajemen rumah terpadu yang berorientasi pada kemudahan akses layanan rumah tangga (perawatan, perbaikan, kebersihan, dukungan rumah tangga) dengan standar operasional yang terukur. Tantangan utama yang dijawab proyek ini adalah keterpecahan layanan, ketidakpastian kualitas, dan rendahnya transparansi (jadwal, harga, ketersediaan mitra). Proyek dikendalikan dengan baseline yang realistis untuk periode tugas (Nov–Des 2025) sehingga output dapat dinilai objektif melalui artefak yang jelas, bukan sekadar status verbal.

Secara manajerial, pendekatan yang dipakai menekankan:
- baseline deliverable akademik yang ketat (kebutuhan, desain, prototipe, uji kegunaan, laporan),
- roadmap implementasi lanjutan (Jan–Apr 2026) sebagai kelanjutan bila sistem diteruskan menjadi produk operasional,
- kontrol biaya melalui EVM (Earned Value Management) dan ambang CPI/SPI,
- kontrol kualitas dengan kriteria penerimaan yang terukur (usability, konsistensi UI, defect, keamanan dasar),
- manajemen risiko mencakup **risiko negatif (threats)** dan **risiko positif (opportunities)**.

---

## Profil Proyek
Proyek dikelola dengan struktur sponsor–PM–tim lintas fungsi. Periode baseline disesuaikan dengan batas waktu akademik, sedangkan roadmap menyiapkan jalur implementasi penuh.

**Informasi kunci proyek:**
- **Nama Proyek:** HomeHero  
- **Jenis Proyek:** Pengembangan platform layanan & manajemen rumah (produk digital)  
- **Periode Baseline Tugas:** Awal Nov 2025 – 29 Des 2025  
- **Tujuan Baseline:** analisis kebutuhan, desain UX/UI, prototipe hi-fi, usability testing, finalisasi laporan & artefak proyek  
- **Arah Produk Lanjutan (Roadmap):** implementasi pengembangan inti & go-live (Jan–Apr 2026)

---

## Manajemen Ruang Lingkup
Ruang lingkup disusun agar jelas memisahkan **apa yang wajib selesai dalam baseline** dan **apa yang menjadi pengembangan lanjutan**. Ini menjaga logika proyek: baseline fokus pada artefak yang dapat dinilai, sedangkan roadmap fokus pada kesiapan produksi.

**In-Scope Baseline (Nov–Des 2025):**
- Analisis kebutuhan & riset pengguna (persona, pain point, kebutuhan fungsional/non-fungsional)
- Desain solusi: user flow, informasi arsitektur (IA), prioritas fitur
- Prototipe high-fidelity yang dapat diuji
- Usability testing + iterasi perbaikan prototipe
- Dokumentasi proyek & laporan akhir

**Out-of-Scope Baseline (ditaruh sebagai Roadmap):**
- Pengembangan backend/mobile produksi penuh
- Integrasi pembayaran produksi dan hardening keamanan
- Pengujian regresi lengkap, deployment produksi, monitoring pasca rilis

---

## Manajemen Waktu/Jadwal
### Pendekatan Penjadwalan
Manajemen jadwal dilakukan dengan membentuk **schedule baseline** untuk periode Nov–Des 2025 (selesai 29 Des 2025). Baseline disusun dari WBS dan dependensi aktivitas: analisis → definisi kebutuhan → desain → validasi desain via uji pengguna → finalisasi. Jalur kritis diidentifikasi agar aktivitas yang menentukan ketepatan waktu mendapatkan kontrol lebih ketat. Pengendalian jadwal menilai kemajuan berdasarkan **bukti keluaran** (dokumen, prototipe, hasil uji), bukan hanya laporan verbal.

Mekanisme kontrol jadwal meliputi rapat sinkronisasi rutin, pembaruan progres berbasis deliverable, serta eskalasi dan penyesuaian prioritas bila hambatan memengaruhi jalur kritis.

### Gantt Chart Baseline (Nov–Des 2025)
![Gantt Baseline Nov–Des 2025]
<img width="2400" height="1200" alt="homehero_gantt_7weeks (1)" src="https://github.com/user-attachments/assets/5e031e73-aafb-4b07-bfca-fcafd3571c8b" />

**Milestone baseline (Nov–Des 2025):**
- Kickoff & inisiasi proyek (awal Nov 2025)
- Analisis & riset pengguna selesai (Nov 2025)
- Kebutuhan & spesifikasi ringkas disepakati (pertengahan Nov 2025)
- Konseptualisasi solusi selesai: user flow + IA + prioritas fitur (awal Des 2025)
- Hi-Fi prototype siap untuk diuji (pertengahan Des 2025)
- Usability testing & iterasi selesai (akhir Des 2025)
- Finalisasi & delivery artefak (29 Des 2025)

### Roadmap Pengembangan Lanjutan (Jan–Apr 2026)
Roadmap ini tidak mengubah baseline tugas; fungsinya sebagai rencana lanjutan jika HomeHero diteruskan menjadi implementasi operasional.

> Simpan file gambar ke: `docs/images/homehero_roadmap_jan_apr2026.png`

![Roadmap Jan–Apr 2026]
<img width="4768" height="2370" alt="homehero_roadmap_jan_apr2026" src="https://github.com/user-attachments/assets/b350e1f0-4d6e-40e6-a651-39c80a552ac9" />


---

## Manajemen Biaya
### Pendekatan Manajemen Biaya
Biaya proyek dikelola melalui baseline anggaran, pembentukan kontrol biaya per komponen utama WBS, dan pelaporan rutin. Pengukuran kinerja biaya dilakukan menggunakan Earned Value Management (EVM) agar deviasi biaya/jadwal dapat diketahui lebih dini dan ditindak dengan rencana korektif.

**Prinsip kontrol biaya yang diterapkan:**
- Biaya di-tracking per kontrol akun (control account) agar evaluasi biaya tetap realistis namun terukur.
- Pelaporan biaya disajikan periodik dan memuat deviasi, penyebab, serta rencana korektif.
- Perubahan biaya hanya boleh terjadi melalui change control resmi dan persetujuan sponsor.

### Struktur Anggaran (Project Budget)
Anggaran dibagi menjadi biaya tetap, material/operasional, kontraktor/tenaga ahli, serta cadangan manajemen untuk ketidakpastian.

| Kategori Biaya | Nilai |
|---|---:|
| Fixed Costs | Rp6.500.000 |
| Material/Operational Costs | Rp4.000.000 |
| Contractor/External Specialist Costs | Rp39.500.000 |
| **Total Project Cost** | **Rp50.000.000** |
| Management Reserve | Rp5.000.000 |

> Catatan manajerial: Management reserve hanya digunakan untuk kebutuhan tak terduga yang disetujui sponsor (bukan untuk menutup pemborosan).

### Pengukuran Biaya dengan EVM (SV, CV, SPI, CPI)
Pengendalian biaya dan jadwal menggunakan metrik berikut:
- **SV (Schedule Variance) = EV − PV**
- **CV (Cost Variance) = EV − AC**
- **SPI (Schedule Performance Index) = EV / PV**
- **CPI (Cost Performance Index) = EV / AC**

**Ambang pengendalian (Control Threshold):**
- **Kuning (Caution):** SPI/CPI berada di rentang 0,9–0,8 atau 1,1–1,2  
- **Merah (Alert):** SPI/CPI < 0,8 atau > 1,2 → wajib corrective action plan dan change request bila menyentuh scope/budget

### Respons Deviasi Biaya (Cost Variance Response)
Jika proyek menyentuh ambang merah, Project Manager menyusun opsi koreksi dan menyampaikannya ke sponsor. Sponsor memilih opsi terbaik (misal penyesuaian ruang lingkup, re-baseline, atau alokasi cadangan). Setelah opsi dipilih, PM menyusun rencana korektif formal dan menetapkan cara mengukur efektivitasnya.

### Analisis Kelayakan Finansial (NPV, ROI, Payback)
Bagian ini menilai kelayakan investasi HomeHero untuk skenario implementasi operasional. Untuk menjaga transparansi, perhitungan ditulis eksplisit.

#### Asumsi Umum (untuk semua skenario)
- Investasi awal (tahun 0): **Rp50.000.000**
- Horizon evaluasi: **3 tahun**
- Discount rate (baseline): **10%**
- Cash flow dinyatakan sebagai **net benefit** (setelah biaya operasional terkait skenario)

#### Rumus yang digunakan
- **NPV = −I0 + Σ (CFt / (1 + r)^t)**
- **ROI (simple) = (ΣCF − I0) / I0**
- **Payback Period (simple)** = waktu sampai kumulatif cash flow menutup investasi awal
- **Discounted Payback Period** = payback dengan cash flow yang didiskontokan

---

### Perhitungan Detail — Skenario Moderat (Baseline)
**Cash flow:** Tahun-1 Rp40.000.000, Tahun-2 Rp60.000.000, Tahun-3 Rp80.000.000 (r=10%)

**Langkah PV per tahun:**
- PV1 = 40.000.000 / 1,1 = **36.363.636**
- PV2 = 60.000.000 / 1,1² = **49.586.777**
- PV3 = 80.000.000 / 1,1³ = **60.105.547**

**Total PV manfaat = 146.055.960**  
**NPV = 146.055.960 − 50.000.000 = 96.055.960 (positif → layak)**

**ROI (3 tahun, simple):**  
(40+60+80 − 50) / 50 = 130 / 50 = **2,6 = 260%**

**Payback (simple):**
- Tahun 1: kumulatif 40.000.000 (kurang 10.000.000)
- Tahun 2: butuh 10.000.000 dari 60.000.000 → 10/60 = 0,1667 tahun  
**Payback ≈ 1,17 tahun (~14 bulan)**

---

### Skenario Cash Flow (Konservatif vs Moderat vs Agresif)
Tiga skenario disusun untuk menggambarkan variasi adopsi pasar dan skala transaksi.

| Skenario | Tahun-1 | Tahun-2 | Tahun-3 |
|---|---:|---:|---:|
| Konservatif | Rp30.000.000 | Rp45.000.000 | Rp60.000.000 |
| Moderat (Baseline) | Rp40.000.000 | Rp60.000.000 | Rp80.000.000 |
| Agresif | Rp50.000.000 | Rp75.000.000 | Rp100.000.000 |

**ROI simple (3 tahun):**
- Konservatif: (135−50)/50 = **170%**
- Moderat: (180−50)/50 = **260%**
- Agresif: (225−50)/50 = **350%**

---

### Sensitivitas NPV terhadap Discount Rate (8% / 10% / 12%)
Tabel berikut menguji ketahanan kelayakan terhadap perubahan discount rate.

| Skenario | Diskonto | NPV | Payback (simple) | Discounted Payback |
|---|---:|---:|---:|---:|
| Konservatif | 8% | Rp57.528.000 | 1,56 thn (~19 bln) | 1,73 thn (~21 bln) |
| Konservatif | 10% | Rp53.356.000 | 1,56 thn (~19 bln) | 1,77 thn (~21 bln) |
| Konservatif | 12% | Rp49.442.000 | 1,56 thn (~19 bln) | 1,81 thn (~22 bln) |
| Moderat (Baseline) | 8% | Rp103.876.000 | 1,17 thn (~14 bln) | 1,32 thn (~16 bln) |
| Moderat (Baseline) | 10% | Rp96.056.000 | 1,17 thn (~14 bln) | 1,36 thn (~16 bln) |
| Moderat (Baseline) | 12% | Rp88.790.000 | 1,17 thn (~14 bln) | 1,40 thn (~17 bln) |
| Agresif | 8% | Rp150.225.000 | 1,00 thn (~12 bln) | 1,14 thn (~14 bln) |
| Agresif | 10% | Rp138.756.000 | 1,00 thn (~12 bln) | 1,18 thn (~14 bln) |
| Agresif | 12% | Rp128.105.000 | 1,00 thn (~12 bln) | 1,22 thn (~15 bln) |

**Interpretasi ringkas:** semua skenario menghasilkan NPV positif bahkan pada diskonto 12%, sehingga proyek tergolong robust. Namun skenario konservatif paling sensitif terhadap kenaikan discount rate dan memerlukan fokus lebih kuat pada strategi adopsi & efisiensi biaya.

---

## Manajemen Kualitas
Manajemen kualitas memastikan deliverable memenuhi standar yang disepakati serta konsisten untuk pengalaman pengguna dan keamanan dasar. Kualitas dipandang sebagai kombinasi **Quality Assurance (QA process)** dan **Quality Control (QC output)**.

**Sasaran kualitas utama:**
- Kegunaan (usability) prototipe tinggi dan mudah dipahami pengguna target
- Konsistensi visual dan navigasi antarlayar
- Minim defect kritis pada artefak prototipe dan spesifikasi
- Keamanan dasar: tidak ada praktik desain yang membuka celah serius (misal input sensitif tanpa validasi konsep)

### Tabel Kontrol Kualitas (Process Action — Acceptable Criteria — Assessment Interval)
| Process Action | Acceptable Criteria | Assessment Interval |
|---|---|---|
| Review kebutuhan (requirements review) | Dokumen kebutuhan disetujui stakeholder kunci; tidak ada konflik requirement utama; traceability ke user flow tersedia | 1x tiap selesai fase analisis + saat ada perubahan besar |
| Audit konsistensi UI (design system check) | Konsistensi komponen ≥ 90% (warna, tipografi, tombol, spacing); tidak ada anomali layout kritis | Mingguan selama fase desain + sebelum freeze prototype |
| Usability testing (task-based) | Task Success Rate ≥ 80%; rata-rata waktu penyelesaian tugas masuk batas yang disepakati; temuan severity tinggi ditutup sebelum final | Minimal 2 siklus: pertengahan Des + akhir Des |
| Defect & issue triage | Tidak ada defect “critical”; defect major ditutup sebelum delivery; backlog terprioritaskan | 2x per minggu saat iterasi prototipe |
| Quality gate sebelum delivery | Semua milestone baseline terpenuhi; artefak lengkap (prototype final + ringkasan uji + rekomendasi) | 1x pada minggu terakhir sebelum 29 Des |
| Review keamanan konseptual | Tidak ada alur yang mengabaikan autentikasi/otorisasi untuk data sensitif; rekomendasi hardening tercatat untuk roadmap | 1x sebelum finalisasi dokumen desain |

---

## Manajemen Risiko (Negatif & Positif)
Risiko dikelola melalui identifikasi, analisis probabilitas–dampak, penetapan risk owner, strategi respons, dan monitoring berkala. Risiko dibedakan menjadi:
- **Risiko negatif (threats):** berdampak merugikan, ditangani dengan avoid/mitigate/transfer/accept
- **Risiko positif (opportunities):** peluang yang menguntungkan, ditangani dengan exploit/enhance/share/accept

![Risk Matrix]
<img width="4047" height="2347" alt="homehero_risk_matrix_clean" src="https://github.com/user-attachments/assets/6dba8167-d30b-4339-b1e1-ea93670ff142" />


### Risk Register (Contoh Ringkas)
#### A. Risiko Negatif (Threats)
- **Keterlambatan baseline artefak (jadwal mepet):** mitigasi dengan jalur kritis, timeboxing, dan definisi “done” berbasis artefak.
- **Scope creep dari stakeholder:** mitigasi dengan change request + impact analysis dan gate review.
- **Risiko keamanan & privasi (konsep layanan masuk rumah):** mitigasi dengan kebijakan verifikasi mitra, audit desain keamanan, dan rencana security testing pada roadmap.
- **Ketergantungan integrasi pihak ketiga (payment/maps):** transfer/mitigate lewat seleksi vendor, fallback flow, dan rencana integrasi bertahap.

#### B. Risiko Positif (Opportunities)
- **Kemitraan komunitas/RT-RW untuk onboarding mitra “Hero”:** *exploit* dengan pilot komunitas untuk mempercepat supply mitra.
- **Validasi usability menghasilkan desain sangat kuat lebih cepat:** *enhance* dengan menambah iterasi terarah untuk mengunci UX dan menurunkan risiko adopsi rendah.
- **Dukungan sponsor/steering mempercepat keputusan perubahan:** *exploit* dengan mempercepat cycle approval dan mengurangi idle time.
- **Momentum publikasi internal/eksternal (kampus/komunitas):** *share* dengan pihak terkait untuk memperluas awareness dan calon user.

### Monitoring dan Eskalasi
Risk register dan risk matrix direview berkala (bi-weekly) pada rapat tim. Risiko pada zona tinggi wajib memiliki rencana kontingensi yang jelas dan pemilik risiko yang ditunjuk. Perubahan level risiko memicu pembaruan rencana dan, bila berdampak pada baseline, masuk ke change control.

---

## Manajemen Pengadaan
Pengadaan dilakukan untuk komponen yang lebih efisien didapat dari vendor eksternal. Strategi pengadaan menekankan seleksi vendor berbasis kriteria objektif: kesesuaian kebutuhan, kualitas, biaya, jadwal, dan keamanan.

**Ruang lingkup pengadaan (contoh item):**
- Infrastruktur cloud/hosting (IaaS)
- Payment gateway (API & biaya transaksi)
- Lisensi/asset desain (ikon/ilustrasi/tool)
- Jasa security testing eksternal (penetration test/audit)
- Perangkat testing tambahan (bila diperlukan)

**Proses persetujuan pengadaan (ringkas):**
- Pengadaan kecil: dapat disetujui PM setelah evaluasi sederhana
- Pengadaan sedang: disetujui PM + sponsor + perwakilan fungsi pengadaan internal
- Pengadaan besar: disetujui PM + sponsor + tim + PMO internal

---

## Manajemen Komunikasi
Komunikasi proyek mengikat seluruh fungsi: sponsor, PM, tim delivery, QA/UX, operasional, dan stakeholder eksternal. Targetnya memastikan keputusan terdokumentasi, isu cepat naik eskalasi, serta progres dapat diverifikasi berbasis artefak.

**Artefak komunikasi utama:**
- Laporan status (progres vs baseline, isu, risiko, biaya ringkas)
- Decision log dan change log
- Notulen rapat & action item
- Ringkasan hasil uji (usability) untuk stakeholder

**Ritme komunikasi:**
- Weekly sync (tim inti): progres deliverable, isu, risiko, next action
- Gate review (milestone): validasi artefak dan persetujuan lanjut fase
- Monthly sponsor review (jika diperlukan): fokus scope–time–cost–risk

---

## Manajemen Stakeholder
Stakeholder dianalisis berdasarkan power–interest agar strategi keterlibatan tepat sasaran. Keterlibatan aktif stakeholder kunci memperkecil risiko hambatan jadwal/biaya/kualitas, terutama untuk keputusan scope dan validasi kebutuhan pengguna.

**Contoh klasifikasi power–interest:**
- **Key Players:** sponsor, steering committee, CCB, PM, end-users, mitra Hero
- **Keep Satisfied:** engineering lead, payment provider
- **Keep Informed:** operations/customer support lead, QA/UX lead
- **Minimal Effort:** komunitas lokal (sebagai pihak pendukung/peluang)

---

## Manajemen SDM (HR)
### Struktur Organisasi Proyek
> Simpan file gambar ke: `docs/images/homehero_org_chart.png`

![Org Chart](docs/images/homehero_org_chart.png)

### RACI (ringkas)
RACI digunakan untuk memperjelas siapa yang **Responsible**, **Accountable**, **Consulted**, dan **Informed** untuk aktivitas utama. Perubahan tanggung jawab harus melalui review PM dan mengikuti change control.

### Staffing Management (Akuisisi, Kalender Resource, Evaluasi, Reward)
Akuisisi SDM dilakukan melalui negosiasi PM dengan functional/department manager untuk menugaskan resource sesuai struktur organisasi proyek. Pengelolaan kalender resource disusun agar kebutuhan jam kerja tiap peran terlihat, kapan peran perlu ditambah, dan kapan dapat dilepas.

> Simpan file gambar ke: `docs/images/homehero_resource_histogram.png`

![Resource Histogram](docs/images/homehero_resource_histogram.png)

**Kebijakan SDM utama:**
- Training tidak dijadwalkan bila skill set memadai; bila ada gap, pembiayaan diambil dari reserve.
- PM melakukan evaluasi kinerja sepanjang proyek dan memberi umpan balik ke functional manager sebelum release resource.
- Reward non-monetary dirancang realistis: gathering apresiasi, sertifikat, publikasi internal, dan penghargaan untuk top performer.

---

## Governance & Change Control
Pengendalian perubahan diberlakukan untuk menjaga integritas baseline scope–schedule–cost. Setiap perubahan harus:
1) diajukan sebagai change request,  
2) dianalisis dampaknya (scope, jadwal, biaya, kualitas, risiko),  
3) disetujui pihak berwenang (sponsor/CCB),  
4) diintegrasikan ke rencana proyek dan dikomunikasikan ulang.

---

## Kesimpulan dan Saran
### Kesimpulan
Baseline Nov–Des 2025 adalah pendekatan yang logis dan dapat dipertanggungjawabkan karena menghasilkan artefak konkret: kebutuhan, desain, prototipe, hasil uji, serta laporan akhir. Roadmap Jan–Apr 2026 menjadi jalur implementasi operasional yang tidak mengganggu penyelesaian deliverable baseline. Dari sisi finansial, evaluasi 3 tahun menunjukkan NPV positif pada berbagai skenario dan discount rate, sehingga proyek robust terhadap variasi asumsi.

### Saran
- Perkuat strategi trust & safety (verifikasi mitra, SOP layanan, mekanisme dispute) karena ini faktor adopsi kunci.
- Jadikan hasil usability testing sebagai “prioritas tertinggi” untuk iterasi UX, karena biaya perbaikan paling murah sebelum implementasi produksi.
- Saat masuk roadmap, tetapkan standar keamanan minimal (audit, security testing) sebelum integrasi pembayaran produksi dan go-live.
- Kunci governance: change request harus disiplin agar scope creep tidak menggerus jadwal dan biaya.

---

## Dokumentasi Prototype
Bagian ini disiapkan untuk menampung bukti prototype dan uji kegunaan.

### 1) Link Prototype
- Figma/Prototype Link: `TULISKAN_LINK_DI_SINI`

### 2) User Flow yang Didokumentasikan
- Onboarding & login
- Jelajah layanan (kategori, detail)
- Booking & penjadwalan layanan
- Pemilihan mitra “Hero” + transparansi harga
- Pembayaran (mock flow)
- Rating & review + laporan masalah (concept flow)

### 3) Screenshot Prototype (wajib)
Simpan gambar di `docs/prototype/` lalu tautkan di bawah ini:

- `docs/prototype/01-home.png` — Home/Dashboard  
- `docs/prototype/02-service-list.png` — Daftar layanan  
- `docs/prototype/03-service-detail.png` — Detail layanan  
- `docs/prototype/04-booking.png` — Booking & jadwal  
- `docs/prototype/05-payment.png` — Pembayaran (mock)  
- `docs/prototype/06-review.png` — Rating & review  
- `docs/prototype/07-profile.png` — Profil & preferensi  

Contoh penyematan:
![Home](docs/prototype/01-home.png)

### 4) Ringkasan Usability Testing
- Metode: task-based testing
- Jumlah partisipan: `ISI`
- Ringkasan temuan: `ISI`
- Perbaikan prioritas: `ISI`
- Dampak perbaikan: `ISI`

---

## Daftar Pustaka
1. Project Management Institute (PMI). *Earned Value Management (EVM) – concepts and metrics*. https://www.pmi.org/  
2. Investopedia. *Net Present Value (NPV)*. https://www.investopedia.com/terms/n/npv.asp  
3. Investopedia. *Return on Investment (ROI)*. https://www.investopedia.com/terms/r/returnoninvestment.asp  
4. Investopedia. *Payback Period*. https://www.investopedia.com/terms/p/paybackperiod.asp  
5. PMI / PMBOK Guide (konsep baseline, change control, risk responses). https://www.pmi.org/pmbok-guide-standards  
6. OWASP Foundation. *OWASP Top 10 (security awareness for web/app)*. https://owasp.org/www-project-top-ten/  
7. ISO/IEC 25010. *System and software quality models (overview)*. https://iso25000.com/index.php/en/iso-25000-standards/iso-25010  
