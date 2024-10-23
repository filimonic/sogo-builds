```
# Debian 12
mkdir --parent /usr/local/sogo-debs/debian
tar -xzvf sogo-deb.tar.gz -C /usr/local/sogo-debs/debian
echo "deb [trusted=yes] file:/usr/local/sogo-debs debian/ " >> /etc/apt/sources.list
apt update
apt install sogo
apt install sope4.9-gdl1-postgresql
```