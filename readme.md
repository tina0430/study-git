# Hello Git World

## git�� �ֿ� ����
- �۾� ���丮 (Working Directory) : 
- �غ� ���� (Staging Area, Stage/Index) :
- ���� ����� (Local Repository) :
- ���� ����� (Remote Repository) :

## �⺻ ��ɾ�
- git init : ���� ����� �ʱ�ȭ (.git ���� ����)
- git status : ���� ������� ����
  - D : Deleted
  - M : Modify
  - ?? : New
- git add : �۾� ���丮���� �غ񿵿����� �ø�
- git commit : �غ� �������� ���� �����(.git)�� �ø�
- git commit -m "msg" : Ŀ�� �޼��� �ۼ�
- git commit -am "msg" : add + Ŀ�� �޼��� �ۼ�
- git push : ���� ����ҿ��� ���� �����(ex-github)�� �ø�
- git log : Ŀ�� ���� ������
- git reset --hard : ���� �ֱٿ� Ŀ���� �������� �ѹ�
- git rm : �۾� ���丮�� �غ񿵿��� �ִ� ���� �� ����
- git rm --cached : �۾����丮�� �ִ� ������ �ǵ��� �ʰ�, �غ񿵿��� �ִ� ���ϸ� ����

## ���ܸ�� ����
- [.gitignore ����](https://git-scm.com/docs/gitignore#_pattern_format)
- [��õ ����Ʈ](https://www.gitignore.io/)

## ���� �����
- ��Ϻ��� : git remote -v 
- �߰��ϱ� : git remote add [��Ī] [�ּ�]
- �����ϱ� : git remote rm [��Ī]
- ��Ī���� : git remote rename [������Ī] [�� ��Ī]
- �ּҼ��� : git remote set-url [��Ī] [�������ּ�]

## �귣ġ
- ��Ϻ��� : git branch
- �����ϱ� : git branch [�� �귣ġ��] �Ǵ� git branch [������ �귣ġ��] [�� �귣ġ��]
- �����ϱ� : git branch -d [�귣ġ��] 
- �̸�����(�̵�) : git branch -m [���� �귣ġ��] [�� �귣ġ��]
- ��ȯ�ϱ� : git checkout [�귣ġ��]