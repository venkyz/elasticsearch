Sensu is a wellknown monitoring setup, which is widely used over platforms. I too had issues where, no log analysis was possible. So on working with this, the best way is to send it over ELK if you have it. 

This is a simple sensu handler that will help you to ship sensu events to Logstash setup.
Here what we have tried is to send it to a remote  ELK setup over filebeat and get this done.

This is done over filebeat setup and used filebeat input as udp 
