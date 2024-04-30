Existuje několik bloků `Operátorů`{:class="block3operators"}, ve tvaru šestiúhelníku, které lze použít ke kontrole podmínek v blocích `když`{:class="block3control"}, `když...jinak`{:class= "block3control"}, `počkej do`{:class="block3control"} a `opakuj do`{:class="block3control"}, abys mohl udělat rozhodnutí.

Operátory `>`{:class="block3operators"}, `<`{:class="block3operators"} nebo `=`{:class="block3operators"} kontrolují vztah mezi dvěma hodnotami nebo `proměnnými`{: class="block3variables"}:

+ Větší než:

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
end
```
+ Menší než:

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Je rovno:

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

Operátory `a`{:class="block3operators"}, `nebo`{:class="block3operators"} a `nikoli`{:class="block3operators"} dělají logická rozhodnutí, pokud:

+ `a`{:class="block3operators"} - obě podmínky jsou pravdivé:

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end
```

+ `nebo`{:class="block3operators"} – platí alespoň jedna podmínka:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `ne`{:class="block3operators"} - podmínka je nepravdivá:

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


