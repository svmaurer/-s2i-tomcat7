s2i-tomcat7

$ make
$ make test

$ docker tag s2i-tomcat7 <your registry>/s2i-tomcat7  
$ docker push <your registry>/s2i-tomcat7

$oc create -n openshift -f s2i-tomcat7-is.json
$oc create -n openshift -f s2i-tomcat7-template.json
