# SIEM
~~~
sudo apt-get update && sudo apt-get upgrade

downlod .deb file.
scp to ubuntu machine
dpkg -i .deb file ($ sudo dpkg -i splunk-8.2.1-ddff1c41e5cf-linux-2.6-amd64.deb)

cd /opt/splunk/bin
sudo ./splunk start
q
y

sudo ./splunk enable boot-start
systemctl enable splunk
systemctl start splunk
~~~

https://www.splunk.com/pdfs/technical-briefs/splunk-validated-architectures.pdf


Detailed video: https://youtu.be/EWq7N6kCwt0
