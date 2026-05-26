Deploy fix countdown Expires len Railway

Repo: hahieume-ui/tikfinity-license-server

Da fix:
- Server dung UTC: process.env.TZ='UTC'
- API verify tra them license va expiresAt ISO UTC
- API tao license tra email/license/expiresAt/licenseData
- Them GET /api/licenses de sync license
- Web admin cot Expires hien countdown tu expiresAt
- Het han hien EXPIRED
- Tu refresh data moi 30 giay

Giu data member/license key:
- Khong upload database.json len GitHub.
- File .gitignore da chan database.json.
- Chi upload code: server.js, package.json, Procfile, nixpacks.toml, database.sample.json, .gitignore.
- Neu Railway dang co data runtime/volume thi deploy code moi se giu data.

