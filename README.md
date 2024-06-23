# My-Java-Spark-Documentation
My Java Spark Documentation


How to install JAVA Spark in Intellij?
1) Download Intellij and Java JDK
2) Create new Maven project (I'd suggest you to use Spark Initializer website for this)
3) Add following dependencies in pom.xml
   ```<dependency>
  <groupId>org.apache.spark</groupId>
        <artifactId>spark-core_2.12</artifactId>
        <version>3.1.1</version>
    </dependency>
    <dependency>
        <groupId>org.apache.spark</groupId>
        <artifactId>spark-streaming_2.12</artifactId>
        <version>3.1.1</version>
    </dependency>
    <dependency>
        <groupId>org.apache.spark</groupId>
        <artifactId>spark-streaming-kafka-0-10_2.12</artifactId>
        <version>3.1.1</version>
    </dependency>```
