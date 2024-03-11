# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GIT

# Membuat branch baru dengan nama Tugas-baru
git checkout -b Tugas-baru

# Menambahkan file text baru, misalnya Tugas-Baru.txt
touch Tugas-Baru.txt

# Edit file Tugas-Baru.txt
nano Tugas-Baru.txt
# Simpan perubahan dengan menekan Ctrl + O, lalu tekan Enter, dan keluar dengan menekan Ctrl + X.

# Tambahkan perubahan ke staging area dan lakukan commit
git add Tugas-Baru.txt
git commit -m "Menambahkan Tugas-Baru.txt"

# Kembali ke branch utama (main)
git checkout main

# Menggabungkan branch Tugas-baru ke dalam main
git merge Tugas-baru

# Sinkronisasi repo local ke repo remote di GitHub
git push origin main
