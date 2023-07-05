# ��������� ���������� ����������

��������� ���������� ���������� ����������� �� ����� C# � �������������� ��������-��������������� ���������� ����������. ��� ������������� ����������� �������� ������� � ���������� � ��� ������ � ��������� �� ���������� � �������.

## �������� �������

### ����� Apartment (��������)

����� `Apartment` ������������ ����� ������ �������� � ����� ��������� ��������:
- `Number` (����� ��������): ����� ��������
- `Owner` (��������): �������� ��������
- `Rooms` (������ ������): ������ �������� ������ `Room`, �������������� ������� � ��������.

����� `Apartment` ����� ��������� ������:
- `AddRoom(Room room)`: ��������� ������� � ������ ������ ��������.
- `Show()`: ���������� ���������� � ��������.
- `ShowAll()`: ���������� ���������� � ���� �������� � ��������.

### ����� Room (�������)

����� `Room` ������������ ����� ������ ������� � ����� ��������� ��������:
- `Name` (��������): ���������� �������
- `Area` (�������): ������� �������

����� `Room` ��������� ��������� `IComparable`, ������� ��������� ���������� ������� ������ �� ������ �� �������.

## ���������� ����������

���������� ���������� ���������� ��������� dll-���������� � ������������� ������ �������. ��� ��������� ��������� ��������:
1. ������� ������ ��������.
2. ��������� ��������� �������� ������ � ������������� �������.
3. ���������� ���������� � ���� �������� � ��������, ������������� �� �������.
