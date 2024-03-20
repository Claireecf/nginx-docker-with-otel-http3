# nginx-dokcer-with-otel-http3

Please build your docker using the command:

docker build -t my-nginx-image -f Dockerfile-nginx . 

and please remember to change the docker_exporter address to your otel collector address/jaeger address in the nginx.conf file.


Thanks for the resource from https://github.com/nginxinc/nginx-otel/issues/30. The official Nginx docker already supports otel module.
