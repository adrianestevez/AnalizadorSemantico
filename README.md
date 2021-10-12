# Tarea 6. Analizador Semántico

Esta actividad consistirá en realizar el analizador semántico con lo que se había hecho en la actividad anterior (tanto analizador léxico como sintáctico). También en esta actividad se mostrará tanto los errores semánticos como el propio árbol sintáctico formado por dicho análisis.

Recordando, la gramática utilizada es la siguiente:

[compilador.xlsx](https://github.com/Erosval2101/Traductores_de_Lenguaje_II/files/5646517/compilador.xlsx)

### Código 1:
 
```sh
int main(){
float a;
int b;
int c;
c = a+b;
c = suma(8,9);
}
```

### Código 2:

```sh
int a;
int suma(int a, int b){
	return a+b;
}

int main(){
float a;
int b;
int c;
c = a+b;
c = suma(8.5,9.9);
}
```

## Resultados.

![Ejecucion1](https://user-images.githubusercontent.com/70926870/101234942-8aadd680-3689-11eb-834e-8ee2a4c2dbdb.PNG)

![Ejecucion2](https://user-images.githubusercontent.com/70926870/101234998-0ad43c00-368a-11eb-9393-2cb41edab703.PNG)

![Ejecucion3](https://user-images.githubusercontent.com/70926870/101235008-29d2ce00-368a-11eb-996f-5a293690a3bc.PNG)

![Ejecucion4](https://user-images.githubusercontent.com/70926870/101235023-5555b880-368a-11eb-9f56-057f371194aa.PNG)

![Ejecucion5](https://user-images.githubusercontent.com/70926870/101235034-7dddb280-368a-11eb-8ca0-e09655631891.PNG)

![Ejecucion6](https://user-images.githubusercontent.com/70926870/101235052-a2d22580-368a-11eb-8d48-c8a270498fe1.PNG)

![Ejecucion7](https://user-images.githubusercontent.com/70926870/101235068-c4331180-368a-11eb-932b-e9c9edd5409e.PNG)

![Ejecucion8](https://user-images.githubusercontent.com/70926870/101234941-8a154000-3689-11eb-9681-951e5c521c83.PNG)

![Ejecucion9](https://user-images.githubusercontent.com/70926870/101235089-fa709100-368a-11eb-9664-0b0f1fbf7a75.PNG)

![Ejecucion10](https://user-images.githubusercontent.com/70926870/101235099-170cc900-368b-11eb-8879-f5a1e53a0dfe.PNG)
 
![Ejecucion11](https://user-images.githubusercontent.com/70926870/101235167-bf229200-368b-11eb-93e0-26e3ebb20f00.PNG)

![Ejecucion12](https://user-images.githubusercontent.com/70926870/101235174-c21d8280-368b-11eb-9cb5-876a14ce2dc0.PNG)

![Ejecucion13](https://user-images.githubusercontent.com/70926870/101235173-c184ec00-368b-11eb-9c95-08799e57d556.PNG)

![Ejecucion14](https://user-images.githubusercontent.com/70926870/101235172-c0ec5580-368b-11eb-9df3-e88f59fff961.PNG)
