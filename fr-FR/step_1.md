Il existe un certain nombre de blocs de forme hexagonale `operateur`{:class="block3operators"} qui peuvent être utilisés pour vérifier les conditions dans les blocs `si`{:class="block3control"}, `si...sinon`{:class= "block3control"}, `attendre jusqu'à ce que` {:class="block3control"} et `répéter jusqu'à ce que`{:class="block3control"} pour prendre une décision.

Les opérateurs `>`{:class="block3operators"}, `<`{:class="block3operators"} ou `=`{:class="block3operators"} vérifient la relation entre deux valeurs ou `variables`{:class="block3variables"} :

+ Supérieur à :

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
end
```
+ Inférieur à :

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Égal à :

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

Les opérateurs `et`{:class="block3operators"}, `ou`{:class="block3operators"} et `non`{:class="block3operators"} prennent des décisions logiques si :

+ `et`{:class="block3operators"} - les deux conditions sont vraies :

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end
```

+ `ou`{:class="block3operators"} - l'une ou l'autre des conditions est vraie :

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `non`{:class="block3operators"} - la condition est fausse :

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


