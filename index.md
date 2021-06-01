<p align="center">
  <body>   
    <img src="post.gif" width="1000" height="600">
  </body>
</p>

# RemotePotato0
https://github.com/antonioCoco/RemotePotato0

<img src="https://github.com/antonioCoco/RemotePotato0/demo.gif">


# AVinfo
````
WMIC /Node:localhost /Namespace:\\root\SecurityCenter2 Path AntiVirusProduct Get displayName /Format:List



Get-CimInstance -Namespace root/SecurityCenter2 -ClassName AntiVirusProduct
````

# Reverse Proxy

#### https://github.com/ffay/lanproxy
###### https://github.com/ffay/lanproxy/releases

````
Lanproxy - это инструмент проникновения в интрасеть, который проксирует персональные компьютеры и серверы LAN в общедоступную сеть. Он поддерживает переадресацию трафика TCP и может поддерживать любой протокол верхнего уровня TCP (доступ к веб-сайтам интрасети, отладка локального платежного интерфейса, доступ по ssh, удаленный рабочий стол. ..). В настоящее время на рынке есть арахисовая оболочка, TeamView, GoToMyCloud и т. Д., Которые предоставляют аналогичные услуги, но для использования стороннего общедоступного сетевого сервера вы должны платить за стороннюю организацию, и эти услуги имеют различные ограничения. , из-за пакета данных он будет проходить через третье лицо, поэтому это также большая скрытая опасность для безопасности данных.
````
##### https://github.com/nodauf/Go-RouterSocks

# Steal pass|cookies

### https://github.com/LimerBoy/Adamantium-Thief

#### https://github.com/moonD4rk/HackBrowserData

### Windows
| Browser                             | Password | Cookie | Bookmark | History |
| :---------------------------------- | :------: | :----: | :------: | :-----: |
| Google Chrome |    ✅    |   ✅   |    ✅    |    ✅    |
| Google Chrome Beta |    ✅    |   ✅   |    ✅    |    ✅    |
| Chromium |    ✅    |    ✅    |    ✅    |    ✅    |
| Microsoft Edge |    ✅    |   ✅   |    ✅    |    ✅    |
| 360 Speed |    ✅    |   ✅   |    ✅    |    ✅    |
| QQ |    ✅    |   ✅   |    ✅    |    ✅    |
| Brave |    ✅    |   ✅   |    ✅    |    ✅    |
| Opera |    ✅    |    ✅    |    ✅    |    ✅    |
| OperaGX |    ✅    |    ✅    |    ✅    |    ✅    |
| Vivaldi |    ✅    |    ✅    |    ✅    |    ✅    |
| Firefox |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Beta |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Dev |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox ESR |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Nightly |    ✅    |   ✅   |    ✅    |    ✅    |
| Internet Explorer |    ❌    |   ❌   |    ❌    |    ❌    |


# LAN attack

#### https://github.com/lgandx/PCredz

This tool extracts Credit card numbers, NTLM(DCE-RPC, HTTP, SQL, LDAP, etc), Kerberos (AS-REQ Pre-Auth etype 23), HTTP Basic, SNMP, POP, SMTP, FTP, IMAP, etc from a pcap file or from a live interface.

````
# extract credentials from a pcap file
python3 ./Pcredz -f file-to-parse.pcap

# extract credentials from all pcap files in a folder
python3 ./Pcredz -d /tmp/pcap-directory-to-parse/

# extract credentials from a live packet capture on a network interface (need root privileges)
python3 ./Pcredz -i eth0 -v

````
