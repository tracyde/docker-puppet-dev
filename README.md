# docker puppet dev

This is a Dockerfile to set up a development environment for writing (https://docs.puppetlabs.com/puppet/ "Puppet") modules.

Build from docker file

```
git clone git@github.com:tracyde/docker-puppet-dev.git
cd docker-puppet-dev
docker build -t puppetdev .
```

You can also obtain it via:

```
docker pull tracyde/puppetdev
```

---
Instructions to run:

```
docker run -i -t --name="puppetdev" -v /*your_module_src_location*:/data puppetdev
```

