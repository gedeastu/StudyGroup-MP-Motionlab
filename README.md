**Version Control** adalah sistem yang
mengelola perubahan terhadap kode
atau dokumen. VCS memungkinkan tim
atau individu untuk melacak setiap versi
dari perubahan yang dibuat, sehingga
memudahkan untuk kembali ke versi
sebelumnya jika diperlukan.

**Git** adalah salah satu Version Control terpopuler
di dunia pengembangan perangkat lunak. Git
memungkinkan developer untuk mencatat dan
mengelola perubahan kode, baik secara individu
maupun kolaboratif. Hal ini membuat Git sangat
berguna dalam proyek kolaboratif karena
fleksibilitasnya dalam mengelola branch kode
secara paralel.

**GitHub** adalah platform berbasis web yang menggunakan Git sebagai
basisnya. GitHub memfasilitasi kolaborasi tim dalam mengelola dan
membagikan kode, serta menyediakan fitur-fitur seperti issue tracking,
project board, dan sistem code review untuk meningkatkan produktivitas
pengembangan.

**Fitur**, Fitur-fitur penting di Git:
- **Commit**: Menyimpan perubahan sebagai snapshot dari kode pada
  waktu tertentu.
- **Branching**: Membuat cabang kode untuk mengembangkan fitur
  baru tanpa mengganggu kode utama.
- **Merging**: Menggabungkan perubahan dari branch berbeda ke
  dalam branch utama.
- **Revert**: Mengembalikan perubahan yang telah dibuat.
- **Stash**: Menyimpan perubahan sementara tanpa melakukan commit.

**Alur kerja Git** mengatur bagaimana proyek dikembangkan
menggunakan cabang (branch).
Jenis-jenis alur kerja yang umum digunakan antara lain:
- **Centralized workflow**: Semua developer bekerja pada satu branch,
  biasanya main.
- **Feature branch workflow**: Setiap fitur memiliki branch sendiri untuk
  meminimalkan risiko konflik.
- **Gitflow**: Alur kerja yang lebih terstruktur dengan branch khusus untuk
  pengembangan, pengujian, dan produksi.

**Perintah-perintah dasar Git:**
- **git init**: Menginisialisasi repositori baru.
- **git status**: Memeriksa perubahan yang terjadi.
- **git add**: Menambahkan perubahan ke staging area.
- **git commit**: Menyimpan perubahan sebagai satu versi.
- **git push**: Mengunggah perubahan ke repositori jarak jauh (misalnya
  GitHub).
- **git pull**: Mengambil pembaruan dari repositori jarak jauh.
- **git reset**: Mengembalikan ke commit tertentu, umumnya digunakan
  untuk "undo".

**Best Practices**
Lakukan commit secara teratur dan jelas.
Hindari langsung melakukan commit ke branch utama
(misalnya main atau master).
Selalu lakukan pembaruan pada branch sebelum melakukan
merge untuk menghindari konflik.
Gunakan .gitignore untuk mengabaikan file yang tidak perlu
diunggah ke repositori.
