# DIDM Renovate

Check de package.json voor alle `milieuinfo/webcomponent*` repositories op updates.
Meer info op https://renovatebot.com.

Run starten kan via:

```
docker run 
--volume ${PWD}/renovate.json:/usr/src/app/renovate.json 
-e RENOVATE_TOKEN=a7fc32cc474d5c80a5ec7f6d410e3a9383d3bfdc 
-e RENOVATE_CONFIG_FILE=/usr/src/app/renovate.json 
-e HTTP_PROXY=http://forwardproxy-pr-build.lb.cumuli.be:3128
-e HTTPS_PROXY=http://forwardproxy-pr-build.lb.cumuli.be:3128
renovate/renovate
```
