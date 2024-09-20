Існує декілька шестикутних блоків `оператор`{:class="block3operators"}, за допомогою яких можна перевіряти умови у блоках `якщо`{:class="block3control"}, `якщо...то`{:class="block3control"}, `чекати поки`{:class="block3control"} та `повторити до`{:class="block3control"}, щоб прийняти рішення.

Оператори `>`{:class="block3operators"}, `<`{:class="block3operators"} і `=`{:class="block3operators"} перевіряють відносини між двома значеннями або `змінними`{:class="block3variables"}:

+ Більше ніж:

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
end
```
+ Менше ніж:

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Дорівнює:

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

Оператори `і`{:class="block3operators"}, `або`{:class="block3operators"} та `не`{:class="block3operators"} приймають логічне рішення, якщо:

+ `і`{:class="block3operators"} — обидві умови справджуються:

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end
```

+ `або`{:class="block3operators"} — одна з умов справджується:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `не`{:class="block3operators"} — умова не справджується:

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


