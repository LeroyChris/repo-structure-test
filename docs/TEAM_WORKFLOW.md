# Team Workflow - StudyFlow
Dokumen ini menjelaskan cara kerja anggota tim saat mengerjakan repository StudyFlow.

## 1. Aturan Utama
- Jangan push langsung ke `main`.
- Jangan push langsung ke `development`, kecuali repo owner memberi izin khusus.
- Semua fitur dikerjakan di branch masing-masing.
- Semua perubahan masuk melalui Pull Request.
- Pull Request harus diarahkan ke `development`.
- Minimal satu anggota lain membaca perubahan sebelum merge.

## 2. Alur Kerja Harian
### Ambil update terbaru
```bash
git switch development
git pull origin development
```
### Masuk ke branch kerja
```bash
git switch feat/flashcard-page
```
Jika branch belum ada:
```bash
git switch -c feat/flashcard-page
```
### Cek status file
```bash
git status
```
### Simpan perubahan
```bash
git add fitur/flashcard/index.html
git commit -m "feat: create flashcard page structure"
git push
```
### Buat Pull Request
- Base branch: `development`
- Compare branch: branch fitur kamu
- Isi deskripsi PR dengan jelas
- Tambahkan cara testing

## 3. Cara Testing Manual
Karena project masih memakai HTML biasa:
1. Buka VS Code.
2. Jalankan Live Server.
3. Buka halaman yang diubah.
4. Cek apakah tampilan dan tombol berjalan.
5. Cek tampilan mobile dengan resize browser.

## 4. Jika Ada Conflict
Jangan panik. Conflict biasanya terjadi karena dua orang mengedit bagian file yang sama.
Langkah aman:
```bash
git switch development
git pull origin development
git switch nama-branch-kamu
git merge development
```
Jika VS Code menampilkan conflict, pilih perubahan yang benar, simpan file, lalu:
```bash
git add .
git commit -m "fix: resolve merge conflict"
git push
```
## 5. Checklist Sebelum Pull Request
- [ ] Branch dibuat dari `development` terbaru.
- [ ] File yang berubah sesuai tugas.
- [ ] Commit message jelas.
- [ ] Halaman bisa dibuka di Live Server.
- [ ] Tidak ada file tidak penting yang ikut commit.
- [ ] PR menjelaskan perubahan dan cara testing.