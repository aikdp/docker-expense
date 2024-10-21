#DOCKER EXPENSE PROJECT: Frontend Application code
FROM nginx
COPY code /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d
COPY nginx.conf /etc/nginx/nginx.conf
COPY expense.conf /etc/nginx/default.d/expense.conf




#DOCKER EXPENSE PROJECT: Frontend Application code:(Siva Code--->he took different nginx.conf file(copied from 78s batch)) 
# FROM nginx
# COPY code /usr/share/nginx/html
# RUN rm -rf /etc/nginx/nginx.conf
# RUN rm -rf /etc/nginx/conf.d
# COPY nginx.conf /etc/nginx/nginx.conf