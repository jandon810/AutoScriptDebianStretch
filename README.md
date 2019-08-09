<h1 align="center"> VPN AutoScript Debian Stretch<img src="https://img.shields.io/badge/Version-3.9-blue.svg"></h1>

<p align="center">VPN AutoScript is made by JanDonCo. to minimize the time consumed and user involvement in setting up your VPS.</p>
<p align="center">[Donations]   GCASH: 09777150475   PAYPAL: marliecarl@gmail.com    FACEBOOK: Carl Marie Bayoneta</p>

<h3 align="center">Supported Linux Distribution</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Support-Debian%209-red.svg"></a>
  
</p>
<h3 align="center">Services</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Service-OpenSSH-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Webmin-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Dropbear-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Stunnel-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-OpenVPN-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Squid3-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Privoxy-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-GproxyPoC-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-ShadowsocksR-green.svg"></a>
 </p>
<h3 align="center">Commands</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Commands-menu-yellow.svg"></a>
 </p>

<h3 align="center">Installation (DigitalOcean, VULTR & MNX Solutions)</h3>

  ```html
wget https://raw.githubusercontent.com/jandon810/AutoScriptDebianStretch/master/DebianStretch && chmod +x DebianStretch && ./DebianStretch
  ```
<h3 align="center">Installation (N Version)</h3>

  ```html
wget https://raw.githubusercontent.com/jandon810/AutoScriptDebianStretch/master/DebianStretchN && chmod +x DebianStretchN && ./DebianStretchN
  ```

<h3 align="center">Installation (Dropbear Port 443)</h3>

  ```html
wget https://raw.githubusercontent.com/jandon810/AutoScriptDebianStretch/master/DebianStretchD && chmod +x DebianStretchD && ./DebianStretchD
  ```

<h3 align="center">Installation LEMP Stack Webserver</h3>

  ```html
wget https://raw.githubusercontent.com/jandon810/AutoScriptDebianStretch/master/LEMP7 && chmod +x LEMP7 && ./LEMP7
  ```


<h3 align="center">Additional Info</h3>
<p align="center">
Recommended OS: Debian 9 Stretch x64

<h3 align="center">Screenshots</h3>
<p align="center">
<img src="https://github.com/jandon810/AutoScriptDebianStretch/raw/master/Snapshots/1.png">
   </p>
  <p align="center">
  <img src="https://github.com/jandon810/AutoScriptDebianStretch/raw/master/Snapshots/2.png">
   </p>
  <p align="center">
  <img src="https://github.com/jandon810/AutoScriptDebianStretch/raw/master/Snapshots/3.png">
  </p>
  <p align="center">
  <img src="https://github.com/jandon810/AutoScriptDebianStretch/raw/master/Snapshots/4.png">
   </p>
   
   <h3 align="center">ShadowsocksR (Optional)</h3>
   <p align="left">
   <h3 align="left">Download (Android):</h3> https://github.com/shadowsocksr-backup/shadowsocksr-android/releases
   </p>
   <p align="left">
   <h3 align="left">Download (Windows):</h3> https://github.com/shadowsocksr-backup/shadowsocksr-csharp/releases
   </p>
   <p align="left">
   <h3 align="left">Configuration file path:</h3> /etc/shadowsocks.json 
   </p>
   <p align="left">
   <h3 align="left">Log file path:</h3> /var/log/shadowsocks.log 
   </p>
   <p align="left">   
   <h3 align="left">Installation directory:</h3> /usr/local/shadowsocks
   </p>
   <p align="left"> 
   <h3 align="left">Installation:</h3>
   </p>
   <p align="left">   
```html
wget --no-check-certificate https://raw.githubusercontent.com/jandon810/AutoScriptDebianStretch/master/ShadowR.sh
chmod +x ShadowR.sh
./ShadowR.sh 2>&1 | tee shadowsocksR.log
```
   </p>
   <p align="left">
   <h3 align="left">Commands:</h3>
   </p>
   <p align="left">
```html
Start: /etc/init.d/shadowsocks start 
Stop: /etc/init.d/shadowsocks stop 
Restart: /etc/init.d/shadowsocks restart 
Status: /etc/init.d/shadowsocks status
```
   </p>
   <p align="left">
   <h3 align="left">Multi Users; Config Setup:</h3>
   </p>
   <p align="left">
```html
{
"server":"0.0.0.0",
"server_ipv6": "[::]",
"local_address":"127.0.0.1",
"local_port":1080,
"port_password":{
    "8989":"password1",
    "8990":"password2",
    "8991":"password3"
},
"timeout":300,
"method":"aes-256-cfb",
"protocol": "origin",
"protocol_param": "",
"obfs": "plain",
"obfs_param": "",
"redirect": "",
"dns_ipv6": false,
"fast_open": false,
"workers": 1
}
```
   </p>
   <p align="left">
<h3 align="center">Facebook Support: https://www.facebook.com/marliecarl10</h3>
   </p>
