FROM nginx
COPY ./dist/sample-angular-app/browser /usr/share/nginx/html
#Changing default config 
COPY ./nginx/default.conf  /etc/nginx/conf.d/default.conf
CMD ["nginx", "-g", "daemon off;"]
