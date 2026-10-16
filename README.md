# ECO AI v1.0 — Interactive Learning Prototype

Static website ready for GitHub + Cloudflare Pages.

## Deploy
1. Open GitHub repository `zynexgate-hub/ai-eco-filter`.
2. Upload **all contents** of this folder into repository root (not the parent folder itself): `index.html`, `style.css`, `script.js`, `assets/docs/`.
3. Commit changes to `main`.
4. Cloudflare Pages automatically redeploys. Build preset None; build command blank; output directory `.`.
5. Open https://ai-eco-filter.pages.dev after deployment completes.

## Scope and limits
- Based on provided E-Modul PBL-STEM and E-LKPD 1/2. Proposal is an internal design reference and not distributed in the public site.
- **Tutor is an offline rule-based demonstration**, NOT an AI model, NOT RAG, and not connected to OpenAI API. Responses are curated hints and can be limited for unseen questions.
- Progress and attendance are **localStorage demonstrations**. No server database, real user authentication, teacher review, cross-device synchronization, or official school attendance. Do not rely on this as an official attendance record.
- Actual AI and official attendance require a secure backend (e.g. Cloudflare Workers + D1), server-side API credentials, per-user authentication and authorization, teacher-defined sessions, rate limits, privacy controls, and source retrieval (RAG) over reviewed materials.
- PDF files are distributed publicly by Cloudflare Pages. Confirm publishing permission before deploying publicly.
- Do not assume Ecorem-EcoFilter efficacy; do not invent formula quantities or experimental data. Source material may require teacher confirmation on compartment count.

## Files
- `index.html` layout and page sections
- `style.css` responsive styling
- `script.js` navigation, missions, demo tutoring, local check-in
- `assets/docs/EModul.pdf`, `ELKPD1.pdf`, `ELKPD2.pdf`


## E-LKPD interaktif (pembaruan)
E-LKPD 1 dan 2 sekarang berupa HTML mandiri di assets/docs/E-LKPD1.html dan E-LKPD2.html, menggantikan tautan PDF lama. Tombol di Perpustakaan membuka HTML tersebut. Simpan otomatis memakai localStorage pada browser/perangkat yang sama; gunakan Ekspor jawaban JSON sebagai cadangan. Belum ada sinkronisasi akun/guru atau pengumpulan tugas ke server. Dokumen E-Modul PDF tetap dipertahankan.
