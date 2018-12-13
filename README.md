# scijava-benchmarks

[JMH](http://openjdk.java.net/projects/code-tools/jmh/)-based benchmarks for [SciJava](https://github.com/scijava/) projects.

## Execute

1. Build with Maven: `mvn clean package -o -U -Denforcer.skip=true`
2. `java -jar target/benchmarks.jar`
