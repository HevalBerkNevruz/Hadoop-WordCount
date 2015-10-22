# Hadoop-WordCount
Technologies Used;
* Java
* Hadoop
* Maven

##Compile WordCount.java and create a jar;
```
$ bin/hadoop com.sun.tools.javac.Main WordCount.java
$ jar cf wc.jar WordCount*.class
```

##To add file of HDFS;
```
$ bin/hadoop dfs -put lyrics.txt /
```

##Run the Application;
```
$ bin/hadoop jar WordCount.jar WordCount lyrics.txt /user/heval/wordcount/output
```
