
maven项目框架
mvn archetype:generate -Dcheckstyle.skip -DarchetypeGroupId=org.apache.flink -DarchetypeArtifactId=flink-quickstart-java -DarchetypeVersion=1.8.0 -DarchetypeCatalog=internal
mvn archetype:generate -DarchetypeGroupId=org.apache.flink -DarchetypeArtifactId=flink-quickstart-java -DarchetypeVersion=1.12.1 -Dcheckstyle.skip -DarchetypeCatalog=local
mvn archetype:create-from-project -Dcheckstyle.skip  
archetype:generate -DarchetypeCatalog=local -Dcheckstyle.skip
clean install -DarchetypeCatalog=local -Dcheckstyle.skip