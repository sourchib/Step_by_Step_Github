# Step_by_Step_Github
Step pengunaan github.

1.Download dan Install Git
2.Buat Akun  Github
3.Klik profile paling pojok kanan lalu plih your repositories
lalu klik new 
4.Buka Project lalu klik kanan projetc tersebut kemudian pilih git bash here   

5.ketik git config --global user.name  " ..." ( user name akun github anda )
6.ketik git config --global user.email   " .... " (email akun github anda)
7.ketik git init
8.git status
9.git add . atau git add
10.git commit -m "P"  (yang  didalam tanda kutip ini di isi terserah anda)
11.git remote add origin  https: .........
12.git push origin master.

Jika git push origin master gagal coba cari berikut ini :

git init
git remote -v (for checking current repository)
git add -A(add all files)
git commit -m "Nama Terserah"
git pull --rebase origin master
git push origin master
