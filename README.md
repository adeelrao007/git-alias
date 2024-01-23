# git-alias
Adding different aliases for reference here

-----------------------------------------
git config --global alias.t 'tag -l'<br>
git config --global alias.stg show<br>
git config --global alias.ct 'tag -a'<br>
git config --global alias.pt 'push origin --tags'<br>
git config --global alias.dtl 'tag -d'<br>
git config --global alias.dtr 'push origin --delete'<br>
git config --global alias.po 'push origin'<br>
git config --global alias.a add<br>
git config --global alias.cl clone<br>
git config --global alias.co checkout<br>
git config --global alias.cb 'checkout -b'<br>
git config --global alias.br branch<br>
git config --global alias.ci 'commit -a -m' // add all with commit message<br>
git config --global alias.st 'status -sb'<br>
git config --global alias.p push<br>
git config --global alias.pl pull<br>
git config --global alias.l 'log --oneline'<br>
git config --global alias.last 'log -1 HEAD --stat'<br>
git config --global alias.rv 'remote -v'<br>
git config --global alias.d 'diff'<br>
git config --global alias.dv 'difftool -t vimdiff -y'<br>
git config --global alias.gl 'config --global -l'<br>
git config --global alias.s '!git rev-list --all | xargs git grep -F'<br>
git config --global alias.us 'reset HEAD --'<br>
git config --global alias.cc 'rev-list --count'<br>
git config --global alias.clean 'gc --prune=now --aggressive'<br>
git config --global alias.aa 'config --global'<br>
git config --global alias.ra 'config --global --unset'<br>
git config --global alias.u 'config --global user.name'<br>
git config --global alias.e 'config --global user.email'<br>
git config --global help.autocorrect 20
