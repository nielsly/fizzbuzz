# fizzbuzz
Shortest fizzbuzzes I've been able to make

## PHP:
```php
for($i=0;$i<101;)echo(''==($x=(++$i%3?'':'fizz').($i%5?'':'buzz'))?$i:$x)."\n";
```
fizzbuzz with trailing spaces in php in 79 characters

```php
function fizzbuzz($n){for($i=0;$i<$n;)echo(''==($x=(++$i%3?'':'fizz').($i%5?'':'buzz'))?$i:$x).($i==$n?'':"\n");}
```
fizzbuzz function without trailing spaces in php in 113 characters

## Python 3:
```python3
for i in range(1,101):print((''if i%3else'fizz')+(''if i%5else'buzz') or i)
```
fizzbuzz in 73 characters in python (similar to the first PHP solution)

```python3
for i in range(1,101):print(((i%3==0)*'fizz'+(i%5==0)*'buzz')or i)
```
fizzbuzz in 66 characters in python

```python3
for i in range(1,101):print((i%3<1)*'fizz'+(i%5<1)*'buzz'or i)
```
fizzbuzz in 62 characters in python

```python3
for i in range(1,101):print(i%3//2*'fizz'+i%5//4*'buzz'or i)
```
fizzbuzz in 60 characters in python
