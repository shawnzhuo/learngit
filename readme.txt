Git �ֲ�ʽ�汾����ϵͳ


git���ԭ��

ͨ�� �� �м����� �� ��������ֿ⡱ ���а汾����
�޸ĵ��ļ���������ӵ��м���stage�� Ȼ�����ύ�����ֿ�

���Խ����޸ģ����ˣ�ɾ�����ύ�Ȱ汾����


ʹ�ã�


#ע��
 ȫ���û�����ȫ���ʼ���ϵ��

$ git config --global user.name "Your Name"$ git config --global user.email "email@example.com"


#�����¿�, ��Ϊ��repository
(���ǹ���Ŀ¼���ļ��İ汾)
init
��ʼ����
ѡ��һ��Ŀ¼��Ϊ�¿�
ʹ��git init
$ git init





Add
�����ļ�����Ŀ¼
Ȼ��ע����ӵ�git���м���
$ git add readme.txt


Commit
ʹ��commit�İ������м����ļ��ύ������
$ git commit
$ git commit -m "wrote a readme file"




Checkout
���ǻ��ˣ�����ȡ��������ǰ���µ�һ���汾
1�����˺�����һ��
2�������ǻ��˺� �м��� һ�£����������ύ���м���


��ǩtag
��������ĳ��ʱ�̵İ汾��
��commit�������ǣ���ǩ�����ƣ�commit�����ֲ����׼���

��֦
����һ������汾


��������δ�ύ���ļ�
�ݴ������м仺���ļ���add�ύ���
Master��ʽ���� ��ʽ�ύ�����ļ���commit�ύ��
ΪʲôGit����ļ���Ҫadd��commitһ�������أ���Ϊcommit����һ���ύ�ܶ��ļ�����������Զ��add��ͬ���ļ�

�û�סĿ¼��
/c/Users/shawnzhuo/.ssh/


Github
������Զ�� ���⣻

����Զ������----��¡----�Լ�Զ������-----get---��������




Ҫ����һ��Զ�̿⣬ʹ������
git remote add origin git@server-name:path/repo-name.git��
git remote add origin git@github.com:shawnzhuo/learngit.git


������ʹ�������һ������master��֧���������ݣ�
git push -u origin master

�˺�ÿ�α����ύ��ֻҪ�б�Ҫ���Ϳ���ʹ���������������޸ģ�
git push origin master


github��¡�����ؿ�
git clone git@github.com:shawnzhuo/gitskills.git


