# Systemd Setup

https://community.hetzner.com/tutorials/docker-compose-as-systemd-service

* mkdir /etc/docker-compose

* mkdir /etc/docker-compose/$SERVICE

* cp docker-compose@.service to /etc/systemd/system/

* systemctl daemon-reload

* systemctl start docker-compose@$SERVICE

* systemctl enable docker-compose@$SERVICE
