#geting nginx base image 

FROM nginx

#remove the existing default configration 

RUN rm /etc/nginx/conf.d/default.conf

#adding custom configration 

COPY default.conf /etc/nginx/conf.d
COPY ./index.html /usr/share/nginx/html/index.html