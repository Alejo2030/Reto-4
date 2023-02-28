# Reto-4
Desarrollo de reto 4




1.Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo


°Algoritmo:(Numeros primos)
1. Realizar una lista del 2 al n
2. Marcar al 1 como número primo, no incluirlo en la lista J
3. Seleccionar al numero 2 como primo y eliminar sus multiplos.
4. Llevar una lista J que contenga los numeros ya seleccionados primos 
5. Tomar el siguiente numero n, si este no es multiplo de los numeros de la lista J, agregarlo a esta misma 
6. Tomar los numeros n de manera creciente
7. Repetir el 5.; si el numero es multiplo de algun numero de la lista J, no agregar el numero a la lista J
8. Repetir con cada numero n 











°Diagrama de flujo:









[![Mapa-primos.png](https://i.postimg.cc/wB7LqtH1/Mapa-primos.png)](https://postimg.cc/1g1fM38S)

°Pseudocodigo:










[![Pseudocodigo.png](https://i.postimg.cc/BbrpsQFP/Pseudocodigo.png)](https://postimg.cc/Cn4ks0mw)






2.Revise el procedimiento matemático para hallar raices cuadradas (son divisiones y restas), plantee el algoritmo en pseudocódigo y en diagrama de flujo.
Lista de pasos: Obtener raices cuadradas:

1. Separar en parejas de derecha a izquierda el radicando 
2. Obtener la raiz cuadrada de la primera pareja de izquierda a derecha 
3. El cuadrado de la raiz se resta con la primera pareja de la izquierda.
4. Bajar la siguiente pareja 
5. Duplicar la raiz en el siguiente renglon 
6. Hallar un digito especifico y agregarlo en el renglon.
7.  Multiplicar el digito obtenido por el numero creado en el segundo renglon.
8.  Restarle este produnto al grupo de parejas.
9.  Obtener un residuo.
10.  Elevar al cuadrado los numeros obtenidos 
11.  Sumar el residuo

°Pseudocodigo:



![Pseudocodigo raices cuadradas](https://user-images.githubusercontent.com/124615465/221888905-32c764b0-869a-46ef-8ab8-2b7e909f4474.png)





°Diagrama de flujo:

[![](https://mermaid.ink/img/pako:eNptVNFS2zAQ_JUbP8EM_EAeOgMkkAAhQPoAo_BwtY4gakuuLLWEwL93FcshhWYyk4t0u7e3d_a6KJ2WYlA8Vu5P-cQ-0PfhwhI-R3sTa0rj9unw8Bsdq7k07NmTWEIgz9ySFny9AEdM5vVXNOI1k1TkWZuSrXYPHdnxhuRkTWNebeHywmXA73vOSSnDnXjUxSeI31rzRkM181os--rf2tvKDzsA695opMZciqeKqeaV8wRJwWjWCb3TxId03pJSJhslJadq9iOI7ag8m1cqI2s0mfLTWeNNLZ4zKTmyEf9dvv0scLjh7OJTxNdrusy8AltsAFU25bpv_h4DWEaDHpxNDjfeldL2_l73Ld8pxs2LqTEp3qrtKGFCS_ADLvRK7oA768L7FKqjpRde8tc-XTLAbFs4Q_ZY0VzIS9iMPGf2PXdoaP3qzidTeqfHoJyoY37mjc2tQbtJeA_LaROknathbCpsmN9pMYlwAaZ7scsKlTPgHIALbEJVIV2bpQkONjdSmkdTOloRo-dl55dre7S0GX4B-KWaxiqYXBJ1Mk02xVHjNsd56iU8xGEnqcXY8CB8VnUJ2qm6lTZgnwWCUqPe6ViCl6tk3XO0we2sakZOgbzaLmR62KQ1OvarcIXr2XqUni0Tos57NMPpjaJRJb9TpzvjSj13utPqoWxIx22v8wbAWzWPNf-n1i0u53unxu4XBwUoajYaL5N1ul0U4UlqWRQDhJr9z0WxsO_I4xjcfGXLYhB8lIMiNpqDDA3GwHUxeOSqxaloGOyn3dtp85J6_wun6IuS?type=png)](https://mermaid.live/edit#pako:eNptVNFS2zAQ_JUbP8EM_EAeOgMkkAAhQPoAo_BwtY4gakuuLLWEwL93FcshhWYyk4t0u7e3d_a6KJ2WYlA8Vu5P-cQ-0PfhwhI-R3sTa0rj9unw8Bsdq7k07NmTWEIgz9ySFny9AEdM5vVXNOI1k1TkWZuSrXYPHdnxhuRkTWNebeHywmXA73vOSSnDnXjUxSeI31rzRkM181os--rf2tvKDzsA695opMZciqeKqeaV8wRJwWjWCb3TxId03pJSJhslJadq9iOI7ag8m1cqI2s0mfLTWeNNLZ4zKTmyEf9dvv0scLjh7OJTxNdrusy8AltsAFU25bpv_h4DWEaDHpxNDjfeldL2_l73Ld8pxs2LqTEp3qrtKGFCS_ADLvRK7oA768L7FKqjpRde8tc-XTLAbFs4Q_ZY0VzIS9iMPGf2PXdoaP3qzidTeqfHoJyoY37mjc2tQbtJeA_LaROknathbCpsmN9pMYlwAaZ7scsKlTPgHIALbEJVIV2bpQkONjdSmkdTOloRo-dl55dre7S0GX4B-KWaxiqYXBJ1Mk02xVHjNsd56iU8xGEnqcXY8CB8VnUJ2qm6lTZgnwWCUqPe6ViCl6tk3XO0we2sakZOgbzaLmR62KQ1OvarcIXr2XqUni0Tos57NMPpjaJRJb9TpzvjSj13utPqoWxIx22v8wbAWzWPNf-n1i0u53unxu4XBwUoajYaL5N1ul0U4UlqWRQDhJr9z0WxsO_I4xjcfGXLYhB8lIMiNpqDDA3GwHUxeOSqxaloGOyn3dtp85J6_wun6IuS)

