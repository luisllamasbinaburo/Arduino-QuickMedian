# Librería Arduino QuickMedian
Librería para Arduino que realiza el cálculo rápido de la mediana de un array en Arduino aplicando el algoritmo QuickSelect modificado por Wirth. <br />
Más información https://www.luisllamas.es/libreria-arduino-quickmedian/

## Instrucciones de uso
La librería QuickMedian dispone de un único método estático para el cálculo de la mediana. No es necesario, por tanto, instanciar un objeto.

Se usan templates para que funcionen con distintos tipos de variables (int, long, float…). La librería incorpora dos ejemplos, uno para int y otro para float.

Para el cálculo de la mediana de un vector se emplea la función GetMedian

```c++
int med = QuickMedian<int>::GetMedian(items, numItems);
```


## Ejemplos
La librería QuickMedian incluye los siguientes ejemplos para ilustrar su uso.
* QuickMedianInt: Ejemplo de uso para variables integer.
* QuickMedianFloat: Ejemplo de uso para variables float.
