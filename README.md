# Step_by_Step_Github
Step pengunaan github.

  
  - Download dan Install Git
  - Buat Akun  Github
  - Klik profile paling pojok kanan lalu plih your repositories
  - lalu klik new 
  - Buka Project lalu klik kanan projetc tersebut kemudian pilih git bash here   
  
  - ketik git config --global user.name  " ..." ( user name akun github anda )
  - ketik git config --global user.email   " .... " (email akun github anda) 
  - ketik git init
  - git status
  - git add . atau git add
  - git commit -m "P"  (yang  didalam tanda kutip ini di isi terserah anda)
  - git remote add origin  https: .........
  - git push origin master.

Jika git push origin master gagal coba cari berikut ini :
  - git init
  - git remote -v (for checking current repository
  - git add -A(add all files)
  - git commit -m "Nama Terserah"
  - git pull --rebase origin master
  - git push origin master
