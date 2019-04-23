FROM nginx:1.15-alpine
MAINTAINER Dockup <support@getdockup.com>

COPY ./conf/default.conf /etc/nginx/conf.d/default.conf
COPY run-nginx /dockup/run-nginx

CMD /dockup/run-nginx
