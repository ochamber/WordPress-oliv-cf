cf-wordpress
============

CloudFoundry sample Wordpress install


### Configuring the CloudFoundry CLI
```
gem install cf
cf target api.run.pivotal.io
cf login [your-cloudfoundry-email]
```

### Pushing the sample app
```
git clone https://github.com/ochamber/WordPress-oliv-cf
cd Wordpress-oliv-cf
cf push
```
