# Ballerina_Performance

1. Build the customized ballerina core using following maven command.
mvn clean install -Dcheckstyle.skip=true -Dmaven.test.skip=true -DskipTests -Dmaven.javadoc.skip=true -Dfindbugs.skip=true

2. Build the ballerina_benchmark 
mvn clean install

3. Run the java file
java -jar benchmarks.jar -wi 5 -i 10 -f 2 - t 1
