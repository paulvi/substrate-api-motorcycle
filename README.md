

https://github.com/paritytech/polkadot  
https://github.com/paritytech/polkadot/blob/master/doc/docker.md

    docker pull docker.io/parity/polkadot:latest

    docker run --rm -it parity/polkadot:latest --version


https://github.com/paritytech/substrate-api-sidecar 

Releases: https://hub.docker.com/r/parity/substrate-api-sidecar/tags

    docker pull docker.io/parity/substrate-api-sidecar:latest

    docker run --rm -it --read-only -p 8080:8080 substrate-api-sidecar

https://github.com/paritytech/substrate-api-sidecar/issues/667
[Question] polkadot node version compatibility #667


