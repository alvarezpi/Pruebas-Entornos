![IES](file:///G:\Mi%20unidad\FP\cabecera-k-fondocolores2-nologos-cdc.png)
###### Pilar Alvarez

**Tasca-Depuracion1**

**1.** Qué hacen estas dos líneas de código???


```
String string2 = "string2";

string2= string2.substring(0, string2.length()-1); 

string2=string2+"1";  
```

<span style="color:blue">**R/** Devolver una subcadena. El valor del string2 con una posición menos, del final hacia atras.

**2.** Què valen les variables string1 i string2 abans d'executar el codi de comprovació següent?

<span style="color:blue">**R/** la variable string1 contiene la cadena string1 y la variable string2 contiene la cadena string2.

```
if(string1 == string2 ) {

System.out.println("SÓN IGUALS " + a );.

} else {

System.out.println("SÓN DIFERENTS");

}
```

**3.** Per què no funciona l'operador == ? Quin operador s'ha d'usar en lloc d'aquest?

<span style="color:blue">**R/** El == aunque es un operadore de comparación, este no se debe usar para los string ya que devolvera un error. Para string se debe usar .equals o .compareTo
La solución sería:

```
String string1="string1";

String string2="string2";.

if (string1.equals(string2)){

System.out.println("SON IGUALES " + a);

<span style="color:red">} else {

System.out.println("SON DIFERENTES");

}
```


**4.** La función2() està declarada com segueix:
```
public void funcion2() {

System.out.println("--------------------");

System.out.println("Aquesta és la funció 2");

System.out.println("Com faig la crida perquè funcione????");

}
```
<span style="color:blue">**R/**
