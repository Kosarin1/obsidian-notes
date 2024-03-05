a) [1, 3, 6, 10, 15, 21, 28, 36, 45, 55]

b)
Na fórmula abaixo, vemos o comportamento da equação. Sendo `n` = `accumul_acelerator`, vemos que para cada ponto de *i* temos associado a ele uma soma na qual o resultado é a soma do acelerador com i, fazendo com que quanto mais elementos, maior o custo de processamento e maior será os valores resultantes da aceleração
![[Pasted image 20240222210551.png]]


c) O desempenho do algoritmo mostrou uma curvatura no final, se considerássemos os próximos valores do algoritmo, veríamos uma curva inclinada, **contudo**, não deve ser confundida com uma função exponencial. 


d)

e)
A função se assemelha com uma função exponencial, contudo, não pode ser definida dessa forma pela sua fórmula. Em termos de complexidade de algoritmo, o algoritmo abaixo apresenta complexidade linear.

```python
  acumul_acelerate = 0 # c1 t1 

    for i in range(1, n+1): #c2 t2 n
        acumul_acelerate = acumul_acelerate + i #c3 t3 n 

    return acumul_acelerate # c4 t4 1 
```
![[Pasted image 20240222211607.png]]

