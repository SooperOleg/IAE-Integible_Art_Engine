�� ���������� � ������� �������� ������� IAE - Intelligible Art Engine (�������� ������������� ������)
� ���� �������� ��������� ����� ���������� IAE, � ����� �������� �������.
������ �������� ������������������ � ������ ����������� �� ������������ �������� windows � POSIX
� ������ ��������� ����������� �������:
	- IAE_Math // ������ ����������
	- IAE_Graphics // ����������� ������
		- IAE_Graphics2D
		- IAE_Graphics3D 
	- IAE_Controlers // ���������� ����� � ������
	- IAE_GUI // ���������� ���
	- IAE_Network // ������� ��������������
	- IAE_FileSystem // �������� �������
	- IAE_DetectCollision // ���������� ������
	-? IAE_Threading // ������������������ � ��������������� ��������������
	-? IAE_Binary // ������ � �������
	-?h IAE_FileFormat_ // ������ � ��������� ������
	-?h IAE_StatusManger // �������� ��������� ����������
	-?h IAE_LoadingResources_ // �������� ��������� ��������
	-@ IAE_Core // ���� ����������
		-@iaesys
			-@ IAE_Core_windows_
			-@ IAE_Core_posix_
		-@ iaemath
	-@ IAE_Scripts // ���������� ������ FUL
	-h IAE_Define_ // ����������� �����������
(�����������:
	- ������
	-? ��������� ������
	-@ ��������������� ������
	-h ��������������� ������)
(����� ������ ��� ������������� ���������� ��� ����� ���������� � ����������, ����� ������������
������� ���������� ������ ����������� � ���� ������)

��� ������ ����� ���� ������������ �������� ���� �� �����, ��� �������� IAE_Controlers �����
���� ����������� �������� �� IAE_Network. ����������� ����� ��� ���������� ��������������� ������.
��� ������������ ����� �������.

�������� ������� ������������ ����� ��������� ��������� (���������������� � �������� �����)
��� �������� ����������������� ���������� IAE. ��� ���������� ����������� ������������ ����������
� ����� ���� ����������� � �������� �������.

��� �������� �������������� ���������� ����� ���� ������������ ������� make

� ��������� ������� ���������� ����������� SDK (Software Delovopment Kit), ��������������� ��� ����������
���������� (���������� ������ ��� �������������� ����������� GCC|MinGW|MVSC)

SDK ������������� ������� ������ ��� ���������� ��������� �������� ����������, � �������������� �����
��������� ���� ��� ������������ ��������������.

������ SDK:
	- MainWindow
	- ResourceManager
	- GraphicViwer
	- CodeViwer
	- ProjectManager
	- SceneViwer
	- RunProjectWiver
	- CompileProject
	- CompileResources
	- DialogWindows

SDK ������������� �������� �� ������ ������ � ��������� ��������� ������������
��������� �������� ����� ������ (�� ���� ���������� ������������� ������������ ���������� ���������
������������� � ������������). �������� �������� SDK � �������������� ��������� ���������� QT.

������ ������� �� ����� ���������������� C++ � ����������� �������������� ����������������� ����������� �����
��� ���������� �������� ��������� � �������� ������ ����������. ��� ���������� ����������� �������� ��������������
� ������������� ��������� ��������� Windows � ������������ ������ ��������� POSIX

===============================================================================================================

������������ � ������� ����� ���������� � �������� /doc � �������������� ������ � ������������ txt.
������ ���������� ����������� � �������� /IAE
������ SDK ����������� � �������� /IAE_SDK
������ ����������� ����� FUL(Full United Language) /FUL_Source
�������� ������� /test
