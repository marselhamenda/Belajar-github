# Log Belajar GitHub

Format per temuan: tanggal — repo + link — bidang — ringkasan — kegunaan + alasan.

---

## 2026-11-25 — Sumber: postingan TikTok @adityagnwann "15 Repo Full Stack AI Agent" (dibagikan user untuk dipelajari)

### Stack inti agent
- **NousResearch/hermes-agent** — https://github.com/NousResearch/hermes-agent — agent skills — Framework agent yang "tumbuh bersama penggunanya" (self-improving, belajar dari pemakaian). 266rb stars. — **Berguna** (konsep): relevan buat sistem kantor/bawahan user, tapi user sudah punya Muse; yang diambil idenya, bukan dipasang.
- **Fission-AI/OpenSpec** — https://github.com/Fission-AI/OpenSpec — agent skills / coding — Spec-driven development: tulis spesifikasi dulu, baru AI coding. 75,7rb stars. — **Berguna**: disiplin spec-first bisa menaikkan kualitas entry coding make.fun.
- **github/spec-kit** — https://github.com/github/spec-kit — agent skills / coding — Toolkit resmi GitHub untuk spec-driven development. 151rb stars. — **Berguna**: pasangan OpenSpec, standar resmi dari GitHub.
- **JuliusBrussee/caveman** — https://github.com/JuliusBrussee/caveman — hemat token — Skill + proxy lokal yang memangkas jawaban & tool call coding agent supaya hemat token ("why use many token when few token do trick"). 122rb stars. — **Berguna**: user di plan gratis dan sensitif soal credit; konsep hemat tokennya langsung relevan.
- **headroomlabs-ai/headroom** — https://github.com/headroomlabs-ai/headroom — hemat token — Mengompres output tool, log, file, dan RAG chunk sebelum masuk LLM; klaim ~20% token lebih hemat untuk coding agent. 80,8rb stars. — **Berguna**: alasan sama seperti caveman.

### Data & memori
- **D4Vinci/Scrapling** — https://github.com/D4Vinci/Scrapling — data — Framework web scraping tangguh, dari satu request sampai crawl besar, tahan anti-bot. 105rb stars. — **Berguna**: buat riset & monitoring web (pantauan cuan, cek harga, riset bounty).
- **docling-project/docling** — https://github.com/docling-project/docling — data — Mengubah dokumen (PDF, Office) jadi data siap pakai gen AI. 71rb stars. — **Kurang berguna** saat ini: user jarang memproses dokumen besar.
- **VectifyAI/PageIndex** — https://github.com/VectifyAI/PageIndex — data — RAG tanpa vector: indeks dokumen berbasis penalaran. 40,8rb stars. — **Kurang berguna** saat ini: belum ada kebutuhan RAG dokumen.
- **mem0ai/mem0** — https://github.com/mem0ai/mem0 — memori — Lapisan memori persisten untuk AI agent. 69,4rb stars. — **Berguna** (konsep): sejalan dengan sistem memori user di Muse.

### Sandbox
- **daytonaio/daytona** — https://github.com/daytonaio/daytona — sandbox — Platform sandbox/dev environment aman untuk menjalankan kode hasil AI. — **Kurang berguna**: user sudah punya Simular Box (2 box) untuk peran yang sama.

### Monitoring & prompt
- **sansan0/TrendRadar** — https://github.com/sansan0/TrendRadar — monitoring — Monitor tren & opini publik multi-platform dengan AI, RSS, MCP, dan alert pintar. 63,9rb stars. — **Berguna**: konsepnya pas buat pantauan cuan harian; catatan: platform yang dipantau mayoritas platform Tiongkok (Weibo, Douyin, Bilibili), jadi buat pasar Indonesia manfaat langsungnya terbatas.
- **danielmiessler/fabric** — https://github.com/danielmiessler/fabric — prompt — Library pola prompt AI crowdsourced untuk tugas-tugas umum (ringkas, analisis, ekstrak). — **Berguna**: pola prompt siap pakai buat konten & riset.

### Video
- **heygen-com/hyperframes** — https://github.com/heygen-com/hyperframes — video — Editor video AI open-source dari HeyGen: edit footage sendiri atau buat/remake video dengan coding agent. 89,9rb stars. — **Sangat berguna**: relevan langsung ke produksi video Kantong Aman, FB "Sell", dan Sahabat Kiko.
- **OpenMontageInc/OpenMontage** — https://github.com/OpenMontageInc/OpenMontage — video — Sistem produksi video agentic open-source: 12 pipeline produksi, 100+ tools, 700+ agent skills. 83,3rb stars. — **Sangat berguna**: paling dekat dengan workflow video user sekarang (stills + pipeline + agent), calon adopsi terkuat dari daftar ini.

### Belajar
- **patchy631/ai-engineering-hub** — https://github.com/patchy631/ai-engineering-hub — belajar — Tutorial mendalam LLM, RAG, dan aplikasi AI agent nyata. 42,1rb stars. — **Berguna**: bahan belajar terstruktur buat sesi belajar harian.
