# git-alias
Adding different aliases for reference here

-----------------------------------------
git config --global alias.t 'tag -l'
git config --global alias.stg show
git config --global alias.ct 'tag -a'
git config --global alias.pt 'push origin --tags'
git config --global alias.dtl 'tag -d'
git config --global alias.dtr 'push origin --delete'
git config --global alias.po 'push origin'
git config --global alias.a add
git config --global alias.cl clone
git config --global alias.co checkout
git config --global alias.cb 'checkout -b'
git config --global alias.br branch
git config --global alias.ci 'commit -a -m' // add all with commit message
git config --global alias.st 'status -sb'
git config --global alias.p push
git config --global alias.pl pull
git config --global alias.l 'log --oneline'
git config --global alias.last 'log -1 HEAD --stat'
git config --global alias.rv 'remote -v'
git config --global alias.d 'diff'
git config --global alias.dv 'difftool -t vimdiff -y'
git config --global alias.gl 'config --global -l'
git config --global alias.s '!git rev-list --all | xargs git grep -F'
git config --global alias.us 'reset HEAD --'
git config --global alias.cc 'rev-list --count'
git config --global alias.clean 'gc --prune=now --aggressive'
git config --global alias.aa 'config --global'
git config --global alias.ra 'config --global --unset'
git config --global alias.u 'config --global user.name'
git config --global alias.e 'config --global user.email'
git config --global help.autocorrect 20
