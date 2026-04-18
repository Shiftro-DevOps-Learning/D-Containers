FROM nginx:stable-alpine

LABEL Organization=Shiftro, Owner=Shravan

ENV PLATFORM=AWS \
    OWNER=Shravan

ADD ./index.html /usr/share/nginx/html
ADD ./default.conf /etc/nginx/conf.d/default.conf

WORKDIR /app

EXPOSE 3000

CMD [ "nginx", "-g", "daemon off;" ]



