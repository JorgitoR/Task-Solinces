Tareas de Solinces.

De React busques una librería de Javascript que renderice gráficas o diagramas estadísticos.
- Las librerias que podemos utilizar para graficar son las siguientes: d3js, chart.js

Definir los parámetros que la librería necesita para renderizar la gráfica
- Los parametros que necesitamos son: labels[x] data[y]

Estructura del Json

```json 
const all_instituciones = [

	{

	"institucion":"La union",
	"SEDE":[
		{
		"sede":"A",
		"jornada":"M",
		"grado":5,
		"Alumnos":[{
			"mujeres":10,
			"hombres":20
			}]
		},

	{
		"sede":"B",
		"jornada":"M",
		"grado":5,
		"Alumnos":[
			{

			"mujeres":10,
			"hombres":20
			}
		]
	}
	]

	}
]

const per_year_per_institucion = [{
	
	"year":2020,
	"institucion":"La Union",
	"SEDE":[
		{
		"sede":"A",
		"jornada":"M",
		"Alumnos":[{

			"mujeres":100,
			"hombres":208

		}]
		
		},

		{
		"sede":"B",
		"jornada":"T",
		"Alumnos":[{

			"mujeres":107,
			"hombres":205

		}]
		
		},


	],
	
}]

const per_grado = [{
	
	"grado": "5",
	"institucion":"la union",
	"sede":"A",
	"Alumnos":[
		{

		"mujeres":10,
		"hombres":15

		},

		{
			"inactivos":4,
			"activos":25,
		}
	]


}]

const por_sede = [{
     
    "sede":"A",
    "institucion":"la union",
    "jornada":"M",
    "grado":"7",
	"Alumnos":[
		{

		"mujeres":10,
		"hombres":15

		},

		{
			"inactivos":3,
			"activos":25
		}
	]

}]


const por_institucion = [{

	"id":2,
	"institucion": "la union",
	"sede":"A",
	"jornada":"M",
	"grado":"7",
	"Alumnos":[
		{

		"mujeres":10,
		"hombres":15

		},
		{

		"inactivos":3,
		"activos":25
		}
	]

}]

```


<img align="left" alt="Generar reportes" width="90%" src="https://i.ibb.co/VvyXTHg/Whats-App-Image-2021-05-25-at-2-47-51-PM-1.jpg" />
<img align="left" alt="Generar reportes" width="90%" src="https://i.ibb.co/9hjWZPg/Whats-App-Image-2021-05-25-at-2-48-11-PM-1.jpg" />


