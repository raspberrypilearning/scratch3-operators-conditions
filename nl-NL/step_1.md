Er zijn een aantal zeshoekige `-operator`{:class="block3operators"}-blokken die je kunt gebruiken om voorwaarden te controleren in `Als`{:class="block3control"}, `Als....dan`{:class="block3control"}, `wacht tot`{:class="block3control"}, en `herhaal tot`{:class="block3control"} blokken om een beslissing te nemen.

De operatoren `>`{:class="block3operators"}, `<`{:class="block3operators"} of `=`{:class="block3operators"} controleren de relatie tussen twee waarden of `variabelen`{:class="block3variables"}:

+ Groter dan:

```blocks3
if <(snelheid) > (50)> then
say [Rustig aan] for (2) seconds
end
```
+ Kleiner dan:

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Gelijk aan:

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

De `en`{:class="block3operators"}, `of`{:class="block3operators"} en `niet`{:class="block3operators"} vergelijkingen kunnen worden gebruikt om voorwaarden te combineren:

+ `en`{:class="block3operators"} - beide voorwaarden zijn waar:

```blocks3
if <<(x position) > (0)> and <(snelheid) > (50)>> then
think [Rustig aan]  
end
```

+ `of`{:class="block3operators"} -een van de voorwaarden is waar:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `niet`{:class="block3operators"} - de voorwaarde is onwaar:

```blocks3
if <not <(totaal) < (50)>> then
move (10) steps
end
```
