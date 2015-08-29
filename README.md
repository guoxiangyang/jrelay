# jrelay

```text

jrelay [options] <actionA> <targetA> <hostA> <portA> <actionB> <targetB> <hostB> <portB>
  action = accept   : valid target = relay | client
           connect  : valid target = relay | server

  target = relay    : other side is a relay
           client   : accept client connection request
           server   : server to connect

  options for working mode :
      -t --tcp                        : work on tcp mode (default)
      -u --udp                        : work on udp mode (not implmentation yet)

  options for connection parameters :
      -S --package-size=SIZE (KB)     : max package size in KB  <= 64
      -c --max-connection=N           : max clients for accept client session
      -T --max-idle-time=TIME(S)      : idle time for client connection

  options for infomation :
      -d --debug                      : print out debug info
      -v --version                    : print version info
      -h --help                       : print this screen
```
