# maven-java-project-template

[![Java CI](https://github.com/PureXYZ/maven-java-project-template/actions/workflows/maven.yml/badge.svg?branch=main&event=push)](https://github.com/PureXYZ/maven-java-project-template/actions/workflows/maven.yml)

### Structure
<pre>
|-- src
    |-- main
    |   |-- java
    |       |-- com
    |           |-- purexyz
    |               |-- App.java
    |-- test
        |-- java
            |-- com
                |-- purexyz
                    |-- AppTest.java
</pre>

### Docker build
```
docker build -t maven-java-project-template:latest .
```

### Docker run
```
docker run -i --rm --name maven-java-project-template maven-java-project-template:latest
```

### Output
```
[main] INFO com.purexyz.App - Hello World!
```
