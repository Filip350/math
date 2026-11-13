---
title: Geometria liczb zespolonych
date: 2026-11-10
---
# Geometria liczb zespolonych

2.1 Obliczanie odległości między dwoma punktami $z_1,  z_2$ 
$$
\boxed{d(z_1,z_2)=|z_2-z_1|}
\\\\
z_2-z_1=(5+5i)-(2+i)
\\
z_2-z_1=3+4i
$$
Odejmujemy jeden punkt od drugiego dzięki czemu "przesuwamy drugi o wartość pierwszego w stronę początku układu współrzędnych" tak jakbyśmy liczyli moduł od punktu (0,0)

2.2 Geometryczna interpretacja (koła, okręgi, pierścienie) modułu liczby zespolonej
$$
|z-z_0| \ \square\ r \\\\
gdzie \ \ \square\ \ to \ =,<,\leq, >, \geq \\\\
pierścień \ \ \ 2<|z-(1+3i)|\leq5 
$$
2.3 Symetralna odcinka

$\boxed{|z-z_1|=|z-z_2|}$  

Zbiór punktów równoodległych od $(z_1)$ i $(z_2)$ – **prosta prostopadła do odcinka, przechodząca przez jego środek**.

**Schemat wyznaczania:**
1. Środek odcinka:
$$ S=\left(\frac{x_1+x_2}{2},\frac{y_1+y_2}{2}\right) $$
2. Nachylenie odcinka:
$$  
a=\frac{y_2-y_1}{x_2-x_1}  
$$
3. Nachylenie symetralnej:
$$
a_s=-\frac1a  
$$
4. Równanie symetralnej:
$$y=a_sx+b  $$
Podstawiamy współrzędne środka (S), aby obliczyć (b).

Półpłaszczyzny
$$  
|z-z_1|\ \square\ |z-z_2|  
$$
$=$ – symetralna odcinka.
$<$ – punkty bliżej $z_1$.
$>$ – punkty bliżej $z_2$.
$\leq,\geq$ – analogicznie, ale z symetralną (brzegiem).

**Przykład:**
$$  
|z-2|<|z-6|  
$$
Symetralna: $x=4$.
Rozwiązanie: $x<4$ – lewa półpłaszczyzna bez brzegu.

2.4 **Elipsa** – zbiór punktów, których suma odległości od dwóch ustalonych punktów (ognisk) jest stała.

$$  
\boxed{|z-z_1|+|z-z_2|=2a}  
$$
$z_1,z_2$ – ogniska elipsy.
$S$ – środek (punkt między ogniskami).
$a$ – półoś wielka (połowa sumy odległości).
$c$ – odległość środka od ogniska.
$b$ – półoś mała, obliczana z Pitagorasa:

$$  
\boxed{b^2=a^2-c^2}  
$$
**Przykład:**
$$  
|z-3|+|z+3|=10  
$$
$$  
S=(0,0),\quad a=5,\quad c=3,\quad b=4  
$$
**Postać kartezjańska** – ta sama elipsa zapisana za pomocą współrzędnych $x,y$:
$$  
\boxed{\frac{x^2}{25}+\frac{y^2}{16}=1}  
$$

Mianownik $25=a^2$ – rozciągnięcie poziome.
Mianownik $16=b^2$ – rozciągnięcie pionowe.

Jeżeli środek to $S=(h,k)$, uwzględniamy przesunięcie:
$$  
\boxed{\frac{(x-h)^2}{a^2}+\frac{(y-k)^2}{b^2}=1}  
$$
_Wzór dotyczy elipsy z poziomą osią wielką. Dla pionowej zamieniamy mianowniki miejscami._
**Nierówności:** $=$ brzeg, $<$ wnętrze, $>$ zewnętrze; $\leq,\geq$ uwzględniają brzeg.