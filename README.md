# install-bookstack-docker

[Optional install-docker if Docker not install]

0. bash -c "$(wget -qLO - https://raw.githubusercontent.com/bigbeartechworld/big-bear-scripts/master/install-docker/run.sh)"

# install-bookstack

1. bash -c "$(wget -qLO - https://raw.githubusercontent.com/zafims/install-traccar/main/run.sh)"

2. mkdir docker-script/bookstack -p
3. cd docker-script/bookstack
4. wget https://raw.githubusercontent.com/zafims/install-bookstack-docker/main/docker-compose.yml
5. Change APP_URL=http://localhost:6875 to APP_URL=http://[ Public IP ]:6875
6. docker-compose up


---> Web Access: [IP Address]:6875 <---

admin@admin.com / password
