# Linsora website

Public site: https://scott4game.github.io/Linso-site/

English, Simplified Chinese and Japanese home, privacy and support pages. Published files are exclusively in `site/`; App source, model files, review materials, keys and private recordings must never be copied here.

## Deployment

Repository Settings → Pages → Build and deployment → Source: **GitHub Actions**. Pushes to `main` deploy through `.github/workflows/pages.yml`. The workflow publishes only `site/`.

The source uses relative links and works under `/Linso-site/`; no custom domain or DNS change is configured. Existing App Store/App links using `linsora.icqnft.com` are not changed by this deployment.

Local preview: `python3 -m http.server 8769 --directory site`. Check all three languages, privacy/support navigation, CSS and mobile overflow before pushing.

Content baseline: Linsora 1.0.1 update, 2026-11-10. Provider keys are user supplied; third-party text processing requires confirmation. System read aloud and offline transcription do not send audio to AI servers. Model permission and App Store review work remain separate from website hosting.
