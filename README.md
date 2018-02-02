# check_containers_status
Check_MK local check to monitor docker containers' status. It monitors that all the containers are actually running and didn't exited or restarting.
This is a simple script meant to monitor single docker hosts (ie webhosting platform like [this one](https://github.com/evertramos/docker-compose-letsencrypt-nginx-proxy-companion)).

## Deployment

Copy the script in /usr/lib/check_mk_agent/local/ on your docker host and run a new inventory on
WATO.
