There are a number of hexagon shaped `operator`{:class="block3operators"} blocks that can be used to check conditions in `if`{:class="block3control"}, `if...else`{:class="block3control"}, `wait until`{:class="block3control"}, and `repeat until`{:class="block3control"} blocks to make a decision.

The `>`{:class="block3operators"}, `<`{:class="block3operators"}, or `=`{:class="block3operators"} operators check the relationship between two values or `variables`{:class="block3variables"}:

+ Greater than:

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
end
```
+ Less than:

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Equal to:

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

The `and`{:class="block3operators"}, `or`{:class="block3operators"}, and `not`{:class="block3operators"} operators make logical decisions if:

+ `and`{:class="block3operators"} - both conditions are true:

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end
```

+ `or`{:class="block3operators"} -  either condition is true:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `not`{:class="block3operators"} - the condition is false:

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


