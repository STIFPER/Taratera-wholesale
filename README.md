# TARATERA Wholesale — notes for future agents

Repository: [STIFPER/Taratera-wholesale](https://github.com/STIFPER/Taratera-wholesale)

## Current implementation
- The age confirmation dialog is in the root `index.html` (`#ageGate` markup and `.age-gate*` CSS).
- English and Thai age-gate copy are intentionally on separate lines. The Thai text uses Noto Sans Thai; keep the paired language lines, centered alignment, and mobile spacing consistent when editing.
- Commit `8b138155cb2e016cfbd631e997dc085fba53fc3a` updated the bilingual typography and alignment.
- That source update was verified on the new Cloudflare Pages site, the old Cloudflare Pages site, and GitHub Pages. The old site is intentionally still online.

## Important context
- The age prompt is a self-declaration only. It does not verify identity or establish that the business or website meets legal requirements.
- Do not describe the site as legally compliant based only on the age prompt. Check current official Thai rules and the operator's actual permits before making compliance claims.
- This repo is deployed to public sites. Treat changes to `index.html` on the default branch as production-impacting; inspect the diff and deployment result.
- Do not delete, disable, or redirect the old Cloudflare Pages site without explicit user approval.

## For edits
1. Read the current `index.html` and this note before changing the age dialog.
2. Preserve the bilingual text and responsive layout unless the user asks to change them.
3. After edits, verify both Cloudflare Pages URLs and the GitHub Pages mirror.
