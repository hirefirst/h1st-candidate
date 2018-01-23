Technical documentation
---


### Setup of git identity (in specific project only)

Download the `bash` script file Then follow the steps of:

```bash
wget https://raw.githubusercontent.com/hirefirst/tool-shed/master/bash/setup-git-local.sh
chmod +x ./setup-git-local.sh
./setup-git-local.sh
```

### Development machines

We use `debian` or `ubuntu` machines (`POSIX-compatible` among other things and `apt-get` on it).

### NodeJS v9.3.0

In order to install `node` and `nodejs` aliases please use following script:

```bash
wget https://raw.githubusercontent.com/hirefirst/tool-shed/master/bash/node-setup.sh
chmod +x ./node-setup.sh
./node-setup.sh
```
do not forget to add PATH 

```bash
if [ -d "$HOME/bin" ] ; then
    PATH="$HOME/.nvm/v9.3.0/bin:/usr/local/sbin:$HOME/bin:$PATH"
fi
```

### MongoDB 3.6

