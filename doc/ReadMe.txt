自动构建项目

方式1:
mkdir maven03
cd    maven03
mvn archetype:generate

根据提示依次输入

groupId: maven03
artifactId: maven03-model
version: 1.0.1
package: com.stx.maven03

最后输入y

方式2:
一次设置所有属性
mvn archetype:generate -DgroupId=组织名，公司网址的反写+项目名
		       -DartifactId=项目名-模块名
		       -Dversion=版本号
		       -Dpackage=代码所在包名

mvn archetype:generate -DgroupId=com.stx.maven04  -DartifactId=maven04-demo -Dversion=1.0.0 -Dpackage=com.stx.maven04-demo
