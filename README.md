Quick start aztec sequencer

1. Get this repo
```git clone https://github.com/LexPrime/aztec-docker
cd aztec-docker
```
2. Copy sample.env to .env and add your variables (L1 RPC, L1 consensus RPC, validator private key, validator public address)
```
cp sample.env .env
nano .env
```
3. Start sequencer
```
docker-compose -f sequencer.yml up -d
```
4. Or start sequencer with local sepolia rpc(+~500 GB disk size)
```
docker-compose -f sequencer+erigon.yml up -d
```
