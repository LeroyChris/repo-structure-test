# Branch Guide - StudyFlow

## 1. Branch Utama
### main
Branch `main` berisi versi final/stabil yang siap ditampilkan ke dosen atau dipakai untuk deployment.
Aturan:
- Tidak boleh direct push.
- Hanya menerima merge dari `development`.
- Harus selalu dalam keadaan stabil.
### development
Branch `development` adalah tempat integrasi fitur harian.
Aturan:
- Menjadi base untuk semua branch fitur.
- Menjadi target Pull Request dari branch `feat/*`, `fix/*`, `style/*`, dan `docs/*`.
- Harus bisa dijalankan lokal setelah setiap merge.

## 2. Branch Fitur
Format:
```txt
type/nama-pekerjaan
```
Contoh:
```txt
feat/landing-page
feat/flashcard-page
feat/pomodoro-page
feat/task-page
docs/project-documentation
fix/navbar-link
style/flashcard-layout
```
## 3. Jenis Branch
| Jenis | Fungsi | Contoh |
|---|---|---|
| feat | Membuat fitur baru | feat/flashcard-page |
| fix | Memperbaiki bug | fix/navbar-link |
| style | Perubahan tampilan | style/pomodoro-layout |
| docs | Dokumentasi | docs/update-readme |
| chore | Setup teknis | chore/setup-folder-structure |

## 4. Larangan Nama Branch
Hindari nama seperti:
```txt
roy-branch
coba
final
update
revisi
branch-baru