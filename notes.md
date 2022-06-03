# execute firefox on local session from remote terminal
export DBUS_SESSION_BUS_ADDRESS=unix:path=/run/user/$UID/bus  
systemd-run --user firefox  


systemd-run --user steam WINDEBUG=+seh steam://rungameid/32350 &>> out.txt  
