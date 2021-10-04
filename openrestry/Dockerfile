FROM openresty/openresty:1.19.9.1-1-alpine-fat
Add "https://raw.githubusercontent.com/LujianDuan/openrestry-proxy/main/openrestry/nginx.conf" /usr/local/openresty/nginx/conf/nginx.conf
RUN adduser -s /sbin/nologin -D -H nginx \
&& apk add npm \
&& apk add nodejs \
&& apk add git
