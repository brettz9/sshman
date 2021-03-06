# SSH Man

A shell script to manage all your ssh config. works nicely with `fzf`.

![render1582444689643](https://user-images.githubusercontent.com/2182004/75106299-ef95c400-5655-11ea-9209-75c35707430f.gif)

## Dependences
 * [expect](https://en.wikipedia.org/wiki/Expect)
 * [fzf](https://github.com/junegunn/fzf) *optional*

## Usage

```
$ s help
```

## Install

### Install Dependences
1. Install `expect`
> See [here](http://www.linuxfromscratch.org/blfs/view/svn/general/expect.html)

2. Install `fzf` (optional)
> It's optional, but strongly suggested. If `fzf` is not installed, then you have to do sever selection by typing sequence number.
See [Installation](https://github.com/junegunn/fzf#installation)

### Install sshman

#### Using git

```
git clone --depth 1 https://github.com/Gcaufy/sshman.git ~/.sshman && \
ln -s /usr/local/bin/s ~/.sshman/sshman
```

#### Using curl
```
curl https://github.com/Gcaufy/sshman/archive/v1.0.1.tar.gz -o /tmp/sshman.tar.gz && \
makedir ~/.sshman && tar zxvf /tmp/sshman.tar.gz --strip-components=1 -C ~/.sshman/ && \
ln -s /usr/local/bin/s ~/.sshman/sshman
```
