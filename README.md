# Payloads for some vulnerabilities

## [XSS](https://github.com/RockThisParty/Payloads/blob/master/XSS_payloads.txt)
## [SQL](https://github.com/RockThisParty/Payloads/blob/master/SQL_payloads.txt)
## [Command Injections for Linux](https://github.com/RockThisParty/Payloads/blob/master/Command_Injections(Linux).txt)
## [Command Injections for Windows](https://github.com/RockThisParty/Payloads/blob/master/Command_Injections(Windows).txt)

#TCP:


Port	 | Status	   | Service		  | TTL 			  | Information
-------- | ----------- | ---------------- | ---------------   | ---------------------	
22/tcp | open  |   ssh |           syn-ack ttl 48	|	#login root
443/tcp | open |    https |         syn-ack ttl 48	| 	#nginx/1.14.0 Ubuntu
445/tcp | filtered | microsoft-ds |  no-response |   
3000/tcp | open  |   ppp |           syn-ack ttl 48	 |	#grafana
7001/tcp | open  |   afs3-callback | syn-ack ttl 48	 |	#HTTP Authentication
7002/tcp | open  |   afs3-prserver | syn-ack ttl 48	 |	#HTTP Authentication
7003/tcp | open  |   afs3-vlserver | syn-ack ttl 48	 |	#HTTP Authentication
7004/tcp | open  |   afs3-kaserver | syn-ack ttl 48	 |	#HTTP Authentication
7005/tcp | open  |   afs3-volser  |  syn-ack ttl 48	 |	#HTTP Authentication
7006/tcp | open  |   afs3-errors  |  syn-ack ttl 48	 |	#HTTP Authentication
7007/tcp | open  |   afs3-bos    |   syn-ack ttl 48  |
7008/tcp | open  |   afs3-update  |  syn-ack ttl 48  |
7009/tcp | open  |   afs3-rmtsys  |  syn-ack ttl 48  |
7010/tcp | open  |   ups-onlinet  |  syn-ack ttl 48  |
7011/tcp | open  |   talon-disc   |  syn-ack ttl 48  |
7012/tcp | open  |   talon-engine | syn-ack ttl 48   |
7013/tcp | open  |   microtalon-dis | syn-ack ttl 48 |
7014/tcp | open  |   microtalon-com | syn-ack ttl 48 |
8000/tcp | open  |   http-alt   |    syn-ack ttl 48  |
8001/tcp | open  |   vcom-tunnel  |  syn-ack ttl 48	 |	#Log server
8002/tcp | open  |   teradataordbms | syn-ack ttl 48 |		#SIGEN
8003/tcp | open  |   mcreport   |    syn-ack ttl 48	 |	#Admin
