---
lang:   RU
title:  И напоследок 
answer: не равно 100$
ok:     Так лучше
error:  Это неправильно
---

Видите двойное равно __'abc' == 'def'__?

Это __==__ означает __проверка на равенство__.
Одиночное равно используется для присваивания значения переменной.

Чтобы немного вас запутать: вы можете использовать присваивание как аргумент метода if:

    a = 0
    
    if a = 100
      puts "Выражение верно, но а сейчас : #{a}"
    else
      puts "#{a} не равно 100"
    end

Поменяйте = на == и посмотрите, что произойдет.

Я вам гарантирую, что вы будете часто забывать поставить двойное равенство.

### Иначе(else)
В коде я использовал else, это выполняется в случае
__if тестовое_выражение__ вычисляется как ложь(false).

> Больше информации вы можете почерпнуть
> <a href="http://www.ruby-doc.org/core/doc/syntax/control_expressions_rdoc.html" target="_blank">здесь</a>.