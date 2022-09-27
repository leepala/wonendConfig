# wonendConfig

# Create secret to save certificate
sudo kubectl create secret generic ssl-womend --from-file=/opt/cert/www.wonend.cn.pem --from-file=/opt/cert/www.wonend.cn.key 