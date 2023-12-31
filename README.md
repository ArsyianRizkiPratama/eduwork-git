# eduwork-git

## Pendahuluan Git

### Deskripsi
  GIT adalah salah satu version control system yang diciptakan oleh Linus Torvalds
  GIT mencatat setiap perubahan file di code atau sourcode kita
  
### Manfaat
  Bisa menyimpan seluruh versi source code
  Berkolaborasi membangun sistem jadi mudah
  Bisa berkontribusi di proyek open source
  Memudahkan dalam tracking perubahan
  Memahami cara deploy modern
  Dsb

### Kapan dibutuhkan
  Saat ingin membangun sistem dengan berkolaborasi
  Membuat versi dari sistem
  Backup sour code
  Berkolaborasi dengan programmer dunia

## Fundamental Git

### Deskripsi
  Perintah perintah dasar yang sering dilakukan untuk mengoperasikan GIT

### Manfaat
  Terbiasa mengerjakan proyek dengan terdokumentasi
  Fleksibel dalam mengeksplorasi fitur
  Mempercepat dalam mengerjakan proyek terlebih jika proyek kolaborasi

### Todo
  Git init
  Git config
  Git status
  Git add
  Git commit
  Git clone
  Git remote
  Git push
  Git pull

###Kapan dibutuhkan
  Saat mengerjakan proyek

### Git init
  Digunakan untuk menginisialisasi repository
  Atau memberi tahu folder saat ini akan dijadikan repository
  Kita tidak bisa menggunakan git tanpa menginisialisasinya

### Git config
  Konfigurasi email dan username
  Biasanya disamakan dengan akun gitlab / github
  Config global untuk konfigurasi ke server
  Config local untuk konfigurasi local
  Untuk melihat semua konfigurasi yang ada di git bisa menggunakan perintah  git config --list 

### Git status
  Digunakan untuk mengetahui status file
  Status file secara umum ada 3. Untracked, staging area, modified
  
### Git add .
  Untuk memasukan file ke staging area

### Git commit
  Untuk mencatat perubahan yang dilakukan

### Git log
  Untuk melihat riwayat commit
  Tekan q untuk keluar dari log

### Git clone
  Digunakan untuk mengcopy repo dari server

### Git push
  Untuk mengirimkan commit ke server

### Git remote
  Semacam api untuk berinteraksi dari client dengan server

### Git pull
  Untuk mengambil commit dari server jika ada perubahan di server yang dibuat oleh branch lain


## Branch

### Deskripsi
  Cabang / copyan dari repo 
  
### Manfaat
  Parallel development
  Bisa digunakan untuk memanajemen pengembangan. Misal test branch, unstable branch, stable branch
  
### Kapan dibutuhkan
  Saat mengembangakan fitur baru

### Pembahasan branch
  Git branch: melihat semua branch (local)
  Git branch --all: melihat semua branch (public)
  Git branch nama_branch: membuat branch baru
  Git checkout nama_branch: untuk berpindah branch
  Git branch -d nama_branch: untuk menghapus branch
  Git merge nama_branch
  
### untuk menggabungkan commit dari 2 branch
  Relatif terhadap branch yang aktif saat ini
  Untuk melakukan merge harus dipastikan tidak ada file yang belum di commit

### Conflict
  Kondisi yang terjadi ketika merging 2 branch yang memiliki perubahan pada file yang sama
  Ketika conflict, kita tidak bisa melakukan commit
  Untuk melakukan commit, conflict harus diselesaikan dulu

## GUI

### Deskripsi
  Software berbasis GUI untuk memudahkan dalam mengoperasikan git

### Manfaat
  Mudah digunakan
  Solving conflict jadi lebih mudah
  Mempercepat kinerja

### Kapan dibutuhkan
  Setiap saat
