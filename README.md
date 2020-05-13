# REDIS BOSH DEPLOYMENT 

Clone this repository https://github.com/bosh-rebels/redis-deployment

```bash
cd redis-deployment

bosh -d redis deploy manifest.yml -l ./vars.yml
```

NOTE : We assume bosh environment is been sourced before your run bosh deploy.