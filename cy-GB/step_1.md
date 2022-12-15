Mae yna nifer o flociau `gweithredwr`{:class="block3operators"} siâp hecsagon sy'n gallu cael eu defnyddio i wirio amodau mewn blociau `os`{:class="block3control"}, `os...yna`{:class= "block3control"}, `aros hyd at`{:class="block3control"}, ac `ailadrodd hyd at`{:class="block3control"} er mwyn gwneud penderfyniad.

Mae'r gweithredwyr `>`{:class="block3operators"}, `<`{:class="block3operators"}, neu `=`{:class="block3operators"} yn gwirio'r berthynas rhwng dau werth neu `newidyn`{: class="block3variables"}:

+ Mwy na:

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
end
```
+ Llai na:

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Yn hafal i:

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

Mae'r gweithredwyr `a`{:class="block3operators"}, `neu`{:class="block3operators"}, a `nid`{:class="block3operators"} yn gallu cael eu defnyddio i gyfuno cyflyrau:

+ `a`{:class="block3operators"} - mae'r ddau amod yn wir:

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end
```

+ `neu`{:class="block3operators"} - mae'r naill amod neu'r llall yn wir:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `nid`{:class="block3operators"} - mae'r amod yn anwir:

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


