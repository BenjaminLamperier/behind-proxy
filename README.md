# Behind-proxy
Working Behind a Network Proxy -  Tips and Tricks

## Standard Windows Configuration

set http_proxy = http://proxyuser:proxypwd@proxy.server.com:8080  
set http_proxy = http://proxyuser:proxypwd@proxy.server.com:8080

## Git Proxy Configuration

### Set Proxy

git config --global http.proxy http://proxyuser:proxypwd@proxy.server.com:8080  
git config --global https.proxy https://proxyuser:proxypwd@proxy.server.com:8080

### Unset Proxy

git config --global --unset http.proxy  
git config --global --unset https.proxy

## Npm (Node Js)

npm config set proxy http://proxy.company.com:8080
npm config set https-proxy http://proxy.company.com:8080
