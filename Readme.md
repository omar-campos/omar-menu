# instalador Scriptssh 
```
apt-get update -y && \
apt-get upgrade -y && \
wget -qO Plus https://raw.githubusercontent.com/omar-campos/omar-menu/main/Plus && \
chmod +x Plus && \
./Plus
```

# Definir/Alterar senha root
```
bash <(wget -qO- https://raw.githubusercontent.com/omar-campos/omar-menu/main/senharoot.ssh)
```
