This Magento 2 docker setup is based on: https://github.com/markshust/docker-magento. You can find the instruction on setting up a new Magento 2 website as well as dockerizing an existing Magento 2 site here.

These customizations have been added:

* Decrease the memory consumption of the PHP-FPM container, from ~300MB to just ~20MB
* Make it work with nginx-proxy: https://git.dtn.com.vn/dtn/nginx-proxy, so we can setup multiple Docker based websites on the same host.