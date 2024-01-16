# Maven Compiler plugin
```xml
<properties>
	<java.version>15</java.version>
	<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
	<project.reporting.outputEncoding>UTF-8</project.reporting.outputEncoding>
</properties>

<build>
	<plugins>
		<plugin>
			<groupId>org.apache.maven.plugins</groupId>
			<artifactId>maven-compiler-plugin</artifactId>
			<version>3.12.1</version>
			<configuration>
				<source>${java.version}</source>
				<target>${java.version}</target>
				<encoding>utf-8</encoding>
			</configuration>
		</plugin>
	</plugins>
</build>
```	

## Java 와 version 충돌등이 발생할 경우 plugin 버전 down
```xml
<build>
	<plugins>
		<plugin>
			<groupId>org.apache.maven.plugins</groupId>
			<artifactId>maven-compiler-plugin</artifactId>
			<version>3.12.1</version>
			<configuration>
				<source>${java.version}</source>
				<target>${java.version}</target>
				<encoding>utf-8</encoding>
			</configuration>
		</plugin>
	</plugins>
</build>
```
