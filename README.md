# AndroidManifest ARSC �������ļ�ԭʼ�޸���


## 1.��;
������ض�apk�������ƽ�֮���޷��ر��������ֱ�ӽ���arsc�ļ��Ķ������ļ��޸ģ�Ȼ��ֻ��Ҫ����ǩ�����ɡ������ڽ��з�����ͻر��롣

## 2.�÷�
### 1>��������
**java -jar AXMLEditor.jar -attr -i [��ǩ��] [��ǩΨһ��ʶ] [������] [����ֵ] [����xml] [���xml]**

������java -jar AXMLEditor.jar -attr -i application package debuggable true AndroidManifest.xml 
AndroidManifest_out.xml

application�ı�ǩ�в���android:debuggable="true"���ԣ��ó����ڿɵ�ʽ״̬

### 2>ɾ������
**java -jar AXMLEditor.jar -attr -r [��ǩ��] [��ǩΨһ��ʶ] [������] [����xml] [���xml]**

������java -jar AXMLEditor.jar -attr -r application allowBackup AndroidManifest.xml AndroidManifest_out.xml

application��ǩ��ɾ��allowBackup���ԣ�������app�Ϳ��Խ���ɳ�����ݱ���

### 3>��������
**java -jar AXMLEditor.jar -attr -m [��ǩ��] [��ǩΨһ��ʶ] [������] [����ֵ] [����xml] [���xml]**

������java -jar AXMLEditor.jar -attr -m application package debuggable true AndroidManifest.xml AndroidManifest_out.xml

application�ı�ǩ���޸�android:debuggable="true"���ԣ��ó����ڿɵ�ʽ״̬

### 4>��ȡ����
**java -jar AXMLEditor.jar -attr -m [��ǩ��] [��ǩΨһ��ʶ] [������] [����xml]**

������java -jar AXMLEditor.jar -attr -m application package name AndroidManifest.xml

application�ı�ǩ���޸�android:debuggable="true"���ԣ��ó����ڿɵ�ʽ״̬

### 5>�����ǩ
**java -jar AXMLEditor.jar -tag -i [��Ҫ�����ǩ���ݵ�xml�ļ�] [����xml] [���xml]**

������java -jar AXMLEditor.jar -tag -i [insert.xml] AndroidManifest.xml AndroidManifest_out.xml

��Ϊ�����ǩʱһ����ǩ���ݱȽ϶࣬�������ʽ�����㣬��������һ����Ҫ�����ǩ���ݵ�xml�ļ����ɡ�

### 6>ɾ����ǩ
**java -jar AXMLEditor.jar -tag -r [��ǩ��] [��ǩΨһ��ʶ] [����xml] [���xml]**

������java -jar AXMLEditor.jar -tag -r activity cn.wjdiankong.demo.MainActivity AndroidManifest.xml AndroidManifest_out.xml

ɾ��android:name="cn.wjdiankong.demo.MainActivity"�ı�ǩ����

