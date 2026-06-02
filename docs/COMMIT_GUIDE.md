# Commit Guide - StudyFlow
Commit message adalah catatan perubahan kode. Commit yang jelas membantu tim melacak progress dan mencari sumber

## 1. Format Commit
```txt
type: deskripsi singkat
```
Contoh:
```bash
git commit -m "feat: create flashcard page structure"
```

## 2. Type yang Digunakan
| Type | Fungsi | Contoh |
|---|---|---|
| feat | Menambah fitur | feat: add flashcard flip interaction |
| fix | Memperbaiki bug | fix: fix broken feature link |
| style | Mengubah tampilan | style: style hero section with Tailwind |
| docs | Dokumentasi | docs: update team workflow |
| chore | Setup teknis | chore: initialize repository structure |
| refactor | Merapikan kode | refactor: simplify flashcard script |

## 3. Contoh Commit yang Baik
```bash
git commit -m "chore: initialize repository structure"
git commit -m "feat: create flashcard page structure"
git commit -m "style: style flashcard layout with Tailwind"
git commit -m "feat: add flashcard flip interaction"
git commit -m "docs: add project overview"
```

## 4. Commit yang Harus Dihindari
```bash
git commit -m "update"
git commit -m "fix"
git commit -m "coba"
git commit -m "final"
git commit -m "revisi lagi"
```

## 5. Prinsip Commit Kecil
Satu commit sebaiknya hanya berisi satu tujuan perubahan.
Contoh urutan untuk Flashcard:
1. `feat: create flashcard page structure`
2. `style: style flashcard layout with Tailwind`
3. `feat: add static flashcard content`
4. `feat: add flashcard flip interaction`
5. `feat: add next flashcard interaction`