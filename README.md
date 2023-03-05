# nginx-logging-proxy

This project is a combination of Nginx Proxy Manager and a normal Nginx instance. The second Nginx can be used as an intermediate to log all traffic including bodies in the JSON format. For that inside the [`nginx.conf`](proxy/nginx.conf#L40) the target needs to be configured. Additionally, [the file to log to](proxy/nginx.conf#L37) can be customized.

This project could be useful to reverse engineer protocols or other network communication through a reverse proxy.
