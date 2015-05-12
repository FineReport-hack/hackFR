注意事项：

1. JDK 版本一定要是1.5，因为其他的class文件的版本是49(也就是JDK1.5)
2. 将编译好的class文件拷贝到原先Jar包的相应位置
	- LicUtils.class 拷贝到com.fr.stable目录里
	- VersionInfoTableData.class 拷贝到com.fr.data目录里
3. 将FineReport.lic拷贝到C:\FineReport_7.1\WebReport\WEB-INF\resources
4. 文件替换完成后重启server即可