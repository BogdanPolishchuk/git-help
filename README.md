# git-help 23.09.2018
 
��� ������ � �������� ���� ����������� ����������� ��������� (��� windows): 
https://desktop.github.com/

��� ������ � ���������-������� ���������� :
https://gitforwindows.org/

��� ��������� ����������� �������:
- Use Git from the Windows Command Prompt

����� ��������� � ����������� ����(������ ������ ����) ����� ����� �������� ��� ������, ����� "Git Bash Here".

����� ��������� ���-�������� ��� � �������.

���������� �������� ���������� ���������:

git config --global user.name '���_������������_github'
git config --global user.email '����_�����������_�����'
git config --global color.diff 'auto'
git config --global color.status 'auto'
git config --global color.branch 'auto'
git config --global credential.helper store
git config --global push.default simple
git config --global core.autocrlf false
git config --global core.eol lf


����� ������ �� �������������, ������� ������������ �� ������� �����������, �������� � ������������ ����������� ���������� ���� � �.�.

#������������: ������� ��������� ����� GitHub

��� ����������/������������ ������������� �����������: ������� ����� GitHub � ���-���������:

Home@Home-PC MINGW64 ~/Desktop/GitHub
$ git clone https://github.com/BogdanPolishchuk/���_�����������.git - ������ ���� �� �������� ���-�����������

� ��������� ����� GitHub �������� ����� � ������ �������

��� ��������� ������ �������� ��� ������� ���������� ���������:

Home@Home-PC MINGW64 ~/Desktop/GitHub/git-help (master)
$ git status

����� ���������� ������� ����������� � ��������� �����

��� �������� � ���������������� ������ ��� ���������� ������ :
��� ������ :
$ git add ���_����� - #��� ������ �����
��� ���������� :
$ git add -A 

����� ���������� ��� ����� �������:

$ git commit -m "����������� ��� ���������"
$ git push -f


����� ������� ���������� � �����������:

$ git pull




