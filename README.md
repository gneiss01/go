# Go Hello World

## Installing on Ubuntu 14.04 LTS
> $ sudo apt-get install golang

**Set GOPATH and PATH**
## Setup workspace and set GOPATH
> $ mkdir -p ~/playground/go; echo "export GOPATH=$HOME/playground/go" >> ~/.bashrc
## Update path
> $ echo "export PATH=$PATH:$HOME/playground/go/bin:/usr/local/go/bin" >> ~/.bashrc
##Make directories inside workspace
> $ cd src/github.com/user/hello

**Compile**
> $ go install github.com/user/hello

**Run**
> $ $GOPATH/bin/hello