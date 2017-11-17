# eos-tutorial
A simple way to get eos dawn tutorial running

## Run EOS
```
sudo rm -rf /data/store/eos # options 
sudo mkdir -p /data/store/eos
sudo chown -R $(whoami) /data/store/eos

rm -rf /data/store/eos/* && docker-compose -f Docker/docker-compose.yml up
```

## Join the container
```
docker exec -ti docker_eos_1 bash
```
