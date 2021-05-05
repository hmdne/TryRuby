---
lang:   MK
title:  Чекај малку, ја оценив ли книгата Gravity's Rainbow? 
answer: ^(splendid|quite_good|mediocre|quite_not_good|abysmal)$
load:   books = {"Gravitys Rainbow" => :splendid, "The deep end" => :abysmal, "Living colors" => :mediocre}
ok:     Многу ми се допаѓа
error:  
---

Една од прекрасните работи во Ruby е тоа што имињата се често повторно употребливи, а тоа значи помалку имиња за паметење.

Се сеќаваш ли како издвојувавме елементи од низа, со користење на број:  
__puts ticket[1]__.

Кај hash-от ова фунцкионира на ист начин, со таа разлика што кај hash-от не користиме број за да го издвоиме елементот, туку користиме име.

Па така, ако сакаш да издвоиш некој од твоите постари оцени, повторно стави го насловот во __[ ]__ наводници. Но, изостави го знакот за еднакво.
Исто како во примерот:

    puts books["Gravitys Rainbow"]