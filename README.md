# soc
> Jika kita udah sering bahas tentang pentest, masa Kamsib gak bahas sisi defence. Maka dari itu, mampir sini ke pojok SOC. 

Sebuah organisasi yang memiliki [Sistem Elektronik](https://pse.kominfo.go.id/home), tentu tidak luput dari yang namanya serangan siber. Baik organisasi besar, maupun skala kecil. Demi mengatasi hal tersebut, organisasi perlu sebuah mekanisme untuk melindungi aset mereka. Salah satu solusinya adalah membentuk sebuah tim yang dapat menangangani serang siber. 

SOC (Security Operations Center) atau pusat operasi keamanan adalah unit terpusat yang menangani masalah keamanan pada tingkat organisasi dan teknis. SOC ini terdiri dari 3 pilar, yakni _people_, _process_, dan _technology_.

## Pengenalan
Lorem ipsum ...

## Tiga+ Pilar
Pilar pertama, confidentiality berarti keamanan informasi harus menjamin bahwa hanya pemilik sistem informasi yang memiliki hak akses informasi tertentu. “Rahasia berarti hanya orang yang berhak, yang bisa melihat data tersebut. Jika bisa dibaca oleh seseorang yang tidak berhak, artinya telah terjadi kebocoran data yang akan merugikan perusahaan dan juga pemilik data,” tutur Girindro. Pilar tersebut, kata dia, mempengaruhi bentuk kontrol dalam beberapa hal, seperti kontrol akses, izin akses file, dan enkripsi. Gambarannya, terkait akses control, sebuah organisasi dapat menerapkan penggunaan User ID, password, verifikasi dua langkah (2FA), dan biometrik. Kontrol akses ini harus disesuaikan dengan nilai suatu data (penting dan atau risiko).

Kedua, menyangkut izin akses file artinya terkait dengan izin siapa saja yang boleh mengakses file, mengedit, membaca, dan termasuk siapa yang bisa memberikan izin akses. Dan, terakhir, enkripsi berarti data yang sifatnya rahasia haruslah dienkripsi, bisa menggunakan metode symmetric atau asymmetric. Pilar kedua, integritas bersinggungan dengan jaminan kelengkapan informasi dan menjaganya dari kerusakan atau ancaman lain yang bisa mengubah informasi itu. Pendek kata, menurut Girindro, integrity ialah cara untuk memastikan bahwa informasi tersebut masih utuh, akurat, dan belum dimodifikasi oleh orang yang tidak berhak.

Dan, pilah terakhir, avaibility artinya bagaimana cara organisasi melalui keamanan informasinya menjamin pengguna untuk dapat mengakses informasi kapan pun tanpa adanya gangguan dan tidak dalam format yang tidak bisa digunakan. Pilar ini meyakinkan bahwa pengguna mempunyai kesempatan dan akses pada suatu informasi. “Pengguna dalam hal ini bisa jadi manusia atau komputer yang tentunya memiliki otorisasi untuk mengakses informasi,” ujar Girindro.

## Tier 
* Tier 1 Security Analyst
Triage Specialist (Separating the wheat from the chaff)
Tinjau lansiran terbaru untuk menentukan relevansi dan urgensi. Membuat tiket masalah baru untuk peringatan yang menandakan insiden dan memerlukan peninjauan Tingkat 2 / Respons Insiden. Menjalankan pemindaian kerentanan dan meninjau laporan penilaian kerentanan. Mengelola dan mengonfigurasi alat pemantauan keamanan (IDS, aturan korelasi, dll.).

* Tier 2 Security Analyst
Incident Responder (IT’s version of the First Responder)
Tinjau tiket masalah yang dibuat oleh Analis Tingkat 1. Memanfaatkan intelijen ancaman yang muncul (IOC, aturan yang diperbarui, dll.) Untuk mengidentifikasi sistem yang terpengaruh dan ruang lingkup serangan. Meninjau dan mengumpulkan data aset (konfigurasi, proses yang berjalan, dll.) pada sistem ini untuk penyelidikan lebih lanjut. Menentukan dan mengarahkan upaya perbaikan dan pemulihan.

* Tier 3 Expert Security Analyst
Threat Hunter (Hunts vs. defends)
Meninjau penemuan aset dan data penilaian kerentanan. Menjelajahi cara untuk mengidentifikasi ancaman diam-diam yang mungkin menemukan jalan mereka di dalam jaringan Anda, tanpa deteksi Anda, menggunakan intelijen ancaman terbaru. Melakukan uji penetrasi pada sistem produksi untuk memvalidasi ketahanan dan mengidentifikasi area kelemahan untuk diperbaiki. Merekomendasikan cara mengoptimalkan alat pemantauan keamanan berdasarkan penemuan perburuan ancaman.

* Tier 4 SOC Manager
Operations and Management (Chief Operating Officer for the SOC)
Mengawasi kegiatan tim SOC. Merekrut, mempekerjakan, melatih, dan menilai staf. Mengelola proses eskalasi dan meninjau laporan insiden. Mengembangkan dan melaksanakan rencana komunikasi krisis kepada CISO dan pemangku kepentingan lainnya. Menjalankan laporan kepatuhan dan mendukung proses audit. Mengukur metrik kinerja SOC dan mengomunikasikan nilai operasi keamanan kepada pemimpin bisnis.

## Cyber Kill Chain
Developed by Lockheed Martin, the Cyber Kill Chain® framework is part of the Intelligence Driven Defense® model for identification and prevention of cyber intrusions activity. The model identifies what the adversaries must complete in order to achieve their objective.
https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html

## Mini Project SIEM
### Security-Blue-Team
This repository will describe the details surrounding the SIEM (wazuh) mini project, which will cover all aspects of topology design, deployment, rules, integration, and fine tune.

#### Topology & Prototype
![My Image](https://raw.githubusercontent.com/13ihsan92/Security-Blue-Team/contributor/Images/Topology-jpg.jpg)

#### Docs & Articles
[Notion](https://13ihsan92.notion.site/Documentation-san-NBA-stl-b5f06c8384c34fbb877a1313cffd7804)

#### Other Refence About Rules, Architecture, & Compliance
- [Open Enterprise Security Architecture (O-ESA)](https://pubs.opengroup.org/security/o-esa/#_Toc291061776)
- [Security Architecture Patterns](https://www.opensecurityarchitecture.org/cms/library/patternlandscape)

**Original Mini Project Repository: [13ihsan92/Security-Blue-Team](https://github.com/13ihsan92/Security-Blue-Team/tree/contributor)**

---

Reviews the latest alerts to determine relevancy and urgency. Creates new trouble tickets for alerts that signal an incident and require Tier 2 / Incident Response review. Runs vulnerability scans and reviews vulnerability assessment reports. Manages and configures security monitoring tools (IDS, correlation rules, etc.).

Reviews trouble tickets generated by Tier 1 Analyst(s). Utilizes emerging threat intelligence (IOCs, updated rules, etc.) to identify affected systems and the scope of the attack. Reviews and collects asset data (configs, running processes, etc.) on these systems for further investigation. Determines and directs remediation and recovery efforts.

Reviews asset discovery and vulnerability assessment data. Explores ways to identify stealthy threats that may have found their way inside your network, without your detection, using the latest threat intelligence. Conducts penetration tests on production systems to validate resiliency and identify areas of weakness to fix. Recommends how to optimize security monitoring tools based on threat-hunting discoveries.

Supervises the activity of the SOC team. Recruits, hires, trains, and assesses the staff. Manages the escalation process and reviews incident reports. Develops and executes crisis communication plan to CISO and other stakeholders. Runs compliance reports and supports the audit process. Measures SOC performance metrics and communicates the value of security operations to business leaders.

