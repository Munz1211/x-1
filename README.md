# X-MPC
     
### RECOMMENDATION OS
     * DEBIAN 10

## YOU CAN USE THIS TO GET ROOT AKSES
<pre></code>sudo su && wget https://raw.githubusercontent.com/anzclan/ovh-root/main/root && bash root</code></pre>

## PORT INFO
     - Open SSH                : 443, 80, 22        
     - Dropbear                : 443, 109, 143      
     - Dropbear Websocket      : 443, 109           
     - SSH Websocket SSL       : 443                
     - SSH Websocket           : 80                 
     - OpenVPN SSL             : 443                
     - OpenVPN Websocket SSL   : 443                
     - OpenVPN TCP             : 443, 1194          
     - OpenVPN UDP             : 2200               
     - Nginx Webserver         : 443, 80, 81        
     - Proxy Loadbalancer      : 443, 80            
     - DNS Server              : 443, 53,           
     - DNS Client              : 443, 88            
     - OpenVPN Websocket SSL   : 443                
     - XRAY DNS (SLOWDNS)      : 443, 53            
     - XRAY Vmess TLS          : 443                
     - XRAY Vmess gRPC         : 443                
     - XRAY Vmess None TLS     : 80                 
     - XRAY Vless TLS          : 443                
     - XRAY Vless gRPC         : 443                
     - XRAY Vless None TLS     : 80                 
     - Trojan gRPC             : 443                
     - Trojan WS               : 443                
     - Shadowsocks WS          : 443                
     - BadVPN 1                : 7100               
     - BadVPN 2                : 7200               
     - BadVPN 3                : 7300               
     - Proxy Squid             : 3128 & 8000
     
### INSTALATION
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade -y && apt install curl -y && apt install -y wget screen && wget https://raw.githubusercontent.com/bestmpc/x/main/install.sh && chmod +x install.sh && ./install.sh</code></pre>

## VERSION
V3.0 - 01/09/2023