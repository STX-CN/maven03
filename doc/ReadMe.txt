�Զ�������Ŀ

��ʽ1:
mkdir maven03
cd    maven03
mvn archetype:generate

������ʾ��������

groupId: maven03
artifactId: maven03-model
version: 1.0.1
package: com.stx.maven03

�������y

��ʽ2:
һ��������������
mvn archetype:generate -DgroupId=��֯������˾��ַ�ķ�д+��Ŀ��
		       -DartifactId=��Ŀ��-ģ����
		       -Dversion=�汾��
		       -Dpackage=�������ڰ���

mvn archetype:generate -DgroupId=com.stx.maven04  -DartifactId=maven04-demo -Dversion=1.0.0 -Dpackage=com.stx.maven04-demo
