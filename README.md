## NetDisk -- a command line net disk interface
This is a tool for handy file storage. It uses the SDK provided by qiniu.

The net cloud relies on qiniu on the backend, it simply stores on and retrives files from the qiniu cloud. To use this, 

1. you should firstly get the qiniu cloud account;
2. put the information into the config file
3. use the command line

    * ./netdisk pull filename
    * ./netdisk push filename
    * ./netdisk ls
    * ...

input the `./netdisk` for help :) 

## TODO
support more commands like `ls`, `cat`, etc.
