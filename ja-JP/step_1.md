たくさんある六角形の形をした`演算`{:class="block3operators"}ブロックは、`もし`{:class="block3control"}、`もし...でなければ`{:class="block3control"}、`まで待つ`{:class="block3control"}、そして`まで繰り返す`{:class="block3control"}ブロックで判断する条件を確認するのに使うことができます。

`>`{:class="block3operators"}、`<`{:class="block3operators"}、または`=`{:class="block3operators"}演算子は、2つの値または`変数`{: class="block3variables"}の関係を確認します。

+ 大きい

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
end
```
+ 小さい

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ 等しい

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

`かつ`{:class="block3operators"}、`または`{:class="block3operators"}、および `ではない`{:class="block3operators"}演算子は、条件を結合するために使用することができます。

+ `かつ`{:class="block3operators"} - 両方の条件が真

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end
```

+ `または`{:class="block3operators"} - いずれかの条件が真

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `ではない`{:class="block3operators"} - 条件が偽

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


