# maven
personal maven repository:
- tinylog-2.0.0
- timo-parser-1.0.0

# usage

in `pom.xml`:

**repositories:**
```
<repositories>
  <repository>
		<id>liuhuanting-maven-snapshot-repository</id>
		<name>liuhuanting-maven-snapshot-repository</name>
		<url>https://raw.github.com/liuhuanting/maven/snapshot/</url>
	</repository>
</repositories>
```
**tinylog-2.0.0:**
```
<dependencies>
	 <dependency>
		<artifactId>tinylog</artifactId>
		<groupId>com.github.liuhuanting</groupId>
		<version>2.0.0</version>
	</dependency>
</dependencies>
```
**timo-parser-1.0.0:**
```
<dependencies>
	<dependency>
		<artifactId>timo-parser</artifactId>
		<groupId>com.github.liuhuanting</groupId>
		<version>1.0.0</version>
	</dependency>
</dependencies>
```
---

个人Maven仓库

搭建方法见[利用GitHub搭建个人Maven仓库](http://liu.fm/2015/07/18/maven-repository-from-github/)
