Esistono diversi blocchi `operatore`{:class="block3operators"} a forma di esagono che possono essere utilizzati per verificare le condizioni nei blocchi `se`{:class="block3control"}, `se...allora`{:class="block3control"}, `attendi fino a quando`{:class="block3control"} e `ripeti fino a quando`{:class="block3control"} per prendere una decisione.

Gli operatori `>`{:class="block3operators"}, `<`{:class="block3operators"} o `=`{:class="block3operators"} verificano la relazione tra due valori o `variabili`{:class="block3variables"}:

+ Maggiore di:

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
end
```
+ Minore di:

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Uguale a:

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

Gli operatori `e`{:class="block3operators"}, `o`{:class="block3operators"} e `non`{:class="block3operators"} prendono decisioni logiche se:

+ `e`{:class="block3operators"} - entrambe le condizioni sono vere:

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end
```

+ `o`{:class="block3operators"} - una delle condizioni è vera:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `non`{:class="block3operators"} - la condizione è falsa:

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


