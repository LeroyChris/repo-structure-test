# StudyFlow - WCD03 Final Project
StudyFlow adalah platform belajar berbasis web yang membantu mahasiswa mengatur waktu belajar, menjaga fokus dengan teknologi

## Identitas Project
- Mata Kuliah: Web Client Development
- Kelas: WCD03
- Kelompok: 9
- Nama Website: StudyFlow
- Kategori: Productivity & Learning Tools
- Repository: [isi link repository]
- Figma: [isi link Figma]
- Deployment: [isi link deployment jika sudah ada]

## Latar Belakang
Mahasiswa dan pelajar sering menghadapi kesulitan dalam mengelola waktu belajar, menjaga fokus, dan mengulang mat

## Fitur Utama
1. Landing Page
- Memperkenalkan StudyFlow.
- Menampilkan masalah, solusi, dan fitur utama.
- Mengarahkan pengguna ke halaman fitur.
2. Time Management / Task
- Membuat daftar tugas belajar.
- Menandai tugas selesai.
- Menampilkan progress sederhana.
3. Pomodoro Timer + Lo-Fi
- Timer fokus dan istirahat.
- Tombol start, pause, dan reset.
- Area musik lo-fi sebagai pengembangan lanjutan.
4. Flash Card
- Kartu soal-jawab untuk active recall.
- Flip card untuk melihat jawaban.
- Next card untuk pindah kartu.
- Statistik sederhana sebagai pengembangan lanjutan.

## Teknologi
Current learning mode:
- HTML5
- Tailwind CSS via CDN
- JavaScript dasar
- Live Server untuk menjalankan halaman lokal
Future mode (opsional):
- React / Vite
- Tailwind CLI
- LocalStorage untuk menyimpan data
- Vercel / GitHub Pages untuk deployment
## Struktur Folder
```txt
studyflow-wcd03/
├── index.html
├── README.md
├── .gitignore
├── assets/
│
├── images/
│
├── icons/
│
└── audio/
├── fitur/
│
├── landing/
│
│
└── index.html
│
├── flashcard/
│
│
└── index.html
│
├── pomodoro/
│
│
└── index.html
│
└── task/
│
└── index.html
└── docs/
├── PROJECT_OVERVIEW.md
├── TEAM_WORKFLOW.md
├── BRANCH_GUIDE.md
├── COMMIT_GUIDE.md
├── TASK_DIVISION.md
└── MEETING_NOTES.md
```
## Cara Menjalankan Project
1. Clone repository:
```bash
git clone [isi link repository]
cd studyflow-wcd03
```
2. Buka project menggunakan VS Code.
3. Jalankan `index.html` memakai extension Live Server.
4. Buka folder `fitur/` untuk melihat halaman fitur masing-masing.
## Git Workflow Singkat
```bash
git switch development
git pull origin development
git switch -c feat/nama-fitur
```
Setelah mengubah file:
```bash
git status
git add .
git commit -m "feat: deskripsi perubahan"
git push -u origin feat/nama-fitur
```
Lalu buat Pull Request ke branch `development`.
## Status Project
Project ini masih dalam tahap prototype pembelajaran Web Client Development. Fokus saat ini adalah membuat struktur semantik html dan styling dengan tailwind CDN