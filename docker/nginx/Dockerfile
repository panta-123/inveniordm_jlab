FROM nginx
COPY nginx.conf /etc/nginx/nginx.conf
COPY conf.d/* /etc/nginx/conf.d/
COPY hostkey.pem /etc/ssl/private/hostkey.pem
COPY hostcert.pem /etc/ssl/certs/hostcert.pem
COPY ca.pem   /etc/grid-security/certificates/5fca1cb1.0
