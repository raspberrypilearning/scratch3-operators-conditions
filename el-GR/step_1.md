Υπάρχει ένας αριθμός από `τελεστές`{:class="block3operators"} μπλοκ εξαγωνικού σχήματος που μπορούν να χρησιμοποιηθούν για τον έλεγχο συνθηκών στα μπλοκ `εάν`{:class="block3control"}, `εάν...αλλιώς`{:class="block3control"}, `περίμενε ώσπου`{:class="block3control"}, και `επανάλαβε ώσπου`{:class="block3control"} για να παρθεί μία απόφαση.

Οι τελεστές `>`{:class="block3operators"}, `<`{:class="block3operators"}, ή `=`{:class="block3operators"} ελέγχουν τη σχέση μεταξύ δύο τιμών ή `μεταβλητών`{:class="block3variables"}:

+ Μεγαλύτερο από:

```blocks3
if <(speed) > (50)> then
say [Slow down] for (2) seconds
end
```
+ Λιγότερο από:

```blocks3
repeat until <(size) < (30)>
play sound [shrink v] until done
change (size) by (-1)
end
```
+ Ισούται με:

```blocks3
wait until <(timer) = (0)>
stop [all v]
```

Οι τελεστές `και`{:class="block3operators"}, `ή`{:class="block3operators"}, και `όχι`{:class="block3operators"} λαμβάνουν λογικές αποφάσεις εάν:

+ `και`{:class="block3operators"} - και οι δύο συνθήκες είναι αληθείς:

```blocks3
if <<(x position) > (0)> and <(speed) > (50)>> then
think [Slow down]  
end
```

+ `ή`{:class="block3operators"} - οποιαδήποτε συνθήκη είναι αληθής:

```blocks3
if <<(volume) < (50)> or <(volume) > (100)>> then
set [pitch v] effect to (25)
end
```

+ `όχι`{:class="block3operators"} - η συνθήκη είναι ψευδής:

```blocks3
if <not <(total) < (50)>> then
move (10) steps
end
```


