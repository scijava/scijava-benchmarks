# scijava-benchmarks

[JMH](http://openjdk.java.net/projects/code-tools/jmh/)-based benchmarks for [SciJava](https://github.com/scijava/) projects.

## Execute

1. Build [`imagejan/scijava-plugins-io-table#update-pom`](https://github.com/imagejan/scijava-plugins-io-table/tree/update-pom) locally with Maven 
1. Build with Maven: `mvn clean package -o -U -Denforcer.skip=true`
2. `java -jar targets/benchmarks.jar`