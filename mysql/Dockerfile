FROM mysql:5.7
COPY dump.sql /home/

HEALTHCHECK CMD ["mysqladmin" ,"ping", "-h", "localhost"]