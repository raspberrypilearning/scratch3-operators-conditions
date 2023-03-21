Hay una serie de bloques `operadores`{:class="block3operators"} con forma de hexágono que se pueden usar para comprobar las condiciones en los bloques `si`{:class="block3control"}, `si...si no`{:class="block3control"}, `esperar hasta que`{:class="block3control"} y `repetir hasta que`{:class="block3control"} para tomar una decisión.

Los operadores `>`{:class="block3operators"}, `<`{:class="block3operators"} o `=`{:class="block3operators"} verifican la relación entre dos valores o `variables`{:clase="block3variables"}:

+ Mayor que:

```blocks3
if <(velocidad) > (50)> then
say [Desacelerar] for (2) seconds
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

Los operadores `y`{:class="block3operators"}, `o`{:class="block3operators"} y `no`{:class="block3operators"} toman decisiones lógicas si:

+ `y`{:class="block3operators"} - ambas condiciones son verdaderas:

```blocks3
if <<(x position) > (0)> and <(velocidad) > (50)>> then
think [Desacelerar]  
end
```

+ `o`{:class="block3operators"} - cualquiera de las condiciones es verdadera:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `no`{:class="block3operators"} - la condición es falsa:

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```
