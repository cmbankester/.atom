# .atom
My atom configs

To initialize a new Atom installation:
```bash
cd $HOME/.atom
git init
git remote add origin git@github.com:cmbankester/.atom.git
git checkout .gitignore
git reset --hard origin/master
# Alternatively:
# cd $HOME
# git clone git@github.com:cmbankester/.atom.git .atom.tmp
# mv .atom.tmp/.git .atom/.git
# rm -rf .atom.tmp
# cd .atom
# git checkout .gitignore
# git reset --hard origin/master
```

NB: the `git checkout .gitignore` step ensures that only the files specified in this repo are replaced, instead of removing everything else in the `.atom` directory
