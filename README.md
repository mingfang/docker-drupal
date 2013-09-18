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

Get My Dockerfile
```bash
git clone https://github.com/mingfang/docker-drupal.git
cd docker-drupal
```

Build
```bash
docker build -t="drupal" .
```

Run
```bash
docker run -p 49800:80 -p 49801:6081 drupal
```

Point your browser to http://localhost:49801

