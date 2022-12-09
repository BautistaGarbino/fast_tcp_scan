# fastTCPScan
This tool consists of a scanner that allows you to quickly and accurately detect the TCP ports that a machine has open.

How is the tool used?
The first thing once we have the fastTCPScan.go script, will be to compile it. We can do this in the following way:

┌─[✗]─[root@parrot]─[/home/z00m/Desktop]
└──╼ #cd /usr/bin/

┌─[root@parrot]─[/usr/bin]
└──╼ #go build -ldflags "-s -w" fastTCPScan.go 

┌─[root@parrot]─[/usr/bin]
└──╼ #upx brute fastTCPScan
