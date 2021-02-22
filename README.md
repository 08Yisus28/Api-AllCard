# API AllCard
_**URL API: https://allcard-backenpy.herokuapp.com/**_
_En este repositorio explicamos el uso de nuestra API del proyecto ALLCARD._

## Proyecto AllCard 🚀

_Este es un proyecto donde se abarcan la mayoria de necesidades de los procesos de bins o del nuevo carding
 en esta api tienes diversas opciones las cuales describiremos en la siguiente doocumentación._

### Pre-requisitos 📋

_Si quieres hacer pruebas de nuestra api puedes realizarlas desde PostMan, Insomnia Rest o en movil tambien tienes la opción de Rest Api Client. Todas estas opciones para poder simular un RestClient._

### Como usarla 🔧

_Para crear una tarjeta necesitas hacer una peticion tipo POST a la siguiente url: https://allcard-backenpy.herokuapp.com/ mandando como parametros el siguiente JSON._
```
{
	"bin": "4152xxx",
	"cantidad_tarjetas": 10,
	"mes": 10,
	"anio": 2025,
	"cvv": "Aleatorio"
}
```
_Los parametros disponibles son_

```
"ALT"
"alt"
"Aleatorio"
"ALEATORIO"
```

_Ejemplo:_
```
{
	"bin": "4152xxx",
	"cantidad_tarjetas": 10,
	"mes": "ALT",
	"anio": "alt",
	"cvv": "ALEATORIO"
}
```
_La cantidad de tarjetas máxima que puedes solicitar es de 500, pero recomendamos solo usar un maximo de 10_

## Más opciones ⚙️

_Que más opciones te ofrecemos._ 

### Extrapolacion por similitud

_Puedes extrapolar mediante este metodo._

```
Peticion tipo PSOST a la URL: https://allcard-backenpy.herokuapp.com/extrapolacion/similitud
Parametros para el JSON: 
{
	"live1": "6169166430898422",
	"live2": "6169169317891189"
}
```

### Extrapolacion por activacion

_Puedes extrapolar mediante este metodo._

```
Peticion tipo PSOST a la URL: https://allcard-backenpy.herokuapp.com/extrapolacion/activacion
Parametros para el JSON: 
{
	"live1": "6169166430898422"
}
```

### Extrapolacion por avanzada

_Puedes extrapolar mediante este metodo._

```
Peticion tipo PSOST a la URL: https://allcard-backenpy.herokuapp.com/extrapolacion/avanzada
Parametros para el JSON: 
{
	"live1": "6169166430898422",
	"live2": "6169169317891189"
}
```

### Extrapolacion por identificacion lógica

_Puedes extrapolar mediante este metodo._

```
Peticion tipo PSOST a la URL: https://allcard-backenpy.herokuapp.com/extrapolacion/identificacion-logica
Parametros para el JSON: 
{
	"live1": "6169166430898422",
	"live2": "6169169317891189"
}
```

### Extrapolacion por metodo bancario

_Puedes extrapolar mediante este metodo._

```
Peticion tipo PSOST a la URL: https://allcard-backenpy.herokuapp.com/extrapolacion/metodo-bancario
Parametros para el JSON: 
{
	"live1": "6169166430898422",
	"live2": "6169169317891189"
}
```

## Construido con 🛠️

_Esta API Rest esta escrita utilizando Flask como framework backend de Python. Y alojada en Heroku para pruebas._

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestro canal informativo [WhatsApp](https://chat.whatsapp.com/JP6sPo69L4Z1ssIMFv1pbW)

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **KimiNox** - *Trabajo Inicial* - [08Yisus28](https://github.com/08Yisus28)

---
⌨️ con ❤️ por [08Yisus28](https://github.com/08Yisus28) 😊
