
Steps to reproduce:

- `convox start`
- `echo "i can change!" > anotherdir/hello`
- `echo "i can't change, i has a sad" > migrations/hello`


## Details

$ convox -v
client: 20161208160629
server: 20161123204337 (console.convox.com)

$ docker -v
Docker version 1.13.0-rc3, build 4d92237
