# Contributing to CoreTrees · Berkontribusi ke CoreTrees

**EN** — Thanks for taking the time to contribute! These guidelines apply to every CoreTrees repository.<br/>
**ID** — Terima kasih telah meluangkan waktu untuk berkontribusi! Panduan ini berlaku untuk semua repositori CoreTrees.

Please also read our [Code of Conduct](./CODE_OF_CONDUCT.md) · Mohon baca juga [Kode Etik](./CODE_OF_CONDUCT.md).

---

## 1. Ways to contribute · Cara berkontribusi

**🐛 Report a bug** — open an issue using the *Bug report* template. · Laporkan bug lewat templat *Bug report*.<br/>
**💡 Suggest a feature** — open an issue using the *Feature request* template. · Usulkan fitur lewat templat *Feature request*.<br/>
**📝 Improve docs** — typos, clarity, examples are all welcome. · Perbaikan dokumentasi sangat diterima.<br/>
**🔧 Send a pull request** — fix a bug or implement an agreed feature. · Kirim PR untuk perbaikan/fitur yang disepakati.

For anything larger than a small fix, please open an issue first so we can align on the approach. · Untuk perubahan yang lebih besar, buka issue terlebih dahulu agar pendekatannya selaras.

## 2. Development workflow · Alur pengembangan

**Fork & clone** — `git clone https://github.com/<you>/<repo>.git && cd <repo>`<br/>
**Create a focused branch** — `git checkout -b feat/short-description` (or `fix/`, `docs/`, `refactor/`, `chore/`, `test/`)<br/>
**Install & run** — see the repository README for exact commands, e.g. `npm install && npm run dev`, `go run ./...`, `docker compose up`<br/>
**Commit** — keep changes small; commit early, commit often.

## 3. Branch & commit conventions · Konvensi branch & commit

**Branches:** `feat/…`, `fix/…`, `docs/…`, `refactor/…`, `test/…`, `chore/…`, `ci/…`

**Commits** follow [Conventional Commits](https://www.conventionalcommits.org/) · Commit mengikuti Conventional Commits:

`feat(auth): add refresh-token rotation`<br/>
`fix(api): prevent race condition on ticket accept`<br/>
`docs(readme): clarify local setup steps`

Type list: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`, `revert`.

## 4. Pull request checklist · Daftar periksa PR

Before requesting review · Sebelum meminta review:

| Check · Periksa |
|---|
| The change is focused and does one thing well · Perubahan fokus dan mengerjakan satu hal. |
| Code follows the project's style & lint rules (`lint`/`format` pass) · Lolos lint & format. |
| Tests added or updated, and the suite is green · Test ditambah/diperbarui dan hijau. |
| No secrets, credentials, or `.env` values committed · Tidak ada rahasia/kredensial yang ikut ter-commit. |
| No leftover `TODO`/`FIXME`, debug logs, or commented-out code · Tanpa sisa TODO/FIXME atau log debug. |
| Docs/README updated if behavior changed · Dokumentasi diperbarui bila perilaku berubah. |
| PR description explains **what** changed and **why** · Deskripsi PR menjelaskan apa dan mengapa. |

## 5. Code quality bar · Standar kualitas kode

CoreTrees follows Clean Architecture, SOLID, DRY, and KISS · CoreTrees mengikuti Clean Architecture, SOLID, DRY, dan KISS:

**Separation of concerns** — clear separation of concerns and single-responsibility modules. · Pemisahan tanggung jawab yang jelas.<br/>
**Meaningful naming** — no magic numbers; no unexplained complexity. · Penamaan bermakna; tanpa magic number.<br/>
**Explicit error handling** — handle errors explicitly; log usefully without leaking secrets. · Tangani error secara eksplisit; log tanpa membocorkan rahasia.<br/>
**Performance & security** — consider both from the start. · Pertimbangkan performa & keamanan sejak awal.

## 6. Reporting security issues · Melaporkan isu keamanan

**Do not** open a public issue for vulnerabilities. Follow [SECURITY.md](./SECURITY.md).<br/>
**Jangan** membuka issue publik untuk kerentanan. Ikuti [SECURITY.md](./SECURITY.md).

---

*By contributing, you agree that your contributions will be licensed under the repository's license. · Dengan berkontribusi, Anda setuju kontribusi Anda dilisensikan sesuai lisensi repositori terkait.*
