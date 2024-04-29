Parcial 2: Inteligencia Artificial - Algoritmos Genéticos

- Carlos Mario Perdomo Ramos
- Cristian David Quinayas Rivera
- Daniel Fernando Solarte Ortega

# Algoritmo genético para planificar el tráfico de llegadas de vuelos en un aeropuerto

Para cada n vuelos se dispone de un TEL (Tiempo Estimado Llegada) de las m pistas disponibles. El tiempo planificado al asignar un vuelo a una pista no puede ser anterior que el correspondiente TEL.

## Tipos de aviones
- Pesado (W)
- Grande (G)
- Pequeño (P)

Cuando se asigna un vuelo a una pista, el retardo resultante se define como la diferencia entre el tiempo de llegada asignado (TLA) y el menor TEL de ese vuelo en todas las pistas.

Utilizaremos, entre otros, los siguientes datos de prueba:

Identificadores de vuelo IV: (UA138, UA532, UA599, NW358, UA2987, AA128, UA1482, NW357, AA129, UA2408, UA805, AA309);

Para los que los correspondientes tipos de avión (TV) vienen dados por la lista: TV = (W,G,W,W,P,W,G,W,W,P,W,G)