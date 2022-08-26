# Hibernate-Demo
Hibernate-ORM Demo Project With H2 Database and JBoss EAP 

# Build Project
~~~
mvn clean install
~~~

# Deploy in EAP 7.x
1. Strat the JBoss EAP
2. Connect to cli:
~~~
./jboss-cli.sh -c
~~~
3. Then deploy the war (the war file can be found under /target folder) the  file into JBoss EAP using below cli command:
~~~
deploy /path/to/xxxxxx.war
~~~
