# Sprint3_Tasca_M3_T02
Info 

DataFrame Airlines Delay
La información resumida sobre la cantidad de vuelos puntuales, retrasados, cancelados y desviados aparece en el Informe mensual del consumidor de viajes aéreos del DOT, publicado aproximadamente 30 días después de fin de mes, así como en las tablas de resumen publicadas en este sitio web. BTS comenzó a recopilar detalles sobre las causas de los retrasos en los vuelos en junio de 2003. Las estadísticas resumidas y los datos sin procesar se ponen a disposición del público en el momento en que se publica el Informe del Consumidor de Viajes Aéreos.

Descripción columnas  
Unnamed: 0: Es una columna con un índice numérico de los registros.
Year: El año de la fecha del vuelo.
Month: El mes de la fecha del vuelo.
DayofMonth: El día del mes de la fecha del vuelo.
DayOfWeek: El día de la semana de la fecha del vuelo, donde 1 es lunes y 7 es domingo.
DepTime: La hora de salida real del vuelo.
CRSDepTime: La hora de salida programada del vuelo.
ArrTime: La hora de llegada real del vuelo.
CRSArrTime: La hora de llegada programada del vuelo.
UniqueCarrier: El código de identificación único de la aerolínea.
FlightNum: El número de vuelo.
TailNum: El número de cola de la aeronave.
ActualElapsedTime: Duración real del vuelo en minutos.
CRSElapsedTime: Duración del vuelo programado en minutos.
AirTime: El tiempo de vuelo en el aire en minutos.
ArrDelay: El retraso en la llegada en minutos. Un vuelo se cuenta como "a tiempo" si operó menos de 15 minutos después de la hora programada que se muestra en CRSElapsedTime.
DepDelay: El retraso en la salida en minutos.
Origin: El aeropuerto de origen del vuelo.
Dest: El aeropuerto de destino del vuelo.
Distance: La distancia del vuelo en millas.
TaxiIn: El tiempo de rodaje en la llegada en minutos.
TaxiOut: El tiempo de rodaje en la salida en minutos.
Cancelled: Indica si el vuelo fue cancelado (1) o no (0).
CancellationCode: El código de cancelación si el vuelo fue cancelado.
Diverted: Indica si el vuelo fue desviado a otro aeropuerto (1) o no (0).
CarrierDelay: El tiempo de retraso debido a la aerolínea en minutos.
WeatherDelay: El tiempo de retraso debido al clima en minutos.
NASDelay: El tiempo de retraso debido al Sistema Nacional de Aviación en minutos.
SecurityDelay: El tiempo de retraso debido a problemas de seguridad en minutos.
LateAircraftDelay: El tiempo de retraso debido a problemas con el avión en minutos.

