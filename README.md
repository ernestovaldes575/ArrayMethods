# Array Methods
Actividad que muestra el funcionamiento de los Array Methods, que son muy necesarios ya que son los que aligeran la carga de trabajo y reducen lineas de código.
# forEach
Este Array Method itera sobre los elementos de un arreglo. Siempre usamos un Arrow Function y dentro declaramos la funcionalidad que queremos que tenga.
```js
const frutas = ['manzana','platano','pera','mango'];
	frutas.forEach((fruta) => {
		console.log(fruta)
	})
//En consola se muestra: manzana, platano, pera, mango
```
Tambien nos ayuda a buscar elementos dentro de un arreglo. El forEach toma dos parámetros que son valor e indice, cuando solo tenemos el valor podemos eliminar los parentesis como en el siguiente ejemeplo. Más adelante mostraremos un ejemplo en donde contenga un valor y un indice.
```js
const dias = ['Lunes','Martes','Miercoles','Jueves','Viernes'];

	dias.forEach(dia => {
		if(dia === 'Sabado'){
			console.log('Si existe');
		}else{
			console.log('No Existe');
		}})
//Lo que imprime en consola: No existe
```
