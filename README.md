# aws
#Connect Phpmyadmin in EC2<br>
ssh -N -L 8888:127.0.0.1:80 -i KEYFILE bitnami@SERVER-IP
<br>
#Check space in disk<br>
df -hT /dev/xvda1<br>
#Get https one line
sudo /opt/bitnami/letsencrypt/scripts/generate-certificate.sh -m YOURMAIL -d YOURDOMAIN <br>
#remove banner<br>
sudo /opt/bitnami/apps/APPNAME/bnconfig --disable_banner 1


