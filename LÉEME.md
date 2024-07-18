# Resultados de la Selección Nacional de Fútbol de Perú

> [Read in ENGLISH](README.md)

## Descripción
Después de un exhaustivo proceso de recopilación de datos, he creado esta base de datos lista para usar que contiene los resultados de cada partido de la selección nacional de fútbol de Perú, junto con detalles importantes para el análisis. Como gran aficionado al fútbol y apasionado por sus estadísticas, inicialmente recopilé estos datos para compartir gráficos y resúmenes con mis amigos. Ahora, quiero compartirlo con la comunidad de GitHub. Este repositorio también incluye un cuaderno de Python con ejemplos de uso.

## Contenido
Este conjunto de datos incluye los resultados de los partidos de la selección nacional de fútbol de Perú, desde su primer partido contra Uruguay el 1 de noviembre de 1927, hasta el partido más reciente según la última actualización. Cubre tanto partidos oficiales como amistosos, con tres excepciones específicas que no están incluidas (ver la sección 'Partidos no considerados' a continuación para más detalles). El archivo `peru_match_results.csv` contiene los siguientes campos:

- `match_id`: Comienza con M seguido del número de partido en orden cronológico.
- `date`: Fecha del partido.
- `rival`: Nombre del equipo contra el que jugó Perú.
- `rival_confederation`: Confederación a la que pertenece el rival.
- `peru_score`: Goles anotados por Perú en el partido.
- `rival_score`: Goles recibidos por Perú en el partido.
- `peru_awarded_score`: Goles anotados por Perú después de revisiones o sanciones (si las hay).
- `rival_awarded_score`: Goles recibidos por Perú después de revisiones o sanciones (si las hay).
- `result`: Resultado del partido (W: victoria, D: empate, L: derrota).
- `shootout_result`: Resultado de la definición por penales (si aplica).
- `awarded_result`: Resultado del partido después de revisiones o sanciones (si las hay).
- `tournament_name`: Nombre específico del torneo (ejemplo: Copa Mundial de la FIFA 2018).
- `tournament_type`: Tipo de torneo (ejemplo: Copa Mundial de la FIFA).
- `official`: Booleano que indica si el partido fue oficial.
- `stadium`: Nombre del estadio donde se jugó el partido.
- `city`: Ciudad donde se jugó el partido.
- `country`: País donde se jugó el partido.
- `elevation`: Altitud (sobre el nivel del mar) de la ciudad donde se jugó el partido.
- `peru_condition`: Indica si Perú jugó como local (home), visitante (away) o en campo neutral (neutral).
- `coach`: Nombre del entrenador del equipo peruano en el momento del partido.
- `coach_nationality`: Nacionalidad del entrenador.

## Partidos no considerados
Tres partidos específicos no fueron considerados en esta base de datos por las siguientes razones:

| Match date  | Rival         | Reason                                    |
|-------------|---------------|-------------------------------------------|
| 1988-03-26  | Canadá        | Peru jugó con equipo sub-19.              |
| 2011-06-28  | Senegal       | Senegal envió un equipo alternativo, posiblemente sub-23. |
| 2013-12-28  | País Vasco    | El País Vasco no es reconocido por la FIFA. |

## Provenance

Los datos fueron recopilados de varias fuentes, incluidas, pero no limitadas a, Sofascore, Google, Wikipedia, FIFA, perufootball.org, Transfermarkt, DeChalaca.com, Facebook, BESOCCER, 11v11.com, Partidos de la Roja, etc.

Todos los datos fueron recopilados manualmente mediante búsqueda en la web.

## License
Este proyecto está licenciado bajo CC BY-NC-SA 4.0. Consulte el archivo [LICENSE](LICENSE) para más detalles.
