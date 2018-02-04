# algoritmos-1
## 1. ¿Cual es la complejidad de tiempo de la función example()?

```c++
int example(int n)
{
  int count = 0;
  for (int i = n; i > 0; i /= 2)
     for (int j = 0; j < i; j++)
        count += 1;
  return count;
}
```
es de complejidad o(n)

## 2. ¿Cual es la complejidad de tiempo de la función example2()?

```c++
void example2(int n, int arr[])
{
    int i = 0, j = 0;
    for(; i < n; ++i)
        while(j < n && arr[i] < arr[j])
            j++;
}
```
es de complejidad o(n^2)

## 3. ¿Cuál es la mejor complejidad de tiempo de bubbleSort?
es de complejidad o(n^2) debido a que el ordenamiento por burbuja no depende de que si la lista esta ordenada
sino de la cantidad de elemntos que tiene la lista
