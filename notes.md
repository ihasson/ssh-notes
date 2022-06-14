# execute firefox on local session from remote terminal
export DBUS_SESSION_BUS_ADDRESS=unix:path=/run/user/$UID/bus  
systemd-run --user firefox  


systemd-run --user steam WINDEBUG=+seh PROTON_LOG=1 steam://rungameid/32350 &>> out.txt  
# Above doesn't quite work. Runs Steam but either doesn't capture wine debug or doesn't get output I want.
