# Proyecto-Escolar-aiudaaa-tioo
Trabajo que me toca hacer para la escuela.

print("Teorema de Pitagoras",)
print("")
import time
for reglas in [2]:
  time.sleep(reglas)
  print(f"En La Variable que buscas debes poner (0)")

for i in [3]:
  time.sleep(i)
  print(f"")


#Que es lo que calculara 
o1= float(input("Valor del Cateto (a): ") )     
o2= float(input("Valor del Cateto (b): ") )     
o3= float(input("Valor de la Hipotenusa (c): ") ) 

if o1==0:
  print("Bien Entonces buscas Cateto a") 
elif o2==0:
  print("Bien Entonces buscas Cateto b")
elif o3==0:
  print("Bien Entonces buscas Hipotenusa")
else:
  print("Entonces haré tu Calculo ")
  
o4= float(input("Continuamos? (Si=00) (No=1) ") )
if o4==1:
  print("No? Entonces que onda we?, no mentira mis jeje")  


#Una pausa antes de calcular
import time

for i in [1]:
  time.sleep(i)
  print(f"calculando..")
for i in [1]:
  time.sleep(i)
  print(f".")
for i in [.2]:
  time.sleep(i)
  print(f".")
for i in [.2]:
  time.sleep(i)
  print(f".")
for i in [.4]:
  time.sleep(i)
  print(f"")

#Esta es la seccion donde hay un error
c3=(o3**2)
c2=(o2**2)

if o1==0:
    print("El cateto (a) es",c3-c2)
elif o2==0:
  print("El cateto (b) es",o1+o3)
elif o3==0:
  print("La Hipotenusa (c) es",o1+o2)
#Aqui termina el bloque


#Reiniciar todo
o7= float(input("Reiniciar? (si=00) (No=1)"))
if o7==00:
  print("ok")
elif o7==1:
  print("Que Negativo anda mi Rey/Reina")

for i in [2]:
  time.sleep(i)
  print(f"Reinciando...")

for i in [1]:
  time.sleep(i)
  print(f"")
for i in [1.6]:
  time.sleep(i)
  print(f"")
