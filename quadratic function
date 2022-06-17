import numpy as np

def kwadratowa(a, b, c):
    delta = b**2 - 4*a*c
    if delta < 0:
        return None
    elif delta == 0:
        x = -b/(2*a)
        return x
    else:
        x1 = (-b + np.sqrt(delta))/(2*a)
        x2 = (-b - np.sqrt(delta))/(2*a)
        return x1, x2

a = float(input("Podaj a: "))
b = float(input("Podaj b: "))
c = float(input("Podaj c: "))

if kwadratowa(a, b, c) is None:
    print("Rownanie sprzeczne")
elif kwadratowa(a, b, c) == 0:
    print("Rownanie ma jedno rozwiazanie:", kwadratowa(a, b, c))
else:
    print("Rownanie ma dwa rozwiazania:", kwadratowa(a, b, c))
