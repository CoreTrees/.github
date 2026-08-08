# Governance · Tata Kelola

**EN** — A lightweight governance model that keeps CoreTrees consistent, secure, and easy to maintain.<br/>
**ID** — Model tata kelola ringan agar CoreTrees tetap konsisten, aman, dan mudah dipelihara.

## Roles · Peran

| Role · Peran | Responsibility · Tanggung jawab |
|---|---|
| **Maintainer** | Sets direction, reviews & merges PRs, manages releases and security. · Menentukan arah, meninjau & merge PR, mengelola rilis & keamanan. |
| **Contributor** | Opens issues and PRs following the guidelines. · Membuka issue & PR sesuai panduan. |

Currently CoreTrees is maintained primarily by **@Halfirzzha**. · Saat ini CoreTrees dikelola terutama oleh **@Halfirzzha**.

## Decision making · Pengambilan keputusan

**EN** — Changes are proposed via issues/PRs. The maintainer reviews for correctness, security, performance, and architectural fit before merging. Significant changes should be discussed in an issue first.<br/>
**ID** — Perubahan diusulkan melalui issue/PR. Maintainer meninjau kebenaran, keamanan, performa, dan kesesuaian arsitektur sebelum merge. Perubahan besar dibahas dulu di issue.

## Branching & releases · Branching & rilis

**Protected main** — `main` is always deployable and protected. · `main` selalu siap-rilis dan diproteksi.<br/>
**Short-lived branches** — work happens on `feat/…`, `fix/…` branches merged via PR. · Kerja di branch pendek lalu di-merge via PR.<br/>
**Semantic Versioning** — releases are tagged `MAJOR.MINOR.PATCH`. · Rilis diberi tag SemVer.

## Definition of Done · Definisi Selesai

A change is **done** only when · Sebuah perubahan dianggap **selesai** hanya bila:

**1.** It meets the requirement and passes logic validation. · Memenuhi kebutuhan & lolos validasi logika.<br/>
**2.** Tests pass and no known regressions are introduced. · Test lolos & tanpa regresi yang diketahui.<br/>
**3.** Errors are handled and observability is adequate. · Error tertangani & observabilitas memadai.<br/>
**4.** Docs are updated where needed. · Dokumentasi diperbarui bila perlu.<br/>
**5.** It is production-ready for the project's scope. · Siap produksi sesuai ruang lingkup.

*Compiling or running is **not** the same as done. · Berhasil dikompilasi/dijalankan **bukan** berarti selesai.*
