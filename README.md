# tarea-herencia-002

En el presente proyecto, usted debe subir los archivos en lenguaje de programación JAVA 

## Problemática 

#paquete personal
#clase Persona
	atributos:	
			nombres
			apellidos
			edad
			cedula

# clase Trabajador - hereda de Persona
	atributos:
			costo_seguro
			horas_trabajadas
			costo_por_hora
	métodos:
			obtener_sueldo ((horas x costo_hora)+costo_seguro)
					

# clase Ejecutivo - hereda de Persona
	atributos:
			sueldo_mensual


#paquete laempresa
#clase Empresa
	atributos:
			nombre
			siglas
			ciudad
			trabajadores tipo Arreglo Trabajador
			ejecutivos tipo Arreglo Ejecutivo
			
# clase EmpresaPublica - hereda de Empresa
	atributos:
			ventas_mensual_fijo
	métodos:
			obtener_monto_total_sueldos (entre los trabajadores y ejecutivo)
			obtener_estado_empresa (si hay ganacia o pérdida en el mes, tomando en consideración monto total de sueldos y ventas mensual fijo)



Para todas las clases anteriores crear constructores, métodos establecer y obtener por cada atributo y sobrescribir el método toString

# clase Principal
			método main
				- Crear un objeto EmpresaPrivada, que genere el siguiente reporte:
				
				Empresa: Compra y Venta Ministerio de Educación
				Siglas: MinEduc
				Ciudad: Quito
				Ventas: $ 10000
				Lista Trabajadores:
					
				 	1) 	Ana Luisa Velez Alcivar
						30 años de edad
						CI: 12903939
						Seguro: $100
						Horas Trabajadas: 40
						Valor x Hora: $ 10
						Sueldo: 500
					2) 	Mario Anibal Vela Narvaez
						35 años de edad
						CI: 212889
						Seguro: $100
						Horas Trabajadas: 50
						Valor x Hora: $ 10
						Sueldo: 600
					3) 	José Luis Andrade
						31 años de edad
						CI: 198734
						Seguro: $100
						Horas Trabajadas: 60
						Valor x Hora: $ 10
						Sueldo: 700
					4) 	Luis Marcelo Bolaños
						38 años de edad
						CI: 567890
						Seguro: $100
						Horas Trabajadas: 70
						Valor x Hora: $ 10
						Sueldo: 800
				
				Lista Ejecutivo:
					
				 	1) 	Marco Anibal Gomez G
						32 años de edad
						CI: 145678
						Sueldo: 1500
					2) 	Xavier J Arreaga M
						35 años de edad
						CI: 65431
						Sueldo: 1600
					3) 	José Luis Caicedo
						34 años de edad
						CI: 198713
						Sueldo: 1700
						
				Sueldos a pagar por la empresa es:  7400.
				La empresa tiene una GANANCIA de 2600
