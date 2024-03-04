# Language-decoding
Language decoding using python
#!/bin/python3
def malayalam():
    for i in range(0xd00,0xd7f):
      print(chr(i),end=' ')
def tamil():
    for i in range(0x0b80,0x0bff):
      print(chr(i),end=' ')
def kannada():
    for i in range(0x0c80,0x0cff):
      print(chr(i),end=' ')
def telungu():
    for i in range(0x0c00,0x0c7f):
      print(chr(i),end=' ')
def Devanagari():
    for i in range(0x0900,0x097f):
      print(chr(i),end=' ')
def Geometricshapes():
    for i in range(0x25a0,0x25ff):
      print(chr(i),end=' ')
def chesssymbols():
    for i in range(0x2654,0x2659):
      print(chr(i),end=' ')
def emoteicons():
    for i in range(0x1f604,0x1f60d):
      print(chr(i),end=' ')
while True:
     print('\nMenu')
     print('1.Malayalam script')
     print('2.Tamil Script')
     print('3.Kannada script')
     print('4.Telungu script')
     print('5.Devanagri script')
     print('6.Geometricshapes')
     print('7.Chesssymbols')
     print('8.Emoteicons')
     print('9.Exit')
     choice=int(input("Enter the number: "))
     if choice ==1:
         malayalam()
     elif choice ==2:
         tamil()
     elif choice ==3:
         kannada()
     elif choice ==4:
        telungu()
     elif choice==5:
         Devanagari()
     elif choice==6:
         Geometricshapes()
     elif choice==7:
         chesssymbols()
     elif choice==8:
         emoteicons()
     elif choice==9:
         print('Exit')
         break
     else:
         print("invalid choice")

