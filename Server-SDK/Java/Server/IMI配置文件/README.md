# server-sdk-java configuration

> ��Ŀ¼Ϊjava��server-sdk�����ļ�Ŀ¼��

## һ��Ŀ¼������
- ��*[/META-INF/imi/imi-config.properties](./META-INF/imi/imi-config.properties)*�� Ϊserver-sdk������Ϣ�����ļ���
- ��*[/META-INF/imi/imi-ks](https://github.com/imiapp/imi-sdk/blob/master/Server-SDK/Java/Server/IMI%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6/META-INF/imi/imi-ks)*��Ϊserver-sdk ˽ԿKeyStore�ļ���

## ����Ĭ�����ô��·����
- ���������ļ�·����classpath:/META-INF/imi/imi-config.properties
- keystore�ļ�·����classpath:/META-INF/imi/imi-ks
- �����ļ�Ҳ�ɷ�����ϵͳ�ļ�Ŀ¼�£����������ļ���ŷ�ʽ���ȡ��ʽ��ο��ĵ���*[�������Server-SDK�ӿ����x.x.x.pdf](../)*��

## ��������˵����
> ���������ļ�imi-config.properties�е�����˵����
- MappingServer�������ӿڵ�ַ�л���
  `��ַ������Ϊwatchtower.service.azurenet.cnע�͵���������������MappingServer�������ӿڵ�ַ��`
  `��ַ������Ϊtest.service.azurenet.cn���ǲ��Ի�����MappingServer�������ӿڵ�ַ��`
  `�û����ݿ����������н���ע���л���`

- ������Ϣ��imi.name=DefaultName��Ҫ�û�������д�Խ�Ӧ�ó����ơ�