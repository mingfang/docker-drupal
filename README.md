docker-drupal
=============

Full stack consisting of Varnish, Apache, Drupal, Memcache, and MySql.

Requirement
Vagrant

Install Docker
```bash
git clone https://github.com/dotcloud/docker.git
cd docker
```

Enable Port Forwarding
```bash
export FORWARD_DOCKER_PORTS=1
```

Start VM
```bash
vagrant up
vagrant ssh
sudo -i
```

