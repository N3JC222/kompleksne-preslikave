# kompleksne-preslikave
1. Vhod
Trenutna verzija programa sprejema za definicijo začetnega območja šest (6) spremenljivk.
Območje naj je podano v kartezičnih koordinatah (brez I za imaginarno os) [začetna vrednost na osi, končna vrednost na osi, korak na osi]

Preslikavo opravimo s kompleksnimi spremenljivkami (8 vrednosti) (A(2), B(2), C(2), D(2) - (Az + B)/(Cz - D) ), ki jih lahko poljubno spreminjamo.
V primeru, da vrednost realnega/kompleksnega dela katere izmed ni podana (oz. je vrednost "") program privzame vrednost 0.

Barvo točk lahko spreminjamo z vrednostmi R, G, B (0-255).

2. Izhod
Trenutna verzija programa gre čez naše območje, preslika točke in jih nariše na "primarni" canvas element (meje območja (-3 -> 3)). 
Za lažjo predstavo vhodnega območja nariše osnovne točke na "sekundarni" canvas element (meje območja (-5 -> 5)).
Za lažjo orientacijo, program nariše tudi realno in imaginarno os glede na meje območja (default: T(0,0) v sredini canvas elementa) in označi točki (T1(1,0), T2(0, I) za lažjo predstavo velikosti enot)

3. Gumbi (button)
Trenutna verzija programa vsebuje dva (2) gumba.
"Draw" - nariše naše območje (trenutne meje, A, B, C, D, barva)
"Clear" - počisti canvas elementa, da strani ni potrebno znova nalagati, če postanejo canvas elementi nepregledni


