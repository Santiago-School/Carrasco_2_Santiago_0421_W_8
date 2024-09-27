# Carrasco_2_Santiago_0421_W_8

print(" ")

print("Santiago Carrasco 0421 3°W")

print(" ")

#se pregunta por el numero

numero = input("ingresa un numero natural: ")

#se hace todo el despapaye para saber si es 

#par o impar con la funcion .isdigit

if numero.isdigit():
    numeroint = int(numero)
    if numeroint % 2 == 0:
        print("el numero es par")
    else:
        print("el numero es impar")
else:
    print("no es un numero natural valido")

![image](https://github.com/user-attachments/assets/3182ff3c-616e-4928-9647-9db5e633cf5c)
