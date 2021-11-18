# polyglot-maven-sample

Reference : https://github.com/takari/polyglot-maven

## What am I doing?

### 1. add extensions.xml
```xml
<?xml version="1.0" encoding="UTF-8"?>
<extensions>
  <extension>
    <groupId>io.takari.polyglot</groupId>
    <artifactId>ARTIFACTID</artifactId>
    <version>0.4.6</version>
  </extension>
</extensions>
```

### 2. Convert POM
```sh
mvn io.takari.polyglot:polyglot-translate-plugin:translate -Dinput=pom.xml -Doutput=pom.yaml
```

### 3. IntelliJ POM recognition
If you use IntelliJ IDE

![image](https://user-images.githubusercontent.com/9425680/142365633-8d628adb-d148-4829-978a-0e939ee3394a.png)
