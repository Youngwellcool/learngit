This is my dev branch yeah!

Git is a distributed version control system.
Git is free software.
Learn git
git has a mutable index called stage
git tracks changes of files
git move
git creating a new branch is quick
creat branch dev

git is simple and diffrent


���
1�����������������ڵ������ܿ�����Ŀ¼
2���汾�⣺��������һ������Ŀ¼.git��������㹤����������Git�İ汾�⡣Git�İ汾������˺ܶණ������������Ҫ�ľ��ǳ�Ϊstage�����߽�index�����ݴ���������GitΪ�����Զ������ĵ�һ����֧master���Լ�ָ��master��һ��ָ���HEAD
3���ݴ������ڹ�����ִ�� git add . ���ǰѹ������ύ���汾����ݴ�����
4��master��֧�������ǰ�л�������master��֧���ڹ�����ִ�� git commit -m "�ύע��",���ǰѰ汾����ݴ����������ύ���汾���master��֧��
5��Զ�ֿ̲⣺����˵GitHub�������Ƶȣ����ڱ��صĲֿ����Զ�ֿ̲⣬������GitHub�ϴ�����һ���ֿ�ʱ��GitHub���Զ�������ֿ�����Ϊorigin�ֿ⣬�ڹ�������ִ�� git push -u origin master ���ǽ����ص�master��֧�������ύ��GitHub�������´����õĲֿ�origin��master��֧��


����git����:
1��git status ---�鿴��������״̬(�Ƿ����޸��˻�û���ύ���汾���)
2��git add readme.txt/. ---����������ָ���ļ�����ȫ���ļ��ύ���ݴ�����
3��git commit -m '�ύע��'  ---���ݴ����е������ύ���汾��ĵ�ǰ��֧(master)��
4��git remote add origin git@github.com:youngwellcool/learngit.git   ---�ѱ��صİ汾���Զ�ֿ̲�origin��������(����)
5��git push -u origin master  ---�����صİ汾���еĵ�ǰ��֧�е������ύ��Զ�ֿ̲�origin��master��֧�� (��һ���ύʱ��Ҫ����-u����ѱ��ص�master��֧��Զ�̵�master��֧�����������Ժ���ύ�Ϳ��Բ���Ҫ����-u)
6��git checkout -b dev  ---����dev��֧�����л���dev��֧����dev��֧��Ϊ��ǰ��֧���Ժ�Ĳ���add��commit��push�ȶ�����dev��֧�в�������ԭ�ȵ�master��֧���ֲ��䣩
7��git brach  ---�鿴���еķ�֧������ǰ�����*�����ǵ�ǰ��֧
8��git checkout master  ---��master��֧��Ϊ��ǰ��֧
9��git merge dev   ---��dev��֧�Ĺ����ɹ��ϲ�����ǰ��֧��
10��git branch -d dev  ---ɾ��dev��֧
