# LiteFileServer
ʹ��Google Dart���������������򵥵��ļ����ط�������
����Ҫ��װnginx/apache��ռ�ø��ٵ���Դ��

1.��װdart sdk

��ο���[����](https://www.dartlang.org/tools/download-editor.html?utm_expid=51752263-1.WpTWnsvDTEGD1RYXp5u58g.1&utm_referrer=https%3A%2F%2Fwww.dartlang.org%2Ftools%2Fsdk%2F "dark sdk")

2.���pub����������

    export PATH=$PATH:/usr/lib/dart/bin

3.��ȡ��Ŀ

    git clone https://github.com/Jokder/LiteFileServer.git

4.����

�����ļ���LiteFileServer/conf.json

    {
    "version": "0.0.1",
    "port":8082,      #�˿ں�
    "root":"web"      #վ���Ŀ¼
    }

�ļ��б��վ���Ŀ¼�µ�filesĿ¼�ж�ȡ��

5.����

    cd LiteFileServer
    pub install
    nohup dart main.dart >/dev/null 2>&1 &


