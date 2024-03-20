# nginx-dokcer-with-otel-http3

Please build your own docker using command:

docker build -t my-nginx-image -f Dockerfile-nginx . 

and remeber to change docker_exporter address to your own otel collector address/jaeger address in nginx.conf.
