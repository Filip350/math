---
title: Arytmetyka Modulo
date: 2026-11-12
---
# Arytmetyka modulo

**Modulo** – reszta z dzielenia liczby $a$ przez $n$, np. $17\bmod5=2$.  
**Kongruencja** – dwie liczby mają tę samą resztę z dzielenia przez $n$:  
$$a\equiv b\pmod n\iff n\mid(a-b)$$
Symbol $n\mid(a-b)$ oznacza, że $n$ dzieli $a-b$ bez reszty, np. $17\equiv2\pmod5$, ponieważ $5\mid15$.  
**Modulo liczb ujemnych** – dodajemy wielokrotności $n$, aż otrzymamy liczbę z przedziału $0\le r<n$, $\boxed{-7=(-2)\cdot5+3}$ 
**Dodawanie modulo:**  
$$(17+8)\bmod5=(2+3)\bmod5=0$$
**Mnożenie modulo:**  
$$(8\cdot9)\bmod5=(3\cdot4)\bmod5=2$$
**Potęgowanie modulo** – można redukować wyniki pośrednie:  
$$3^4=(3^2)^2\equiv1^2\equiv1\pmod8$$
**Klasa reszt** $[a]_n$ – zbiór wszystkich liczb całkowitych mających tę samą resztę modulo $n$:  
$$[a]_n={a+kn\in\mathbb Z}$$
Przykład:  
$$[2]_5={\ldots,-8,-3,2,7,12,\ldots}$$
**Równość klas:**  
$$[a]_n=[b]_n\iff a\equiv b\pmod n$$
Np. $[2]_5=[7]_5$.  
**Zbiór klas reszt:**  
$$\mathbb Z_n={[0]_n,[1]_n,\ldots,[n-1]_n}$$
Przykład: $\mathbb Z_5={[0]_5,[1]_5,[2]_5,[3]_5,[4]_5}$.  
**Dodawanie klas:**  
$$[a]_n+[b]_n=[a+b]_n$$
Np. $[3]_5+[4]_5=[2]_5$.  
**Mnożenie klas:**  
$$[a]_n\cdot[b]_n=[ab]_n$$
Np. $[2]_5\cdot[3]_5=[1]_5$.  
**Element neutralny:** dla dodawania $e=[0]_n$, dla mnożenia $e=[1]_n$.  
**Element odwrotny przy dodawaniu:**  
$$[a]_n+[-a]_n=[0]_n$$
Np. $[2]_5+[3]_5=[0]_5$.  
Każdy element ma odwrotność przy dodawaniu, dlatego $(\mathbb Z_n,+)$ jest **grupą abelową**.  
**Element odwrotny przy mnożeniu:**  
$$[a]_n\cdot[b]_n=[1]_n$$
Np. $[2]_5\cdot[3]_5=[1]_5$.  
**Warunek istnienia odwrotności przy mnożeniu:**  
$$\boxed{\operatorname{NWD}(a,n)=1}$$
**Zbiór elementów odwracalnych:** $\mathbb Z_n^\times$, np. $\mathbb Z_6^\times={[1]_6,[5]_6}$.  
$(\mathbb Z_n^\times,\cdot)$ jest grupą abelową, natomiast $(\mathbb Z_n,\cdot)$ dla $n\ge2$ nie jest grupą, ponieważ zero nie ma odwrotności.
Gdy $n$ jest liczbą pierwszą, wszystkie niezerowe klasy mają odwrotności względem mnożenia.  

**Tablica działań** – wiersz i kolumna wskazują argumenty, a ich przecięcie wynik działania.  
**Tablica dodawania modulo 3:**

|$+_3$|0|1|2|
|---|---|---|---|
|**0**|0|1|2|
|**1**|1|2|0|
|**2**|2|0|1|

**Tablica mnożenia modulo 3:**

|$\cdot_3$|0|1|2|
|---|---|---|---|
|**0**|0|0|0|
|**1**|0|1|2|
|**2**|0|2|1|

**Element neutralny w tablicy** – element, którego wiersz i kolumna pozostawiają pozostałe elementy bez zmian. Przy dodawaniu $e=0$, przy mnożeniu $e=1$.  
**Element odwrotny w tablicy** – taki element $b$, dla którego $a_b=b_a=e$.  
Przy dodawaniu modulo 3 odwrotnym do $2$ jest $1$, ponieważ $2+1\equiv0\pmod3$.  
Przy mnożeniu modulo 3 odwrotnym do $2$ jest $2$, ponieważ $2\cdot2\equiv1\pmod3$.  
**Przemienność w tablicy** – symetria względem głównej przekątnej oznacza $a_b=b_a$.  
**Łączność:**  
$$(a_b)_c=a_(b_c)$$
Trzeba sprawdzić wszystkie trójki elementów albo wykorzystać znane własności działania. Samo sprawdzenie jednego przykładu nie wystarcza.