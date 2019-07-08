FROM nginx:alpine

RUN ln -snf /usr/share/zoneinfo/${TIMEZONE} /etc/localtime && echo ${TIMEZONE} > /etc/timezone

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80 443