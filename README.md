# PHP Beautifier

A toolfor format and beautify the style of PHP code with my style.

### Input

```php
<?php
/* dfgdgdf gdfg */
for ($v = 7;$v <= 100 / 10;$v++) {
$b = $v;
$x = [];
for ($i = 1;$i <= $v;$i++) {
$x[] = $i;
}
for ($k = 3;$k <= ((floor($v - 1) / 2) + 1);$k++) {
$r = $k;
solve($x, $v, $b, $k, $r);
}
}
```


### Result (It has not completed yet)

```php
<?php
/* dfgdgdf gdfg */
for($v=7;$v<=100/10;$v++) {
    $b=$v;
    $x=[];
    for($i=1;$i<=$v;$i++) {
        $x[]=$i;
    }
    for($k=3;$k<=((floor($v-1)/2)+1);$k++) {
        $r=$k;
        solve($x,$v,$b,$k,$r);
    }
}
```
