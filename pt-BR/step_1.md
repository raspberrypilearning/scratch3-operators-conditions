Existem vários blocos de `operador`{:class="block3operators"} em forma de hexágono que podem ser usados para verificar as condições em `if`{:class="block3control"}, `if...else`{:class="block3control"},`espere até`{:class="block3control"}, e `repita até`{:class="block3control"} blocos para tomar uma decisão.

Os operadores `>`{:class="block3operators"}, `<`{:class="block3operators"}, ou `=`{:class="block3operators"} verificam o relacionamento entre dois valores ou `variáveis`{:class="block3variables"}:

+ Maior que:

```blocks3
if <(velocidade) > (50)> then
say [Diminuir a velocidade] for (2) seconds
end
```
+ Menor que:

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Igual a:

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

Os operadores `e`{:class="block3operators"}, `ou`{:class="block3operators"}, e `não`{:class="block3operators"} podem ser usados para combinar condições:

+ `e`{:class="block3operators"} - ambas as condições são verdadeiras:

```blocks3
if <<(x position) > (0)> and <(velocidade) > (50)>> then
think [Diminuir a velocidade]  
end
```

+ `ou`{:class="block3operators"} - qualquer uma das condições é verdadeira:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `e`{:class="block3operators"} - ambas as condições são verdadeiras:

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


