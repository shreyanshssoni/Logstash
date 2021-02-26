This is the Demo of the Logstash to collect and analyze the Logs from (.log) files and applu some filteration and stored into elasticsearch.
In Logstash we have total 3 Parts
      **1)Input
     2)Output
     3)Filter**
    
We can add input as a .log file or get logs from Filebeats(ELK Stack) and analyze logs
In filter we can apply different types of filters as per need.**(https://www.elastic.co/guide/en/logstash/current/filter-plugins.html)**
In output we can define port of elasticsearch running and define custom index name.



NOTE:
 Please change your filepath before run logstash in your local system.
 
 
 **Steps:
 (1)Make apache.conf file in anywhere in your local system or directory of logstash
 (2)Give path of input log files
 (3)In final step apply given command: ./logstash -f /filepath of apache.conf file/apache.conf**
