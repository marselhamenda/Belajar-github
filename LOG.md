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

---

## 2026-11-25 — Sumber: video TikTok @sinyal.kini "5 repo GitHub yang lagi viral minggu ini" (dibagikan user untuk dipelajari)

- **thedotmack/claude-mem** — https://github.com/thedotmack/claude-mem — memori — Konteks persisten lintas sesi untuk agent: merekam semua yang dilakukan agent, mengompresnya, dan menyuntikkannya ke sesi berikutnya. 119rb stars. — **Berguna** (konsep): prinsip yang sama dengan sistem memori Muse user.
- **pingdotgg/t3code** — https://github.com/pingdotgg/t3code — agent tooling — Mengendalikan Claude Code/Codex dari komputer atau HP mana pun. 78,9rb stars. — **Kurang berguna** langsung: user memakai Muse app, bukan Claude Code; idenya (remote control agent) sudah tercover.
- **D4Vinci/Scrapling** — sudah dicatat di entri 2026-11-25 sebelumnya (daftar @adityagnwann). Muncul lagi di daftar viral ini (+8.712 stars/minggu menurut video).
- **milind-soni/OpenMausBot** — https://github.com/milind-soni/OpenMausBot — agent/sandbox — Alternatif Grok Bot open-source dengan VM sendiri yang bisa dipakai bot. 27,7rb stars. — **Kurang berguna**: peran VM/bawahan sudah dipegang Simular Box.
- **Nutlope/hallmark** — https://github.com/Nutlope/hallmark — desain — Skill desain anti "AI slop": bikin UI hasil AI tidak kelihatan generik. — **Berguna**: sejalan aturan user "jangan kelihatan AI-nya" untuk video & Space.

---

## 2026-11-25 — Sumber: carousel BuildWithZam "5 repo agent pintar" (screenshot dari user)

- **vectorize-io/hindsight** — https://github.com/vectorize-io/hindsight — memori — Memori agent yang belajar dari pengalaman (bukan sekadar menyimpan). 63,3rb stars. — **Berguna** (konsep): arah evolusi sistem memori agent.
- **obra/superpowers** — https://github.com/obra/superpowers — skills — Framework/plugin skills untuk coding agent (kumpulan skill terstruktur + cara pakainya). 250rb+ stars (menurut fork terjemahannya). — **Berguna** (konsep): sejalan sistem skill yang user bangun; struktur skill-nya bisa jadi contoh.
- **DietrichGebert/ponytail** — https://github.com/DietrichGebert/ponytail — workflow — Skill yang memaksa agent menaiki "tangga YAGNI": selalu pilih solusi paling minimal yang benar, tidak over-engineering. — **Berguna** (konsep): sejalan aturan user "jangan buang waktu buat hal yang nggak diminta".
- **mksglu/context-mode** — https://github.com/mksglu/context-mode — hemat konteks — Plugin lokal yang menahan output tool di luar context window agent (sandbox + pencarian SQLite FTS5), klaim hemat konteks sampai 99%. 34,4rb stars. — **Berguna** (konsep): user di plan gratis; manajemen konteks = manajemen credit.
- **affaan-m/everything-claude-code (ECC)** — https://github.com/affaan-m/everything-claude-code — konfigurasi agent — Koleksi lengkap konfigurasi Claude Code: agents, skills, hooks, commands, rules, dari pemenang hackathon Anthropic. — **Kurang berguna** langsung (bukan untuk Muse), tapi bisa jadi inspirasi struktur rules/skill.

---

## 2026-11-25 — Sumber: video TikTok @xismusx tentang FreeLLMAPI (dibagikan user untuk dipelajari)

- **tashfeenahmed/freellmapi** — https://github.com/tashfeenahmed/freellmapi — AI gratis — Satu endpoint /v1 yang menggabungkan free tier 87 provider LLM (Gemini, Groq, Mistral, NVIDIA, OpenRouter, dll): klaim 10,1 miliar token gratis/bulan dari 1.313 endpoint model, dengan routing/failover otomatis kalau satu provider penuh. 58,1rb stars. — **Berguna** (konsep/cadangan): user sensitif credit dan di plan gratis; tapi ini untuk Claude Code/CLI (bukan Muse), dan tetap butuh API key gratis dari tiap provider (daftar sendiri). Tidak dipasang — hanya dicatat.

---

## 2026-11-25 — Sumber: permintaan langsung user ("Open generative ai — tambahin di github dan pelajari")

- **Anil-matcha/Open-Generative-AI** — https://github.com/Anil-matcha/Open-Generative-AI — video/gambar AI — Studio open-source (self-hosted, MIT) untuk generate gambar & video AI: 600+ model dalam 14 studio (Image, Video, Audio, Lip Sync, Cinema, Workflows), tanpa filter konten dan tanpa biaya langganan aplikasinya. 36,2rb stars. — **Berguna, dengan catatan penting**: aplikasinya memang gratis, tapi mesin generate-nya memakai API MuAPI yang berbasis kredit (berbayar per generate) — jadi ini BUKAN jalan gratis untuk video AI; yang gratis hanya dashboard/studionya. Relevan kalau suatu saat user punya budget kredit API; untuk sekarang (modal nol) belum bisa menggantikan pipeline video yang ada.

---

## 2026-11-25 — Sumber: permintaan langsung user (berurutan: Voice Studio, Open SEO, AppFlowy, OpenProject)

- **debpalash/VoiceStudio** — https://github.com/debpalash/VoiceStudio — suara/TTS — Alternatif ElevenLabs open-source yang berjalan LOKAL di perangkat sendiri: voice cloning, voice design, dubbing video, dikte, transkripsi, dan narasi dalam 646 bahasa; jalan di laptop/HP/server. Ada juga versi Cloud & Pro berbayar. 118rb stars. — **Sangat berguna (potensial)**: kebutuhan voiceover user konstan (Kantong Aman, FB "Sell", Sahabat Kiko) dan pilihan suara di Muse terbatas; lokal = tanpa biaya per pakai. Catatan jujur: kualitas/speed tergantung hardware perangkat yang menjalankan, dan mutu narasi Bahasa Indonesia-nya belum terverifikasi.
- **jamiepine/voicebox** — https://github.com/jamiepine/voicebox — suara/TTS — Alternatif lain "open-source AI voice studio" (clone, dictate, create). 61,2rb stars. — **Berguna**: pembanding VoiceStudio kalau yang utama tidak cocok.
- **every-app/open-seo** — https://github.com/every-app/open-seo — SEO — Alternatif open-source Semrush/Ahrefs: riset keyword, rank tracking, insight kompetitor, backlink, audit situs, AI visibility; punya MCP server + agent skills. Modelnya pay-as-you-go dengan API key DataForSEO sendiri (data tetap berbayar per pemakaian); hosted trial gratis / $10/bln. 28,8rb stars. — **Berguna**: buat SEO YouTube Sahabat Kiko dan gig artikel SEO di starter pack freelance user.
- **AppFlowy-IO/AppFlowy** — https://github.com/AppFlowy-IO/AppFlowy — produktivitas — Workspace kolaboratif AI open-source, alternatif Notion: proyek, wiki, dan tim dalam satu tempat, data dipegang sendiri (bisa self-host). 79,5rb stars. — **Berguna** (opsional): calon pengganti Notion untuk catatan/proyek pribadi user; sistem user saat ini sudah berjalan di Space Muse.
- **opf/openproject** — https://github.com/opf/openproject — manajemen proyek — Software manajemen proyek open-source terkemuka, alternatif Jira: agile planning, issue tracking, manajemen portofolio. 17,7rb stars. — **Kurang berguna** untuk user saat ini: ini alat PM tim skala besar; sistem kantor user sudah tercover Ruang Kerja + goals di Muse.

---

## 2026-11-25 — Sumber: video TikTok @garryaudie tentang andrej-karpathy-skills (dibagikan user untuk dipelajari)

- **multica-ai/andrej-karpathy-skills** — https://github.com/multica-ai/andrej-karpathy-skills — perilaku agent — Satu file CLAUDE.md berisi panduan perilaku untuk Claude Code yang diturunkan dari observasi Andrej Karpathy soal jebakan LLM saat coding. Isinya BUKAN perintah "lakukan ini", melainkan 4 prinsip larangan/kebiasaan: (1) Think Before Coding — jangan berasumsi, jangan sembunyikan kebingungan, tanyakan kalau ambigu; (2) Simplicity First — kode minimum yang menyelesaikan masalah, tanpa fitur/abstraksi spekulatif; (3) Surgical Changes — sentuh hanya yang diminta, jangan refactor kode tak terkait; (4) Goal-Driven Execution — definisikan kriteria sukses yang bisa diverifikasi, loop sampai terbukti. ~200rb stars menurut video. — **Sangat berguna**: isinya nyaris sama dengan sifat kerja yang user tetapkan sendiri (jangan ngeyel, jangan kerjakan yang nggak diminta, double-check hasil) — validasi eksternal bahwa aturan-aturan itu memang praktik terbaik; prinsipnya sudah diterapkan dalam cara kerja Muse untuk user.

---

## 2026-11-25 — Sumber: permintaan langsung user (ComfyUI, Ollama)

- **Comfy-Org/ComfyUI** — https://github.com/Comfy-Org/ComfyUI — gambar/video AI lokal — GUI + API + backend model difusi paling modular: antarmuka graph/nodes untuk merangkai workflow generate gambar (dan video via node) secara LOKAL, diklaim sebagai local inference engine tercepat. 148rb stars. — **Sangat berguna (potensial)**: ini mesin lokal di balik banyak workflow gambar/video AI — relevan untuk produksi visual Kantong Aman/Sahabat Kiko tanpa biaya per generate. Catatan jujur: butuh GPU/hardware memadai agar cepat; belum dicoba di perangkat user.
- **ollama/ollama** — https://github.com/ollama/ollama — LLM lokal — Cara termudah menjalankan LLM open-source secara lokal (Kimi, GLM, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma, dll) dengan satu perintah, lengkap dengan API lokal. 188rb stars. — **Berguna**: fondasi kalau user mau eksperimen AI lokal gratis (mis. otak tambahan untuk bawahan di Simular Box); kualitas model lokal di bawah model cloud frontier dan butuh RAM/GPU sesuai ukuran model.

---

## 2026-11-25 — Sumber: video TikTok @aishift.id "5 Repo Gratis" (DITONTON penuh, bukan dari deskripsi)

Tema video: repo gratis yang kodenya Rp0, lalu dijual sebagai jasa. Angka stars di bawah = data GitHub saat dicek (angka di video sedikit lebih lama).

- **zhouxiaoka/autoclip** — https://github.com/zhouxiaoka/autoclip — video — Tool desktop AI open-source (MIT): satu link video panjang (podcast/wawancara/kursus) otomatis jadi klip pendek + subtitle + cover + caption, siap untuk TikTok/Reels/Shorts. 15,9rb stars. — **Sangat berguna (potensial)**: ini persis mesin untuk proyek akun clipping TikTok user yang sedang diparkir — bahan bakar jasanya juga jelas (jasa klip untuk YouTuber/podcaster).
- **remotion-dev/remotion** — https://github.com/remotion-dev/remotion — video — Membuat video secara programatik dengan React: 1 template bisa dirender jadi ratusan video (video produk massal untuk brand). 75,6rb stars. — **Sangat berguna (potensial)**: cocok untuk video produk Kantong Aman skala banyak. CATATAN LISENSI (dari video, penting): gratis untuk perorangan/tim sampai 3 orang; perusahaan di atas itu kena ketentuan berbayar.
- **OpenHands/OpenHands** — https://github.com/OpenHands/OpenHands — agent coding — Platform pengembangan berbasis AI agent yang menulis kode sendiri (AI programmer). 94,3rb stars. — **Berguna** (konsep/komparasi): pembanding arsitektur agent coding; user sudah dilayani Muse + bawahan.
- **gitroomhq/postiz-app** — https://github.com/gitroomhq/postiz-app — sosmed — Tool penjadwalan media sosial agentic: kelola/jadwalkan banyak akun klien (Instagram/TikTok/YouTube) dari satu tempat. 42,3rb stars. — **Berguna**: user mengelola banyak akun (Kantong Aman, Sell, Sahabat Kiko, Pr Social) — penjadwalan terpusat bisa menghemat waktu; posting otomatis tetap dibatasi aturan tiap platform.
- **xiamuceer-j/MuMuAINovel** — https://github.com/xiamuceer-j/MuMuAINovel — novel — Asisten penulisan novel berbasis AI (GPL-3.0): alur karakter → alur cerita → bab, membantu merapikan novel untuk diterbitkan di platform novel online. 3,3rb stars. — **Berguna**: relevan langsung dengan proyek novel user "Chat Tengah Malam" (target Fizzo).

---

## 2026-11-25 — Sumber: video TikTok @herlambangawn "9 Repo GitHub pengganti software berbayar" (DITONTON penuh)

Lima dari 9 repo di video ini sudah dicatat sebelumnya atas permintaan langsung user (Open Generative AI, VoiceStudio, OpenSEO, AppFlowy, OpenProject — video inilah sumber daftar nama itu). Empat sisanya baru:

- **OpenWhispr/openwhispr** — https://github.com/OpenWhispr/openwhispr — suara — Aplikasi dikte voice-to-text (pengganti Wispr Flow): model lokal (NVIDIA Parakeet/Whisper) atau cloud dengan API key sendiri, privacy-first, cross-platform, bisa offline. 12,1rb stars. — **Berguna**: dikte lokal gratis untuk naskah/caption tanpa mengetik.
- **calcom/cal.diy** — https://github.com/calcom/cal.diy — produktivitas — Infrastruktur penjadwalan open-source (pengganti Calendly), repo open-source Cal.com untuk pemakaian pribadi: halaman booking yang tersinkron Google Calendar/Outlook. 50,3rb stars. — **Kurang berguna** saat ini: user belum menjual jasa konsultasi/booking; relevan nanti kalau freelance-nya jalan.
- **chatwoot/chatwoot** — https://github.com/chatwoot/chatwoot — customer support — Platform live-chat & omni-channel desk open-source (pengganti Intercom/Zendesk): satu inbox untuk web, email, WhatsApp, Instagram. 40,5rb stars. — **Kurang berguna** saat ini: untuk bisnis dengan volume chat pelanggan; user belum di tahap itu.
- **CapSoftware/Cap** — https://github.com/CapSoftware/Cap — video — Perekam layar open-source (pengganti Loom): rekam layar + kamera + mic untuk demo produk/tutorial, share lewat link. ★24,6rb menurut teks di video. — **Berguna**: untuk video tutorial/demo (mis. tutorial seperti video Pexel) dengan tampilan profesional.
