# suricata-yaml

my customize surricata yaml config file

<code>wget https://raw.githubusercontent.com/gellanyhassan0/suricata-yaml/main/suricata.yaml -O suricata.yaml &&</code><br>
<code>cat suricata.yaml > /etc/suricata/suricata.yaml</code><br>

#for windows<br>
#https://forum.suricata.io/t/how-to-configure-suricata-ids-in-ips-mode-in-windows-server-2019/1648/22

<code>cd C:\Program Files\Suricata</code><br>
<code>suricata -c suricata.yaml -l ./log -knone -i ip</code><br>
