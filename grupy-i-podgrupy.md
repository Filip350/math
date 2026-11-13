---
title: Grupy i podgrupy
date: 2026-11-11
---
# Grupy i podgrupy
Grupa to niepusty zbiór $(G)$ wraz z działaniem $*$, które spełnia określone warunki.
$$ \boxed{(G,*)} $$
Żeby $(G,*)$ było grupą, musimy sprawdzić cztery warunki:

| Własność          | Warunek               |
| ----------------- | --------------------- |
| Zamkniętość       | $a*b\in G$            |
| Łączność          | $(a*b)*c=a*(b*c)$     |
| Element neutralny | $a*e=e*a=a$           |
| Element odwrotny  | $a*a^{-1}=a^{-1}*a=e$ |
Warunki muszą zachodzić dla wszystkich odpowiednich elementów zbioru.

Jeżeli dodatkowo: $a*b=b*a$ to otrzymujemy grupę przemienną (abelową).

Podgrupa to po prostu mniejszy zbiór w zbiorze głównym, który z tym samym działaniem nadal tworzy grupę.

Na przykład:
$$
\boxed{(2\mathbb Z,+)\text{ jest podgrupą }(\mathbb Z,+)} \\\\
\boxed{(2\mathbb Z,+)\leq(\mathbb Z,+)} 
$$
Aby wykazać, że coś jest grupą, musimy sprawdzić wymagane własności dla wszystkich elementów.

Ale żeby wykazać, że nie jest grupą, wystarczy jeden kontrprzykład.
##### szybszy sposób sprawdzania podgrup
Zamiast za każdym razem sprawdzać wszystkie cztery własności, możemy skorzystać z kryterium podgrupy.

Jeżeli $H$ jest niepustym podzbiorem grupy $(G,+)$, to wystarczy sprawdzić:

Dla zwykłego dodawania $(G,+)$:
$$\boxed{\forall a,b\in H:\ a-b\in H}$$
Dla dowolnego działania $(G,*)$:
$$\boxed{\forall a,b\in H:\ a*b^{-1}\in H}$$