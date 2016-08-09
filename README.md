# nagios-rabbitmq-plugin
Simple php utility script for monitoring rabbitmq  using nagios.
Author: Kaburu 
Email : mbaya at kelvin dot gmail dot com
Installation 
==================================================================
1.  Download the script into your nagios plugin directory ie: /usr/lib64/nagios/plugins/

2.  Add the command into your nrpe.cnf file ie: /etc/nagios/nrpe.cnf // command[check_mq]=/usr/lib64/nagios/plugins/rabbit host=127.0.0.1 port=15672 username=guest password=guest

3.  Add the new command to your nagios server command.cnf file

4. Create the services on client.cnf from your nagios server 


====================================================================
a. You might need to change the processor to point the right php on your server

b. It is very basic, feel free to modify it to fit your needs


