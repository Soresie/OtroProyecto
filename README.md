# Este es mi archivo README para entregar
## Expondremos toda la sintaxis general
### Esto es un archivo .md (Markdown)
#### Esto son encabezados
##### Sergio Orellan Sieira  
<br><br>
  
**Este texto esta en negrita**   
__Este también__       
<br>

*Este texto está en cursiva*   
_Este también_   
**Este texto esta en negrita y _esto en cursiva_** 

<br><br>

~~Este texto está tachado~~
<br>
> Este texto es una cita

   
<br><br>

Esto es un <sub>subíndice</sub>

Esto es un <sup>superíndice</sup>   
<br><br>

Esto es un bloque distintivo para código y poder copiarlo facilmente

```
git status
git add
git commit
```

Markdown no soporta colores, aunque estas sond sitintas formas de añadir color usando otros lenguajes:

Esto es un placeholder para el color naranja.
![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `#f03c15`

Esto es un placeholder para el color azul.
 ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) `#1589F0`

```diff
- Texto en rojo
+ Texto en verde
! Texto en naranja
# TExto en gris
@@ Texto en violeta @@
```
Tambien se pueden usar emojis:    
🔴
🟠
⚫
🟢
🟡    
<br><br>

Esto es como se crean links: [Documentación GitHub](https://docs.github.com/es). 




Asi se ve una foto:   
![gato](https://github.com/Soresie/OtroProyecto/assets/166688955/a3699a9d-1378-4475-9fb5-37a701cf42c3)    


Asi se vería una lista desordenada:

- Gato
* Perro
+ Conejo
- Cobaya

  <br><br>

   
Y asi una lista ordenada:
  
1.  Londres
2.  Tokio
3.  Berlín
4.  Oslo

<br><br>

Asi se hacen listas anidadas:    

1. Uno
   - Dos
     - Tres
       - Cuatro   
  
Asi se ve una lista de tareas:   
- [x] Completado
- [ ] En curso
- [ ] Pendiente   
   <br>
   
Asi se menciona a alguien:

@Soresie   
<br>   
   
Asi se usan emojis:   
:bowtie: 😄 😆 😊 😃     
   
Asi es una nota al pie[^1].

Esta es otra nota al pie[^2].

[^1]: Su referencia.
[^2]: Otra referencia.    

<br><br>   

> [!NOTE]
> Esto es una nota.

> [!TIP]
> Esto un consejo.

> [!IMPORTANT]
> Esto es una nota importante.

> [!WARNING]
> Esto es una advertencia.

> [!CAUTION]
> Esto es un mensaje de precaución.




Lo siguiente es un mensaje que no se ve en el Markdown(no se ve):
<!-- No se ve en Markdown -->   
<br><br>   



Esto es una tabla:   
| Esto es una  | Tabla |
| ------------- | ------------- |
| Celda1  | Celda2  |
| Celda3  | Celda4  |     



Tambien se puede formatear la tabla con estilos:    

| Esto es una  | Tabla |
| ------------- | ------------- |
| *Cursiva*  | **Negrita** |
| ***Negrita cursiva***  | ~~Tachado~~ |    


<br><br>
  
Esto es una sección contraida:    


<details>

<summary>Click para ver más</summary>

### Encabezado

Texto contraido. 

Tambien puedes poner más cosas, como código.

```java
System.out.println("Hello World");
```
</details>   
<br>

Mas funciones de código:   
``` solidity
// Remarcar sintaxis de codigo:
pragma solidity ^0.8.0;

contract HelloWorld {
    function hello() external pure returns (string memory) {
        return "Hello World!";
    }
}
```




   <br>    
Asi son las expresiones matemáticas (Ecuación de Schrödinger):

$$\frac{\hbar^2}{2m} \nabla^2 \Psi(\mathbf{r}) + V(\mathbf{r})\Psi(\mathbf{r}) = E\Psi(\mathbf{r})$$



