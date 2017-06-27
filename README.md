# git-repo-script
Fork/mirror of the main script interfacing to google's repo repository management copied from: https://storage.googleapis.com/git-repo-downloads/repo

The best way to use this file is to fetch is using wget: 
```Shell
wget https://raw.githubusercontent.com/spgreene/git-repo-script/master/repo
chmod a+x repo
```

Or curl:
```Shell
curl https://raw.githubusercontent.com/spgreene/git-repo-script/master/repo > repo
chmod a+x repo
```

and put the file somewhere it can be referenced.  Recommended places are:
* *~/bin/*
* */usr/bin*
* project root (the root directory of the project using repo)
