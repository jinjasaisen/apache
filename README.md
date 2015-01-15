# apache-config1

http://web-programmers-blog.com/server-side/apache2-403-forbidden/

apache 2.4 config ex1

# /etc/httpd/extra/httpd-vhosts.conf

<Directory / >
Options FollowSymLinks
AllowOverride None
</Directory>
<Directory /www/testSite>
Options Indexes FollowSymLinks MultiViews
AllowOverride All
Require all granted
</Directory>
