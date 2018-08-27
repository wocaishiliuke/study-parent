# study-parent

方便学习中maven项目的依赖管理，创建该Maven POM工程

## 问题
1.其中maven-resources-plugin和maven-compiler-plugin下载不下来，为lastUpload文件，可[手动下载](http://repo1.maven.org/maven2/org/apache/maven/plugins/)，或利用dependence标签下载，如下：
```
<dependency>
	<groupId>org.apache.maven.plugins</groupId>
	<artifactId>maven-resources-plugin</artifactId>
	<version>2.7</version>
</dependency>
```
