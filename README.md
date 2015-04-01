# i2g-repo-manifests
This project is for integration ImpalaToGo (http://impala2go.info) with all required dependencies using google's repo tool.
This make integration more simple but affects the workflow. Use with care.
##To install Repo:

Make sure you have a bin/ directory in your home directory and that it is included in your path:
```
    $ mkdir ~/bin
    $ PATH=~/bin:$PATH
```
Download the Repo tool and ensure that it is executable:
```
    $ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    $ chmod a+x ~/bin/repo
```
Google's description available here: http://source.android.com/source/downloading.html#installing-repo


##To use this project please run:
```
$ mkdir ImpalaToGo-repo
$ cd ImpalaToGo-repo
$ repo init -u https://github.com/ImpalaToGo/i2g-repo-manifests.git -m default.xml
$ repo sync
```

Now you have all related source code in the structure as we maintaining it.
Pay attention that this project is for our convinience and may change according to ImpalaToGo needs
