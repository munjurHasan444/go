# go
#how to install go in kali 2021

$ sudo apt update && sudo apt full-upgrade -y
$ wget https://golang.org/dl/go1.13.6.linux-amd64.tar.gz
$ sudo tar -C /usr/local -xzf go1.13.6.linux-amd64.tar.gz
$ echo "export PATH=$PATH:/usr/local/go/bin"  >> ~/.profile
$ echo "export GOPATH=~/.go" >> ~/.profile
$ source ~/.profile
$ go version
