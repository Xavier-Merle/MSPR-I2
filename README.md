# Packer command
`packer build -only=virtualbox-iso .\debian-kube-base.json`

# Vagrant command
`vagrant up`

# Helm command
```bash
helm install odoo bitnami/odoo --namespace cogip --create-namespace --set odooPassword=odoo123 --set postgresql.auth.postgresPassword=pgroot123 --set postgresql.auth.password=pguser123 --set postgresql.auth.database=bitnami_odoo --set postgresql.auth.username=bn_odoo
```
