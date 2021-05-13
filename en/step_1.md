There are a number of hexagon shaped `operator`{:class="block3operators"} blocks that can be used to check conditions in `if`{:class="block3control"}, `if...else`{:class="block3control"}, `wait until`{:class="block3control"}, and `repeat until`{:class="block3control"} blocks to make a decision. 

The `greater than`{:class="block3operators"}, `less than`{:class="block3operators"}, or `equal to`{:class="block3operators"} operators check the relationship between two values or `variables`{:class="block3variables"}:

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
end

wait until <(timer) < (0)>
stop [all v]

repeat until <(size) = (300)>
play sound [grow v] until done
change (size) by (1)
end
```

The `and`{:class="block3operators"}, `or`{:class="block3operators"}, and `not`{:class="block3operators"} operators make logical decisions if:
+ `and`{:class="block3operators"} - both conditions are true 
+ `or`{:class="block3operators"} -  either condition is true
+ `not`{:class="block3operators"} - the condition is false

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end

if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end

if <not <(total) < (50)>> then
move (10) steps
end
```


