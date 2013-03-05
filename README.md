config
======

personal config backup

#git
    cd ~/.ssh
    ssh-keygen -t rsa -C "your_email@example.com"
    ##copy ~/.ssh/id_rsa.pub to github.com
    sudo apt-get install xclip
    xclip -sel clip < ~/.ssh/id_rsa.pub
    
#nginx(apt-get install nginx)
    sudo sh -c 'echo "autoindex on;" > /etc/nginx/conf.d/autoindex.conf'
    sudo ln -s ~/workspace /usr/share/nginx/www/workspace
    sudo nginx -s reload

#nginx(./configure)
    sudo ln -s ~/workspace /usr/local/nginx/html/workspace
    wget https://raw.github.com/seavers/config/master/nginx.conf -o /usr/local/nginx/conf/nginx.conf    

#apache.conf
    wget https://raw.github.com/seavers/config/master/apache2.conf -o /etc/apache2/apache2.conf

