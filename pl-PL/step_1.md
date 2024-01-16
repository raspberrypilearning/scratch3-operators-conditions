Istnieje wiele sześciokątnych bloków określanych jako `operator`{:class="block3operators"}, które mogą być użyte do sprawdzania warunków bloków `if...else`(jeśli... w innym razie){:class="block3control"}, `wait until`(czekaj aż){:class="block3control"}, oraz `repeat until` (powtarzaj dopóki) {:class="block3control"} w celu podjęcia decyzji.

`>`{:class="block3operators"}, `<`{:class="block3operators"}, lub `=`{:class="block3operators"} operatorzy sprawdzają zależność pomiędzy dwoma wartościami lub zmiennymi ``{:class="block3variables"}:

+ Wartość wyższa niż:

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
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

Operatory `and` (i){:class="block3operators"}, `or` (lub) {:class="block3operators"} oraz `not` (nie) {:class="block3operators"} mogą być używane do podejmowania logicznych decyzji jeżeli:

+ `and` (i) {:class="block3operators"} - oba warunki są prawdziwe:

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end
```

+ `or` (lub) {:class="block3operators"} - jeden z warunków jest prawdziwy:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `not` (nie) {:class="block3operators"} - warunek Nie jest prawdziwy:

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


