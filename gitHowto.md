git init .

git add

git add --all

git commit -m " initial comments "

git remote add origin https://github.com/dariushazimi/vim.git

git push -u origin master

git push -f origin master

If you prefer working with the command line
, you can also install a native Git shell, 
such as Git for Windows. With Git for Windows, 
running the following in the command line will store your credentials:


git config --global credential.helper wincred
"remove the ^M character from vim file
git config --global core.autocrlf input
