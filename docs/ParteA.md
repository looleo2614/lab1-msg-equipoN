#	Rol	Decisión	Estado	Lo que escribe el equipo
D1	Hipotecas	El subsidio semanal lo calcula Mortgage	Tomada	Principio GRASP y qué datos de Mortgage lo justifican
Respuesta: 

D2	Hipotecas	¿El subsidio y el aporte de la pareja se guardan como atributos al construir la hipoteca, o se calculan cada vez que se piden?	Abierta	Opción elegida y por qué
Respuesta:

D3	Inversiones	Investment está declarada final	Tomada, revisable	¿La mantienen así? Una ventaja y un riesgo
Respuesta: 

D4	Registro	¿Quién detecta un número de hipoteca repetido: RegisterMortgage o el repositorio?	Abierta	Opción elegida, principio y qué pasaría si mañana cambia el repositorio
Respuesta: 

D5	Integrador	EstimateFundsForWeek recibe MortgageRepository (una interfaz) y no InMemoryMortgageRepository	Tomada	Principio GRASP y qué gana el caso de uso con esa decisión
Respuesta: 

D6	Integrador	Las sumas sobre todas las hipotecas e inversiones están en métodos privados de EstimateFundsForWeek. ¿Se quedan ahí o pasan a un experto nuevo del dominio?	Tomada, revisable	Opción elegida y por qué
Respuesta: 
