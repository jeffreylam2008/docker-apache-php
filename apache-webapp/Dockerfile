FROM httpd:2.4
COPY init.httpd.conf /usr/local/apache2/conf/init.httpd.conf
RUN echo "Include /usr/local/apache2/conf/init.httpd.conf" >> /usr/local/apache2/conf/httpd.conf
RUN chmod 775 -R /usr/local/apache2/htdocs/


