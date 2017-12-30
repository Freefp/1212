1、所有项目必须引用本模块；
2、修改b-a-base模块pom.xml文件中properties下的localDir参数指向b-a-base\src\lib目录
3、在项目pom.xml文件中modelVersion标签后增加引用b-a-base模块<parent>标签如下：
<parent>
	<groupId>bpit</groupId>
	<artifactId>b-a-base</artifactId>
	<version>201609</version>
	<relativePath>../b-a-base</relativePath>
</parent>


遗留问题：