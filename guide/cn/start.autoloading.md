# �Զ�����

Kohana ��Ҫʹ�� PHP �����[�Զ�����](http://php.net/manual/language.oop5.autoload.php)����������˲��õ��� [include](http://php.net/include) �� [require](http://php.net/require) ֮ǰ�Ϳ���ʹ�����ļ���

��Ҳ����ͨ�� [Kohana::auto_load] �������أ���ʹ�ôӼ򵥵�������ת��Ϊ�ļ�����

 Classes are loaded via the [Kohana::auto_load] method, which makes a simple conversion from class name to file name:

1. ����������[�ļ�ϵͳ](start.filesystem)��  `classes/` Ŀ¼
2. �κ��»����ַ�ת��Ϊб��
2. �ļ���������Сд��

������һ����δ�����ࣨ���磬`Session_Cookie`����ͨ��ʹ�� [Kohana::find_file] ���������� Kohana �����ļ�ϵͳ������Ϊ `classes/session/cookie.php` ���ļ���

## �Զ�������

[!!] �� `application/bootstrap.php` �����ļ�Ĭ���Ѿ��������Զ���������

ʹ�� [spl_autoload_register](http://php.net/spl_autoload_register) ��Ӷ�������������