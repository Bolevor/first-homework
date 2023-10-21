 # ������� �������� ��� ��������, ������������� ���������� ����������� � ���������� ��� � ��������� ������������ �� GitHub
 
 cd d:/'git projects'/'First Homework'  
    git init  
    touch readme.md  
    git add readme.md  
    git commit -m 'ddddd'  
    git status  
    git remote add git@github.com:Bolevor/first-homework.git  
    git push -u origin master

# ��������� �� ��������

## ��� � ������������� �������	

��� � �������� ������������� ������� � ��������� ������ ��� ������, ���� � ���������� ������������� ������.

# HEAD � ����� ������

���� HEAD (����. �������, ���������) � ���� �� ��������� ������ ����� .git. �� ��������� �� ������, ������� ������ ��������� (�� ���� �� ����� �����).

# ����

```
git log``` - ������� ������ ����� ������ � git

```
git log --oneline``` - ����������� ���

# ������� ������

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;
  
 %% ������� ��� ������ ��� �������: 
  A --> B;
```
