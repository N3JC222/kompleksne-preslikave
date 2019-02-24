# kompleksne-preslikave
1. Vhod
Trenutna verzija programa sprejema za definicijo začetnega območja šest (6) spremenljivk.
Območje naj je podano v kartezičnih koordinatah (brez I za imaginarno os) [začetna vrednost na osi, končna vrednost na osi, korak na osi]

Preslikavo opravimo s kompleksnimi spremenljivkami (A, B, C, D - (Az + B)/(Cz - D) ), ki jih lahko poljubno spreminjamo.

Barvo točk lahko spreminjamo z vrednostmi R, G, B (0-255).

2. Izhod
Trenutna verzija programa gre čez naše območje, preslika točke in jih nariše na "primarni" canvas element (meje območja (-3 -> 3)). 
Za lažjo predstavo vhodnega območja nariše osnovne točke na "sekundarni" canvas element (meje območja (-5 -> 5)).
Za lažjo orientacijo, program nariše tudi realno in imaginarno os glede na meje območja (default: T(0,0) v sredini canvas elementa) in označi točki (T1(1,0), T2(0, I) za lažjo predstavo velikosti enot)


