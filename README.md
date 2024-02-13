# Clase Date() JavaScript

Permite obtener datos sobre la fecha, como día, hora, minuto, mes, año, etc.

## 

* **getFullYear() ->** muestra el año en curso; el año completo

```javascript
const fecha = new Date();
let anio = fecha.getFullYear();
console.log(anio)
```

* **getMonth() ->** muestra el mes en curso; un numero entre 0 y 11 según el mes correspondiente; 0 será enero y 11 diciembre.

```javascript
const fecha = new Date();
let mes = fecha.getMonth();
console.log(mes)
```

* **getDate() ->** muestra el día del mes en curso; un numero entre 1 y 31 según corresponda.

```javascript
const fecha = new Date();
let dia = fecha.getDate();
console.log(dia)
```

* **getHours() ->** muestra la hora actual; un numero entre 0 y 23 según corresponda.

```javascript
const fecha = new Date();
let hora = fecha.getHours();
console.log(hora)
```

* **getMinutes() ->** muestra el minuto actual; un numero entre 0 y 59 según corresponda.

```javascript
const fecha = new Date();
let minuto = fecha.getMinutes();
console.log(minuto)
```

* **getSeconds() ->** muestra el segundo actual; un numero entre 0 y 59 según corresponda.

```javascript
const fecha = new Date();
let segundo = fecha.getSeconds();
console.log(segundo)
```

* **getDay() ->** muestra el día de la semana; un numero entre 0 y 6 siendo 0 el domingo y 6 el sábado.

```javascript
const fecha = new Date();
let diaSemana = fecha.getDay();
console.log(diaSemana)
```

