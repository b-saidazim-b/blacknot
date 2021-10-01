print('''
+-------------------------------+
|                               |
|           BLAKNOT             |
|                               |
+-------------------------------+
''')
tanla = input('''
[1] -----> Engi blaknot 
[2] -----> Eski blaknot 
[3] -----> Chiqish \n--> 
''')
file = open('txt.txt', 'w')
if tanla == 1:
    a = input('Write bloknot: ')
    file.write(a)


if tanla == 2:
    file.read()

if tanla == 3:
    exit()

    file.close()
