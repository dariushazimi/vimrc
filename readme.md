
git remote add origin https://github.com/dariushazimi/vimrc.git
git push -u origin master

#Tips
Replace double quotes with single quotes in Vim

%s/\"\([^"]*\)\"/'\1'/g

Before: var string = "This is inside some quotes";
After: var string = 'This is inside some quotes';]
