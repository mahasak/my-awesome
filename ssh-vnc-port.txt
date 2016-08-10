# Setup SSH forward port #

It is very convenient to forward port from local to remote ssh to use with vaious application e.g. VNC to remote server

`ssh -L 5901:127.0.0.1:5901 -N -f -l remote_user remote_ip -i /path/to/remote/key.pem`
