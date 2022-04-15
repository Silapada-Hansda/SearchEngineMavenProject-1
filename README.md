# SearchEngineMavenProject

1. Download the project Folder
2. From the project directory execute: mvn clean package install assembly:assembly
3. From the target directory(to create index): java -jar SearchEngineProject-1.0-SNAPSHOT.jar createindex
4. From the target directory(to search args[topicQuery, top n]): java -jar SearchEngineProject-1.0-SNAPSHOT.jar 3 10

#Reference:

[1] https://lucene.apache.org/core/9_1_0/index.html
[2] https://trec.nist.gov/data/clinical2015.html
[3] http://www.trec-cds.org/
