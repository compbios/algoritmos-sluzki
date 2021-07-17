Algoritmo volumenareacilindro
	//para calcular el volumen se utiliza la funcion pi*radio^2*altura
	//para calcular el area se utiliza la funcion 2*pi*radio*(radio+altura)
	Escribir "Para calcular el volumen y el area de un cilindro, ingrese primero el valor del radio (r) y luego la altura (a)"
	Leer r
	Leer a
	//se aplica la formula para el volumen
	V <- ((r*r) * 3.1416) * a
	//se aplica la formula para el area
	A <- (2* 3.1416 *r * (r+a))
	Escribir "El volumen es: ", V
	Escribir "El area es: ", A	
FinAlgoritmo
