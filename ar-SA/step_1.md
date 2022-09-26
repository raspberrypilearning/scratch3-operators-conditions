يوجد عدد من المقاطع البرمجية (اللبنات البرمجية) ذات الشكل السداسي `عامل  رياضي`{:class="block3operators"} المقاطع البرمجية التي يمكن استخدامها للتحقق من الشروط في `إذا`{:class="block3control"} ، `إذا ... وإلا`{:class="block3control"} ، `انتظر حتى`{:class="block3control"} ، و المقطع البرمجي `كرر حتى`{:class="block3control"} لاتخاذ قرار.

تتحقق العمليات الرياضية `>`{:class="block3operators"} أو `<`{:class="block3operators"} أو `=`{:class="block3operators"} من العلاقة بين قيمتين أو `متغيرات`{:class="block3variables"}:

+ أكبر من

```blocks3
if <(سرعة) > (50)> then
say [ابطئ] for (2) seconds
end
```
+ أقل من

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ يساوي

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

الـ `و`{:class="block3operators"}, `أو`{:class="block3operators"}, و `ليس`{:class="block3operators"} هي عمليات تستخدم لدمج الشروط المنطقية:

+ `و`{:class="block3operators"} - كلا الشرطين صحيحان:

```blocks3
if <<(x position) > (0)> and <(سرعة) > (50)>> then
think [ابطئ]  
end
```

+ `أو`{:class="block3operators"} - احد الشرطين صحيح:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `ليس`{:class="block3operators"} - الشرط خاطئ:

```blocks3
if <not <(المجموع) < (50)>> then
move (10) steps
end
```
