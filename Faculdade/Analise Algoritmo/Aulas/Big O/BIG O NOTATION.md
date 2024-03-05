> Existe para avaliar o desempenho de um algoritmo ao decorrer do tempo, é uma das técnicas para análise de algoritmos e desempenho. 

  > Não ficar atrelado a máquina, olhar para o código 
  
> Notação O: Pior cenário possível
> Notação Ω: Melhor cenário possível 

> Quando usar: Comparação de um ou mais algorítmos 

> Como ele vai se comportar com a quantidade de dados que vai entrando pra ele

> Operações x Elementos

![[1_nlogn.png]]
### Introdução 
> Quanto maior o conjunto de dados, maior o tempo de processamento, um exemplo claro seria o *bubble sort*, o qual roda ^2 o tamanho da array, e por isso é ineficiente. 


```python 
def bubble_sort(arr):
	n = len(arr)
	for i in range(n): 
		for j in range(0, n-i-1): 
			if arr[j] > arr[j+1] : 
				 arr[j], arr[j+1] = arr[j+1], arr[j]
	return arr 

arr = [64,34,21,55,66,33,99,12,1,11]
print("Array Original: ", arr)
print("Array Ordenada: ", bubble_sort(arr))  
``` 
![[render.png]]
<sup><sub>Equação que descreve o Bubble Sort</sub></sup>



### Pontos a pesquisar 
* análise assintótica e limites
* função _quasilinear_, ou _linearítica_
* master theorem 
* ir ver mais a fundo o Big O 