dockergen: /usr/local/bin/docker-gen -watch -notify "pkill -USR2 haproxy" /usr/src/app/haproxy.tmpl /haproxy.cfg
haproxy: /docker-entrypoint.sh haproxy -f /haproxy.cfg
