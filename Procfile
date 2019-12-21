dockergen: docker-gen -watch -notify "nginx -s reload" /app/nginx.tmpl /etc/nginx/conf.d/default.conf
dockergen: docker-gen -watch -notify "nginx -s reload" /app/nginx-stream.tmpl /etc/nginx/stream.conf.d/default.conf
nginx: nginx
