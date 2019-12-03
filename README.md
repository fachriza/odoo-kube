# Odoo-kube
Installation odoo with kubernetes and skaffold

```sh
$ clone this repo && cd odoo-kube
$ cp .env.example to .env
$ cp config/odoo.conf.example config/odoo.conf
$ git submodule init && git submodule update
$ kubectl create -f odoo-namespace.yaml
$ skaffold run -n odoo
```

to access odoo web `http://localhost:8069`
to access pgadmin `http://localhost:5555`


### Environment
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

