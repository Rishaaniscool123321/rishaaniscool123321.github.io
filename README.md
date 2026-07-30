# Rishaan Profile with Admin Panel

Public site:
- `/`

Admin page:
- `/admin/`

Admin username:
- `Rishaaniscool123321`

Admin password:
- `GitHub123`

## Important security limitation

GitHub Pages is a static hosting service. The username/password in the admin page
is visible to anyone who inspects the page source, so it is not secure authentication.

The admin panel saves changes in the current browser and can export a JSON backup.
To publish changes for all visitors, update `site-config.json` and the carousel files
in the GitHub repository.

For secure login and automatic publishing, use a backend such as Firebase,
Supabase, Cloudflare Pages Functions, or Netlify Functions.

Supported admin image uploads: PNG, JPEG, JPG, HEIF, HEIC, DNG and WebP. Videos are rejected.
