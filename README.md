Generate a Self-Signed SSL Certificate

    openssl req -x509 -nodes -days 365 -newkey rsa:2048 \
    -keyout certs/nginx-selfsigned.key \
    -out certs/nginx-selfsigned.crt

Certificate location 

    Private key: cp /etc/ssl/private/nginx-selfsigned.key /root/data/https/nginx-http-html/nginx-https-html/nginx/certs
    Certificate: cp /etc/ssl/certs/nginx-selfsigned.crt /root/data/https/nginx-http-html/nginx-https-html/nginx/certs
