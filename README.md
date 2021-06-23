# go
#how to install go in kali 2021<br/>

$ sudo apt update && sudo apt full-upgrade -y <br/>
$ wget https://golang.org/dl/go1.13.6.linux-amd64.tar.gz<br/>
$ sudo tar -C /usr/local -xzf go1.13.6.linux-amd64.tar.gz<br/>
$ echo "export PATH=$PATH:/usr/local/go/bin"  >> ~/.profile<br/>
$ echo "export GOPATH=~/.go" >> ~/.profile<br/>
$ source ~/.profile<br/>
$ go version<br/>
