# storm-example

You can build this project with mvn clean install and then execute the it with java -jar storm-app-0.0.1-SNAPSHOT.jar
from the target directory.

In my environment I see the following output:

log4j:WARN No appenders could be found for logger (org.apache.zookeeper.ZooKeeper).
log4j:WARN Please initialize the log4j system properly.
log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig for more info.
1

3

2

7

5

11

...

3471031

3471283

3471317

3471407


The process runs for 10 seconds and in that time we are able to observe 3.4 million numbers.
