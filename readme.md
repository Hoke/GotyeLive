#�׼�ֱ��(GotyeLive)����APP��Ƶ��������������

##���

##ֱ��APP�������
<div align="center">
<img src="https://github.com/QPlus/GotyeLive/blob/master/pic/freamwork.jpg" width="800" alt="ֱ��APP�������ͼ" align="center"/>
</div>

Ŀǰ�׼��ṩ:

[��̨������(golang)](https://github.com/QPlus/qplus-live-server) [IOS App(object-C)](https://github.com/QPlus/qplus-live-ios)

[Android  App(java)]�׼�ϣ�����ͨ��ѧϰ֮��,�п�Դ����ĳ���Ա�ܹ����뵽�����Դ��Ŀ���У����׼ӹ�ͬ����android�汾��


##�׼�ֱ������QQȺ
�׼�ֱ��������Ⱥ_01 : [544476772](https://github.com/QPlus/GotyeLive/blob/master/pic/qpluslive-group01.png)

<img src="https://github.com/QPlus/GotyeLive/blob/master/pic/qpluslive-group01.png" width="200" alt="ȫ��ֱ��App��Ƶ����"/>


##�׼�ֱ��qpluslive����������

###���������
����Ŀ���׼�ֱ���ͻ���[QPlusLive For IOS](https://github.com/QPlus/GotyeLive_IOS)��ֱ��ҵ���������

����Ŀ��ʹ��Golang��д��ֱ��ҵ�������������ֱ�����У�Ϊ�˷����Ҳ���ʹ�ã�����ʹ���ѱ���汾��[�������]
(https://github.com/QPlus/GotyeLive/blob/master/doc/gotyelive_server.tar.gz)


����Ŀ������װȫ��ֱ��APP����ƣ�Ŀǰ��1.0�汾�����ڻ᲻�ϸ��£������ڴ���

### ʹ�÷�ʽ
����Ŀ��Ҫʹ��Mysql,��������ϵͳ�ð�װMysql��

�������ݿ�ͱ��SQL�ű�Ϊ[gotye_open_live.sql](https://github.com/QPlus/GotyeLive/blob/master/doc/gotye_open_live.sql), 
���ؽ�ѹ���.tar.gz��������С�

ѹ�������ṩ�˱���õ�֧��`Linux`�Ŀ�ִ���ļ���

ѹ�����е�[config.ini](https://github.com/QPlus/GotyeLive/blob/master/doc/config.ini)�Ƿ������������ļ������е������밲��ʽ�޸�, ����˵������:
```
[apiserver]
#�����������˿�
http_port = 8080

[mysql]
#���ݿ��ַ
address = 192.168.1.10
#���ݿ���
dbname  = gotye_open_live
#���ݿ��˺�
account = app
#���ݿ�����
password = 123456
```
ѹ�����е�[run](https://github.com/QPlus/GotyeLive/blob/master/doc/run)�Ƿ����������ű���ʹ��˵������:
run -s or start : ��������������
run -k or stop  : �رշ���������
run -i or info  : �鿴��������Ϣ
run -h or help  : ��ýű�ʹ��˵��

##API˵��

[Ӧ�ò�Э��]��鿴[API_DOC](api_doc.md)


