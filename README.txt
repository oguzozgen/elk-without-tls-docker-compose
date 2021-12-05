Run first for key generation

docker-compose -f docker-compose.setup.yml run --rm keystore

Then run 

docker-compose -f elk-no-tls-stack.yml -d