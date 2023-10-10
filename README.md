# tech-hostcheck
CX-780 - Hostcheck utility for Customer Service

To use this, add the following to your .bashrc fie.

alias hostcheck="/bin/bash <(curl -s https://raw.githubusercontent.com/cPanelPeter/tech-hostcheck/main/hostcheck) "

Restart shell (or type: source ~/.bashrc)

Then you can run: 

hostcheck domainname.tld
or
hostcheck ip.ad.dre.ss


