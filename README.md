

## Running `polkadot` node

`docker-compose up`

Run single node dev network with docker

    docker run --rm -it -p 9944:9944 parity/polkadot:latest --dev

and sidecar connected to the node 

    docker run --rm -it --read-only -p 8080:8080 parity/substrate-api-sidecar:latest

Open <http://localhost:8080/> in browser to check JSON description of API

-----

https://github.com/paritytech/polkadot  
https://github.com/paritytech/polkadot/blob/master/doc/docker.md

    docker pull docker.io/parity/polkadot:latest

    docker run --rm -it parity/polkadot:latest --version
    
    docker run --rm -it parity/polkadot:latest --dev
    
    docker run --rm -it polkadot --version


https://github.com/paritytech/substrate-api-sidecar 

Releases: https://hub.docker.com/r/parity/substrate-api-sidecar/tags

    docker pull docker.io/parity/substrate-api-sidecar:latest

    docker run --rm -it --read-only -p 8080:8080 substrate-api-sidecar
    docker run --rm -it --read-only -p 8080:8080 parity/substrate-api-sidecar:latest

https://github.com/paritytech/substrate-api-sidecar/issues/667
[Question] polkadot node version compatibility #667


