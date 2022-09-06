FROM nginx
LABEL "Project"="vprofileapp"
LABEL "Author"="Alexander Kozyr"
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY vproapp.conf /etc/nginx/conf.d/vproapp.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]