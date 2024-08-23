- Si en nuestra applicación necesitamos crear 2 Beans que sean del mismo objeto. Para que spring detecte cual pillar, podemos hacer las siguientes cosas:

1- Poniendo la anotación @Primary. En este caso crea la lista itemsFacture.

![](/src/main/resources/img/1.PNG)

2- Poniendo la anotación @Qualifier("el nombre del metodo del Bean")

![](/src/main/resources/img/2.PNG)

3- Y por último, poniendo el Bean por defecto. `se puede poner el nombre que quiera`

![](/src/main/resources/img/3.PNG)

![](/src/main/resources/img/4.PNG)