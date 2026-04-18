FROM nginx:stable-alpine

LABEL Organization=Shiftro, Owner=Shravan

ENV PLATFORM=AWS \
    OWNER=Shravan

ADD ./index.html /usr/share/nginx/html

WORKDIR /app

EXPOSE 3000

CMD [ "nginx", "-g", "daemon off;" ]



