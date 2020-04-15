# fizzbuzz
Shortest fizzbuzzes I've been able to make

## PHP:
```php
for($i=0;$i<100;)echo''==($x=(++$i%3?'':'fizz').($i%5?'':'buzz'))?$i:$x,"\n"
```
fizzbuzz in php in 76 characters

```php
for($i=0;$i<100;)echo$x=(++$i%3?'':'fizz').($i%5?'':'buzz')?:$i,"\n"
```
fizzbuzz in php in 68 characters

```php
for(;$i<100;)echo$x=(++$i%3?'':fizz).($i%5?'':buzz)?:$i,"\n"
```
fizzbuzz in php in 60 characters, ignoring PHP warnings

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
for i in range(100):print(i%3//2*'fizz'+i%5//4*'buzz'or i+1)
```
fizzbuzz in 60 characters in python

```python3
for i in range(100):print(i%3//2*'fizz'+i%5//4*'buzz'or-~i)
```
fizzbuzz in 59 characters in python (thanks to my friend Johannes for pointing this one out)

```python3
i=0
while i<100:print(i%3//2*'fizz'+i%5//4*'buzz'or-~i);i+=1
```
fizzbuzz in 60 characters in python in 2 lines
