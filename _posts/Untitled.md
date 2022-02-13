```python
lambda a:a**2

f = lambda a:a**2
```


```python
f(4)
```




    16




```python
f(2)+f(3)
```




    13




```python
f(2)+2*f(3)
```




    22




```python
a = lambda b:b+2

type(a(3))
```




    int




```python
c = lambda d,e,g:d+e+g
c(1,2,3)

type(c(1,2,3))
```




    int




```python
v=(2,3)
type(v)
```




    tuple




```python
def add_function(*args):
    result = 0
    print(f'args의 타입: {type(args)}')
    for arg in args:
        print(arg)
        result += arg
    print('==='* 5)
    print(f'sum: {result}')
    
add_function(1,2,5,9)
```

    args의 타입: <class 'tuple'>
    1
    2
    5
    9
    ===============
    sum: 17
    


```python
def ss(*d):
    res=0
    for a in d:
        res -= a
    return res


print(ss(1,2,5))
```

    -8
    


```python
def sampling(args: tuple):
    # 튜플로 매개변수를 감쌉니다.
    z_mean, z_log_var = args
    
    return 
```


```python

```
