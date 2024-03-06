#bienvenidos a mi sufrimiento (la programacion)

<p>ola, aqui vas a ver los ejercicios del reto 3 que con tanto esfuerzo y sufrimiento logré terminar</p>

1. Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.

<b>1.1 Pseudocodigo para obtener los numeros primos hasta un entero positivo n</b>

``` 
n: entero 
x: entero
primos: entero


Inicio
print("Ingrese un numero entero positivo n")

  x:=2
    Mientras (x < n) hacer
    descartar los multiplos de x menos x
    guardar x en primos
    Avanzar al siguiente numero en la lista con paso x+1 y repetir
    Fin Mientras
    Si (x**2 > n) entonces
	  Acaba el ciclo
	  Fin si
  print("primos")
  
  Fin
```
<b>1.2 Diagrama de flujo</b>

[![](https://mermaid.ink/img/pako:eNqFkr1OwzAUhV_lyhOUMtAxokW0oaVDu8AWd7Di29ZS7FT-EanavBgLErwYN3ZAQiDhSLZzvpMTX9snVtYSWca2Vf1S7oX18JxzA9TuL9ZBo60dHKzSNOyF8wKCAfPx2gEwl3B9PYFpsTQ7i07YCENim5QyjZZZ0YxHvTKLSl6sFBpvhYMGbr_tCT6c3t-awWAEEzB30CaURzQvcnQlrZP-pkPl1aGipUmkFI2Gpk2f9L8RNjFxUSyCsJJsDaDpi-1DiB1_s_jZY9HA1fimN369pdq44eZHDW3Uz-v63MG_kFNnWBZz1W1E91BmSk49GzLaVi2UpLM6dRpnfo8aOctoKnErqEbOuGnJKoKvn46mZJm3AYcsHKTwmCuxs0KzbCsqRypK5Wu7Sucfr0H7CdQ4pyE?type=png)](https://mermaid.live/edit#pako:eNqFkr1OwzAUhV_lyhOUMtAxokW0oaVDu8AWd7Di29ZS7FT-EanavBgLErwYN3ZAQiDhSLZzvpMTX9snVtYSWca2Vf1S7oX18JxzA9TuL9ZBo60dHKzSNOyF8wKCAfPx2gEwl3B9PYFpsTQ7i07YCENim5QyjZZZ0YxHvTKLSl6sFBpvhYMGbr_tCT6c3t-awWAEEzB30CaURzQvcnQlrZP-pkPl1aGipUmkFI2Gpk2f9L8RNjFxUSyCsJJsDaDpi-1DiB1_s_jZY9HA1fimN369pdq44eZHDW3Uz-v63MG_kFNnWBZz1W1E91BmSk49GzLaVi2UpLM6dRpnfo8aOctoKnErqEbOuGnJKoKvn46mZJm3AYcsHKTwmCuxs0KzbCsqRypK5Wu7Sucfr0H7CdQ4pyE)



2. Revise el procedimiento matemático para hallar raíces cuadradas (son divisiones y restas), plantee el algoritmo en pseudocódigo y en diagrama de flujo.

<b>2.1 Pseudocodigo para hallar raices cuadradas</b>
``` 
x: float
n: int
cociente: float
promedio: float


Inicio

print("Ingrese un numero n")
	Si n < 0 entonces
	  print("El numero", n ,"No tiene raiz cuadrada
	Sino si n==0 entonces
	  print("La raiz cuadrada de", n ,"es 0")
	Sino
	  x= 2.0
	  cociente= n/x
	  promedio= (x + cociente)/2.0
	  
	  Mientras cociente != promedio:
	  x= promedio
	  cociente= n/x
	  promedio= (x+cociente)/ 2.0
	  
	  print("La raiz cuadrada de", n ,"es", promedio, ")
	  
	  Fin Mientras

	Fin Sino

	Fin Sino si

	Fin Si

Fin
```

<b>2.2 Diagrama de flujo</b>

[![](https://mermaid.ink/img/pako:eNqlks9uwjAMxl_Fywm0MdCO1boJKH86DQ7AAanlYDUGKrUJSlONDXi2SXuyJW0pHNhpqRS5v3z-bCU-sEhyYg5bJ_Ij2qLSsPBCAWZ1GzOMvyDKkSvkCJwgFyDylJQE0YRW6wV6gS82ijJU12er0qBXSPrBz_cSnqHzWuH-4QxOheCYxUfwgkFS50vQMQkCZer_lTSVRxgYKFzXsFJ0-b8YD4N3LIxs_wIog87qtto6joK9C0-PnVIRycj0ockF0V6WaKdkSjyWLuzhvha0bU5l61m3cTDxB9PFrDuv6PAmHVXUmijMaj-4c-tKYIAUEWVlyv5y8o8mx7awX1_N9RsXd3R2qOS-lb81hrFohsJ-FpZREZ-B3dkDM6-YYszNVB0sC5neUkohc0zIaY15okMWipORYq7l_FNEzNEqpweW7zhq8mLcKEyZs8YkM9S0oqWalJNaDOzpF1062hM?type=png)](https://mermaid.live/edit#pako:eNqlks9uwjAMxl_Fywm0MdCO1boJKH86DQ7AAanlYDUGKrUJSlONDXi2SXuyJW0pHNhpqRS5v3z-bCU-sEhyYg5bJ_Ij2qLSsPBCAWZ1GzOMvyDKkSvkCJwgFyDylJQE0YRW6wV6gS82ijJU12er0qBXSPrBz_cSnqHzWuH-4QxOheCYxUfwgkFS50vQMQkCZer_lTSVRxgYKFzXsFJ0-b8YD4N3LIxs_wIog87qtto6joK9C0-PnVIRycj0ockF0V6WaKdkSjyWLuzhvha0bU5l61m3cTDxB9PFrDuv6PAmHVXUmijMaj-4c-tKYIAUEWVlyv5y8o8mx7awX1_N9RsXd3R2qOS-lb81hrFohsJ-FpZREZ-B3dkDM6-YYszNVB0sC5neUkohc0zIaY15okMWipORYq7l_FNEzNEqpweW7zhq8mLcKEyZs8YkM9S0oqWalJNaDOzpF1062hM)


