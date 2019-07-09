https://github.com/dockerfile/ubuntu/tree/master/root

https://stackoverflow.com/questions/47903079/how-to-install-packages-from-docker-compose






try:

docker-compose -f docker-compose-ubuntu.yml build
docker run -it custom-ubuntu_custom-ubuntu /bin/bash

or

docker-compose -f docker-compose-ubuntu.yml up




try:
docker-compose -f docker-compose-ubuntu.yml up
