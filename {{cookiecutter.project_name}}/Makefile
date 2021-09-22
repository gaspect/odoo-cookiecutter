run:
	@ docker stack deploy -c docker-stack.yml odoo

show:
	@ docker stack services odoo

stop:
	@ docker stack rm odoo

rm:
	@ docker volume rm odoo_data | true
	@ docker volume rm odoo_filestore | true

logs:
	@ docker service logs -f odoo_odoo
