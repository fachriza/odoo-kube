# Odoo-kube
Installation odoo with kubernetes and skaffold

* clone this repo && cd odoo-kube
* cp .env.example to .env
* cd config && cp odoo.conf.example odoo.conf
* git submodule init && git submodule update
* run `kubectl create -f odoo-namespace.yaml`
* run `skaffold run -n odoo`


### Environtment
* [Kubernetes] - Production-Grade Container Orchestration
* [Skaffold] - Local Kubernetes Development
* [Odoo] - Open Source ERP and CRM
* [PostgreSQL] - the world's most advanced open source database
* [pgAdmin] - PostgreSQL Tools

   
   [Skaffold]: <https://skaffold.dev/>
   [Kubernetes]: <https://kubernetes.io/>
   [Odoo]: <https://www.odoo.com/>
   [PostgreSQL]: <https://www.postgresql.org/>
   [pgAdmin]: <https://www.pgadmin.org/>

