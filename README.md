# jigdo

Forked version of jigdo with ClearOS changes applied

## Update usage
  Add __#kojibuild__ to commit message to automatically build

* git clone git+ssh://git@github.com/clearos/jigdo.git
* cd jigdo
* git checkout master
* git remote add upstream git://pkgs.fedoraproject.org/jigdo.git
* git pull upstream master
* git checkout clear7
* git merge --no-commit master
* git commit
