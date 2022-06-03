# Practica Contador e Inputs

### Parte 1 (creacion de logica)

- Clonar este repo e instalar sus dependencias

```
git clone "linkDelRepo"
cd "nombreDelProyecto"
npm i
```

- En App crear un input number y dos botones, un "-" y un "+".
- Crear un estado que funcione de contador, y agregar los respectivos eventos de restar y sumar a los botones.
- El numero del input se debe actualizar acorde a la ejecucion de los eventos.

### Parte 2 (componetizar)

- Crear un componente Count que reciba como propiedades:
    - "min" que sera el numero inicial del input y el minimo.
    - "max" que sera el tope maximo del contador.
    - Si el usuario llega al min o al max, deshabilitar el boton que corresponda.
- Tomar la logica armada previamente y pasarla al componente Count reemplazando por las props segun corresponda.

### Parte 3 (elevando el estado)

- En App crear un nuevo estado con valor inicial en false.
- Pasar por props el setter al Count.
- En Count, si el usuario llego al maximo del contador, cambiar el valor del estado boolean de App a true.
- Si el usuario llega al maximo pero vuelve a restar el contador, el estado boolean debe volver a false.
- En App, si el estado es true renderizar una alerta (estilar algo sencillo con un span o un p) que le indique al usuario que llego al maximo del contador. Si el estado es false no se debe ver nada.