Istnieje wiele sześciokątnych bloków określanych jako `wyrażenia`{:class="block3operators"}, które mogą być użyte do sprawdzania warunków bloków `jeżeli...to`{:class="block3control"}, `czekaj aż`{:class="block3control"}, oraz `powtarzaj aż`{:class="block3control"} w celu podjęcia decyzji.

`>`{:class="block3operators"}, `<`{:class="block3operators"}, lub `=`{:class="block3operators"} operatorzy sprawdzają zależność pomiędzy dwoma wartościami lub `zmiennymi`{:class="block3variables"}:

+ Wartość wyższa niż:

```blocks3
if <(prędkość) > (50)> then
say [Zwolnij] for (2) seconds
end
```
+ Wartość niższa niż:

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Równa się:

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

Operatory `i`{:class="block3operators"}, `lub`{:class="block3operators"} oraz `nie`{:class="block3operators"} mogą być używane do podejmowania logicznych decyzji jeżeli:

+ `i`{:class="block3operators"} - oba warunki są prawdziwe:

```blocks3
if <<(x position) > (0)> and <(prędkość) > (50)>> then
think [Zwolnij]  
end
```

+ `lub`{:class="block3operators"} - jeden z warunków jest prawdziwy:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `nie`{:class="block3operators"} - warunek Nie jest prawdziwy:

```blocks3
if <not <(razem) < (50)>> then
move (10) steps
end
```


