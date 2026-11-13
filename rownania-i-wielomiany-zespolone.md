---
title: Równania i wielomiany zespolone
date: 2026-11-11
---
# Równania i wielomiany zespolone

3.1 **Pierwiastek wielomianu** – liczba $z$, dla której $P(z)=0$.

W zbiorze $\mathbb{C}$ rozwiązujemy również równania z ujemną deltą:
$$  
\sqrt{-36}=6i  
$$
3.2 Pierwiastki sprzężone - Jeżeli wielomian ma **współczynniki rzeczywiste**, to wraz z pierwiastkiem $a+bi$ występuje pierwiastek sprzężony $a-bi$.
$$  
z_1=2+3i \Rightarrow z_2=2-3i  
$$
3.3 Rozkład wielomianu na czynniki - Jeśli znamy pierwiastki $z_1,z_2$, możemy zapisać wielomian stopnia drugiego:
$$  
\boxed{P(z)=a(z-z_1)(z-z_2)}  
$$
Gdzie $a$ to współczynnik przy $z^2$.

**Przykład:**
$$  
P(z)=z^2-6z+13  
$$
Pierwiastki: $z_1=3+2i$, $z_2=3-2i$.
$$  
P(z)=(z-(3+2i))(z-(3-2i))  
$$
3.4 **Krotność pierwiastka wielomianu** – liczba wystąpień danego pierwiastka w rozkładzie wielomianu na czynniki.

Przykład:
$$  
P(z)=(z-2)^2(z-3)  
$$
$z=2$ – pierwiastek dwukrotny.
$z=3$ – pierwiastek jednokrotny.

**Zasada:** suma krotności wszystkich pierwiastków jest równa stopniowi wielomianu (w zbiorze $\mathbb C$).
$$  
2+1=3  
$$
3.5 Zasadnicze twierdzenie algebry

Każdy wielomian stopnia $n\geq1$ o współczynnikach zespolonych ma **dokładnie $n$ pierwiastków zespolonych, licząc z krotnościami**.

Przykład:
$$  
P(z)=(z-2)^2(z+3)  
$$
$z=2$ – krotność 2.
$z=-3$ – krotność 1.
Stopień wielomianu: $3$.

**Wniosek:** każdy wielomian stopnia $n\geq1$ można w zbiorze $\mathbb C$ rozłożyć na $n$ czynników liniowych, uwzględniając ich powtórzenia.