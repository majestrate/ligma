# ligma

jellyfin server reimplementation that uses a real database (postgres).


## building

requirements:

* golang 1.20
* [openapi-generator-go](https://github.com/contiamo/openapi-generator-go)
* postgres >= 15


build:

    git clone https://github.com/majestrate/ligma
    cd ligma
    go generate ./...
    go get ./...
    go build ./cmd/ligmaD -o ligmaD.bin
