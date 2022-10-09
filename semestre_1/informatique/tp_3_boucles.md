### Exercice 1
1.
`````python
for i in range(1, 6):
    print(i)
print('Partez !')
`````

2. 
`````python
for i in range(5, 0,-1):
    print(i)
print('Partez !')
`````
### Exercice 2
````python
for i in range (1,11):
    print(f'{i} X 7 = {i * 7}')
````
### Exercice 3
1.
`````python
n = int(input('Entrez le nombre de lignes : '))
for i in range(n+1):
    print(i * '*')
`````
2. 
````python
n = int(input('Entrez le nombre de lignes : '))

for i in range(n,0 ,-1 ):
    print((i-1) * ' ' + '*')
````
3. 
`````python
n = int(input('Entrez le nombre de lignes : '))
for i in range(n):
    print((2*i+1) * '*')
`````
### Exercice 4
1.
`````python
s = 0
for i in range(1,31):
    s += i
    print(f'{s}+{i}')
print(s)
`````
2. 
````python
s = 0
for i in range(1,21):
    s += i**2
    print(f'{s}+{i**2}')
print(s)
````
3. 
`````python
p = 1
for i in range(1,16):
    p *= i
    print(f'{p}X{i}')
print(p)
`````

4. 
`````python
p = 1
for i in range(1,11):
    print(f'{p}X{2*i+1}')
    p *= (2*i+1)

print(p)
`````

### Exercice 5
1. 
`````python
import random



def suite(a,n):
    if n == 0:
        x_0 = 1
        return x_0
    else:
        x = 1/2 * (suite(a, n-1) + a / suite(a, n-1))
        return x

if __name__ == "__main__":
    a = 1.5
    k = random.randint(0,20)
    for i in range(k):
        print(f'Voici X_{i} = {suite(a,i)}')
`````
### Exercice 6
`````python
import random
def suite(Uo ,n):
    if n == 0:
        return Uo
    elif suite(Uo, n-1) % 2 == 0:
        Un = suite(Uo, n-1) / 2
    else:
        Un = 3 * (suite(Uo, n-1)) +1

    return Un

if __name__ == "__main__":
    Uo = random.randint(1,100)
    k = 10
    for i in range(k):
        print(f'Voici U_{i} = {suite(Uo, i)}')
`````
### Exercice 7 fibonaci
`````python
def fibo(n):
    if n == 0:
        U = 0
        return U
    elif n == 1:
        U = 1
        return U
    else :
        U = fibo(n-1) + fibo(n-2)
        return U
`````
### Exercice 8
`````python
l = []
n = ?
for i in range (1 , n+1):
    if n % i == 0:
        l.append(i)
print(l)
print(len(l))
`````

### Exercice 9

`````python
import random
for i in range (11):
    print('\n')
    for j in range (11):
        print(f'{j} X {i} = {j * i}')



`````

### Exercice 10


