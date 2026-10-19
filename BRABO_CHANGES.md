# Brabo preparation changes

Prepared locally on 2026-10-19. The owner authorized publication to brabo1-com on 2026-10-19. No remote commit has been published yet. Original source: `dyad-sh/portal-mini-store-template@05e29f6b18d386d1690b37595800304d679a2274`.

## Purpose and compatibility

Preserve template features and component-selection protocol while preparing an independently distributed source tree. Original licenses and historical notices are retained. The component tagger runtime is byte-identical to the reviewed npm package; only local distribution metadata/paths changed. `data-dyad-*`, `DYAD_DISABLE_DB_PUSH` and the existing cart storage key are compatibility identifiers, not network destinations.

The upstream MIT declaration and original `© 2024 Dyad Snacks. Crafted with passion.` footer notice are retained in LICENSE/notices/source comment. This refines the earlier review: the HTML entity `&copy;` carries an original notice even though no separate LICENSE file was supplied. Brabo store branding and six original local SVG snack illustrations replace external demo imagery. Customer-provided external images remain supported. Database/authentication/orders/roles are preserved. The existing Gmail delivery integration remains; SMTP verification is skipped during build or when credentials are absent. No email was sent. Docker/Compose now include the local vendor package and pinned tooling; the upstream unrelated MongoDB service is replaced by explicit configuration of your own compatible PostgreSQL service, without substituting the database adapter.

Two build CPUs and a template-local output tracing root bound build resources and prevent tracing the parent Electron checkout. These are explicit preparation settings.

## Files changed from upstream

- `.env.example`
- `.gitignore`
- `.npmrc`
- `Dockerfile`
- `README.md`
- `docker-compose.yml`
- `eslint.config.mjs`
- `next.config.ts`
- `package.json`
- `pnpm-lock.yaml`
- `src/app/(frontend)/layout.tsx`
- `src/app/(frontend)/page.tsx`
- `src/components/site-header.tsx`
- `src/endpoints/seed/snacks.ts`
- `src/payload.config.ts`

## Files excluded/replaced

None.

## Added files

- `.dockerignore`
- `BRABO_SOURCE.json`
- `DEPENDENCIES.json`
- `LICENSE`
- `LICENSES/Brabo-assets-MIT.txt`
- `LICENSES/Next-Dockerfile-MIT.txt`
- `LICENSES/Payload-MIT.txt`
- `LICENSES/shadcn-MIT.txt`
- `THIRD_PARTY_NOTICES.md`
- `public/images/snacks/candy.svg`
- `public/images/snacks/chips.svg`
- `public/images/snacks/cookies.svg`
- `public/images/snacks/crackers.svg`
- `public/images/snacks/drinks.svg`
- `public/images/snacks/nuts.svg`
- `vendor/nextjs-webpack-component-tagger/LICENSE`
- `vendor/nextjs-webpack-component-tagger/README.md`
- `vendor/nextjs-webpack-component-tagger/lib/index.cjs`
- `vendor/nextjs-webpack-component-tagger/lib/index.d.cts`
- `vendor/nextjs-webpack-component-tagger/lib/index.d.ts`
- `vendor/nextjs-webpack-component-tagger/lib/index.js`
- `vendor/nextjs-webpack-component-tagger/package.json`
- `BRABO_CHANGES.md`
- `BRABO_FILES.json`

## Remaining release work

Content publication was explicitly authorized on 2026-10-19. Remaining: actual own-repository commits/pins; own hosting for desktop preview assets; desktop creation with Dyad destinations blocked and process-wide network observation. This local preparation does not prove those checks. Full Portal checkout, order, reset-password/email and deploy flows are not certified by the build and HTTP smoke. Current upstream versions and their peer/deprecation warnings remain documented; no broad dependency upgrade is claimed.

## Publication preparation — 2026-10-19

Added `public/brabo-template-preview.svg`, an original Brabo card illustration under the included `LICENSES/Brabo-assets-MIT.txt`. Content publication to this template's brabo1-com repository is authorized. Local allowlist/hashes include the illustration and current authorization metadata. Upload and pinned public URLs remain unverified until a remote commit exists.

Publicação pela interface do GitHub: o LICENSE do plugin recebeu somente uma quebra de linha final; texto e avisos preservados. DEPENDENCIES.json conserva o hash da distribuição original; BRABO_FILES.json registra os bytes publicados.

Compatibilidade desktop T137: Node24/pnpm11.1.2 validados; engines/packageManager/README alinhados. A aprovação anterior de Sharp foi migrada de onlyBuiltDependencies para allowBuilds; script de unrs-resolver explicitamente recusado. Política de idade mínima1440 preservada, sem aprovação genérica de scripts.
