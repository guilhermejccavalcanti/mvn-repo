# mvn-repo

Stores custom maven artifacts. 

To use that, add this repository to your pom.xml

```xml
<repositories>
  <repository>
    <id>guilhermejccavalcanti</id>
    <name>guilhermejccavalcanti</name>
    <url>https://github.com/guilhermejccavalcanti/mvn-repo/raw/master/</url>
  </repository>
</repositories>
```
Then add any artifact from here as a maven depedency, for instance, for the file in https://github.com/guilhermejccavalcanti/mvn-repo/blob/master/smart/smartzap/1.0.0/smartzap-1.0.0.jar add:

```xml
<dependency>
  <groupId>smart</groupId>
  <artifactId>smartzap</artifactId>
  <version>1.0.0</version>
</dependency>
```
