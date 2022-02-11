# GUI-Linux-Ec2

sudo amazon-linux-extras install epel

arrow_right yum groupinstall "MATE Desktop"

arrow_right sudo yum install xrdp chromium

arrow_right systemctl enable --now xrdp

sudo bash -c 'echo PREFERRED=/usr/bin/mate-session > /etc/sysconfig/desktop'
