# UY_new
*New Uruguayan Hierarchical Grid*, La Nuevo Grilla Jerárquica Uruguaya.

## Grilla e sus geocódigos

* **Grilla científica**:  conjunto de 40 grades organizadas hierarquicamente por tamanho de célula, de 131 km a 4 metros. Cada uma de suas células pode ser identificada por um código base16h.

* **Grilla postal**: subconjunto com da grilla científica com 7 grades. Cada uma de suas células pode ser identificada por um código base32, mais compacto que o científico, porém representando as mesmas c

## Geocódigos postales

<img align="right" width="400" src="https://user-images.githubusercontent.com/1651447/193488479-8c8b9923-31e8-4dc9-b10c-df2b0b35874d.png" />

Todo código postal es relativo a un departamento, capital departamental o municipio. La relación puede ser contextual (por ejemplo residentes hablando)  o explícita &mdash; por el geocódigo de jurisdicción nominal. 

A Uruguay se le asignó  en el contexto [ISO 3166](https://en.wikipedia.org/wiki/ISO_3166) el geocódigo [`UY`](https://en.wikipedia.org/wiki/ISO_3166-2:UY). Las subdivisiones nominales de UY se expresan mediante una jerarquía de abreviaturas separadas por un guión.

Por ejemplo [`UY-CO-ColoniaSacramento`](https://osm.codes/UY-CO-ColoniaSacramento) y [`UY-RV`](https://osm.codes/UY-RV) son geocódigos nominales válidos. O geocódigo postal completo [`UY-CO-ColoniaSacramento~4D8DM`](https://osm.codes/UY-CO-ColoniaSacramento~4D8DM) representa un cuadrado de 4 metros de lado.

O primeiro de `UY-CO-ColoniaSacramento` é um índice variando de zero a 15, representafo por dígito hexadecimal. Por exemplo, `UY-CO-ColoniaSacramento~4` ou simplesmente `.4`, com o ponto indicando que é relativo. Abaixo os primeiros dígitos válidos de Colonia Del Sacramento:

![image](https://user-images.githubusercontent.com/1651447/193492339-be3e2f38-1620-4f40-8140-104577a43305.png)

em seguida cada uma dessas células de cobertura do município é subdividida em 32, resultando no segundo dígito:

![image](https://user-images.githubusercontent.com/1651447/193484824-287e73d8-f3df-4150-ab14-954c8bebd063.png)

Foi destacado acima o `4J`, e abaixo o `4D` que doi subdividido até chegar no `4D8DM`.

O Geocódigo postal [UY-CO-ColoniaSacramento\~**4D8DM**](http://osm.codes/UY-CO-ColoniaSacramento~4D8DM), um quadrado de 4 m, passível de ser utilizado como código postal e como localizador de uma residência urbana.

## Geocódigos científicos

....

## Grade L0 de cobertura

Grade rotulada conforme **geocódigos postais**

![image](https://user-images.githubusercontent.com/1651447/193483610-c90fc5aa-1977-46a7-9a8c-9ae81a880b1e.png)

A mesma grade L0 agora rotulada conforme **geocódigos científicos**:

![image](https://user-images.githubusercontent.com/1651447/193483969-0807eb8f-7e37-4c0c-9a29-05afceb2a4f0.png)

As células da grade L0 podem podem ser divididos em 32, mas na grade científica recebem geocódigos de 3 dígitos neste caso:
![image](https://user-images.githubusercontent.com/1651447/193484255-abb3c13f-bcb4-43d1-94aa-06feb9be1aac.png)

As células da grade L0 divididas em 16 células menores, expressas através da base16:

![image](https://user-images.githubusercontent.com/1651447/193484160-bb040999-c12c-4d47-9365-ad12fd3b3073.png)


----

