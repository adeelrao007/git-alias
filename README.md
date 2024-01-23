# git-alias
Adding different aliases for reference here

-----------------------------------------
git config --global alias.aa 'config --global'<br>
git config --global alias.ra 'config --global --unset'<br>
git config --global alias.u 'config --global user.name'<br>
git aa alias.e 'config --global user.email'<br>
git aa alias.t 'tag -l'<br>
git aa alias.stg show<br>
git aa alias.ct 'tag -a'<br>
git aa alias.pt 'push origin --tags'<br>
git aa alias.dtl 'tag -d'<br>
git aa alias.dtr 'push origin --delete'<br>
git aa alias.po 'push origin'<br>
git aa alias.a add<br>
git aa alias.al 'add .'<br>
git aa alias.cl clone<br>
git aa alias.co checkout<br>
git aa alias.cb 'checkout -b'<br>
git aa alias.br branch<br>
git aa alias.ci 'commit -a -m' // add all with commit message<br>
git aa alias.st 'status -sb'<br>
git aa alias.p push<br>
git aa alias.pl pull<br>
git aa alias.l 'log --oneline'<br>
git aa alias.last 'log -1 HEAD --stat'<br>
git aa alias.rv 'remote -v'<br>
git aa alias.d 'diff'<br>
git aa alias.dv 'difftool -t vimdiff -y'<br>
git aa alias.gl 'config --global -l'<br>
git aa alias.s '!git rev-list --all | xargs git grep -F'<br>
git aa alias.us 'reset HEAD --'<br>
git aa alias.cc 'rev-list --count'<br>
git aa alias.clean 'gc --prune=now --aggressive'<br>
git aa help.autocorrect 20<br>
git gl
