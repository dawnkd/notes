Latest Go release: https://go.dev/dl/
Install go:
```bash
wget https://dl.google.com/go/gox.xx.x.linux-amd64.tar.gz
sudo tar -xvf gox.xx.xlinux-amd64.tar.gz
sudo mv go /usr/local
```
Add environment vairables to `~/.bashrc`:
```bash
export GOROOT=/usr/local/go
export GOPATH=$HOME/go
export PATH=$GOPATH/bin:$GOROOT/bin:$PATH
```
Reload shell or `source ~/.bashrc`
Check Go version:
```bash
go version
```


`