Ślůnski git
===========

Dodej trocha wůnglu do swojygo gita!
------------------------------------

Zainspirowany [podlaskim gitem](https://github.com/maciejkorsan/podlaskigit) postanowiłem utworzyć śląską wersję git aliasów.

Aby z nich skorzystać, jedyne co musisz zrobić to dodać poniższe linijki do pliku `~/.gitconfig`.


```
[alias]
        szrajbnij = commit
        haja = blame
        ftoryciul = blame
        inkszy = checkout
        kamerlik = stash
        tasza = stash
        upa = stash pop
        nazot = revert
        gichnij = push
        ciulnij = push -f
        abszlag = merge --abort
        niy = merge --abort
        narychtuj = init
        tukej = clone
        dej = clone
        asta = branch
        loboc = show
        glancuj = commit --amend
        pierona = !git reset HEAD~1 --mixed
        nahasiok = reset HEAD --hard
        geszichta = log
        gyszichta = log
        gorolski = remote
        rajch = remote -v
        sztof = diff
        szychta = !git add -A && git commit -av
        # wydupc stare asty / delete merged
        ordnung = "!git branch --merged | grep -v '\\*' | xargs -n 1 git branch -d; git remote -v update -p"
        naszteluj = config
```
