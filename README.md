# Read-Class-05

MIchael Rouspn 
Date:07/29/22

Reading Notes:

SMB (Server Message Block Protocol) was birth in 1983 by Barry Feigegbaum, originally established to turn DOS INT 21H local files access into a networked file system. The creation of SMB was established in 1980's, in its original state it was designed to run on top of NetBIOS over TCP/IP NBT using IP port 139 and UDP port 137 and 138. Sharing of access between hardware, file and data on the same network such as (printers, serial ports), also it was designed to carry out protocols  for authenticated inter-process communication. SMB was the means of communication for computers to talk to each other. 

Soon after Microsoft  started to leverage the SMB technology and integrated with the protocol using their LAN manager product. The merger allowed Microsoft to add additional capabilities in  Windows, to enhance SMB’s performance including support for symbolic links, hard links, larger file sizes, and an initial attempt to support direct connections over TCP port 445 without requiring NetBIOS as a transport (a largely experimental effort that required further refinement. (www.UpGuard.com/blog/smb-port)


Once Microsoft merged with the usage of SMB, they launched an effort to change the name of SMB in 1996. Once SMD, now Common Internet File System or (CIFS) came with a wealth of additional features. There were also more changes initiated by Micsoft to follow in 2000, there was a change over from using ports port 139 and UDP ports 137 and 138. to using Microsoft’s change to port 445..The change resulted in complication regarding performance issues around latency and multiple acknowledgements. 



## Things I want to know more about:

**How was Microsoft able to make such major changes to SMB? 
