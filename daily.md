#daily
- tags
 [intellij] : intellij툴 관련
 [미디어캐스트] : 미디어캐스트 관련
 [싸인캐스트] : 미디어캐스트 관련

##solved
###[intellij] hibernate schema run as application 문제.//2017.12.18 : -ek

: intellij hibernate schema관련 작업을 .java run as application 문제.

error log : servlet null 관련  >
 1. pom.xml 수정
 ```
 <dependency>
     <groupId>javax.servlet</groupId>
     <artifactId>javax.servlet-api</artifactId>
     <version>3.1.0</version>
     <scope>provided</scope>
 </dependency>
 ```
 2. cfg 위치수정(resource 쪽으로)


###[싸인캐스트] jdk complier 1.6으로 되돌아보는문제.//2017.11.?? : -ek
 1. pom.xml 수정
 maven-compiler-plugin 내 config 의 source와 target 을 1.7로 수정

```
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-compiler-plugin</artifactId>
    <version>2.5.1</version>
    <configuration>
        <source>1.7</source>
        <target>1.7</target>
        <compilerArgument>-Xlint:all</compilerArgument>
        <showWarnings>true</showWarnings>
        <showDeprecation>true</showDeprecation>
    </configuration>
</plugin>
```

##todo solve
###1.[intellij]dc 등 관련 live template 설정 옮기기.
###2.[미디어캐스트] player_skin null 문제 - event시
###3.[미디어캐스트] player_skin null 문제 - event시


##todo organize
###1.