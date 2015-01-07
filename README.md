# TwoAuth
2 way authuntication prototype in groovy .


##Notes:
* Grails version 2.4.2
* JDK 1.7
* Grails setup behind proxy
	* if behind NTLM proxy server , use this program [CNTLM](http://cntlm.sourceforge.net/)
	* CNTLM will provide an authntication proxy to NTLM proxy bridge
	* after setup , configure your grails ( in .grails/proxysettings.groovy)to refer to CNTLM proxy(local host)
