# Network Penetration Testing

## Basic Linux Commands

> Print Working directory
	
`pwd`	

> Change Directory

`cd directory path`

> Return To Previous Directory

`cd ..`

> View Contents of A Directory

`ls`
`ls -la` - Displays hidden files

> Create a Directory

`mkdir <directory name>`

> Remove Directory

`rmdir <directory name>`

> Copy files

`cp <file name> <path to directory>/<file name>`

> Move files

`mv <file name> <pah to directory>/<file name>`

> Remove files

`rm <filename>`

> Create new file

`echo <file name>`

> Locate files

`locate <file name>`

> Update File System

`updatedb`

> Manual

`man`

- Usage:

`man ls`
`man cd`

> Change Mode

`chmod`

- Usage

`chmod 777 <file>` - Gives read, write & execute permissions

`chmod +x <file>` - Gives execute permissions

> Check System Logs

`cd /var/log`

> Common Network Commands

`ifconfig` - similar to `ipconfig` on Windows

> For *Wireless* Adapters

`iwconfig`

> Ping 

- Ping (latency is the technically more correct term) means the time 
  it takes for a small data set to be transmitted from your device to 
  a server on the Internet and back to your device again. ... 
  Note that ping refers to two-way latency (aka round-trip delay), 
  a value relevant for Internet usage.

Usage

`ping <ip addr>`


> arp

- Arp associates IP addresses with MAC addresses

Usage
`arp -a`

> Netstat

- This displays all ports that are open and what's connected/using them...

Usage

`netstat -ano`

`route`

> Check command history

`history`

> Check specific history for a given command

`history | grep <command>`
