This is a deployment for ELK stack.


Info coming soon. This is pretty much ready to.

A user may need to be generated through curl request.
You can deploy without authentication for easier deployment. Just remove the security and authentication references in files. 

Install filebeat on endpoints you want to injest logs from.
Point to logstash container. 
logstash then pushes logs to elasticsearch

Go to the Discover section in Kibana.
Create a index pattern

Stack Management is used to manage things. Go there to for Index Patters, Index Management, Users, etc...

If you add in an endpoint that has new fields. Go to index patterns, click your index pattern, and click refresh fields list
