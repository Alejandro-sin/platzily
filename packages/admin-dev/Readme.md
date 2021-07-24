

## TAREAS:

- [x]  Crear paquete de admin en el monolito
- [x]  Crear rama Admin-ev
- []  Crear rama Admin-ev
- [ ]  Quitar del diagrama la sección de Core, ya que no la implementaremos.
- [ ]  Justificar lo de la decisión de la persistencia/databases. CAP theorem.
- [ ]  Evaluar la posibilidad de generar un id por link para poder identificar rápidamente según políticas si link ingiere las cosas.
- [ ]  Tener conversaciones con users/Links. Reglas de negocio sobre el alcance que tendremos. (Agendar reunion)
- [ ]  Hablar con equipo de Statistics y Users. Conversar desde queries hasta reglas.
- [ ]  Sistema autenticación, Roles , Preguntar a Core: ¿Como funcionará?

## PREGUNTAS :

1. ¿ Como se va a establecer las políticas? Si se pueden crear. ¿ Qué reporte damos del porqué se banea tal link o campaña?
2. ¿Como vamos a manejar tareas 
3. ¿Se banean campañas también? ¿Cuando se banea?
4. ¿A los cuantos bans de links se banean los usuarios?, Asignación de peso por bans.
5. enviar dm-SantI-Alexis-Omar:
    1. Setup: Cual sería nuestra primera línea de código para que todo se integre con [LEARNA](https://lerna.js.org/)
    2. ¿Tendremos nuestro propio monolito?
    3. ¿De tener este monolito como se conectará con el proyecto?

## BACKLOG:

## EPIC

- [Golang](https://platzi.com/backend-go/)
- Next

## REST-API

- API design.
    - End point to banner user by (id) x
    - End point to banner link (Id) x
    - End point to banner user by (id) x
    - End point to search campaing by id x
    - End point to search users by id x
    - End point to link by id x
    - Authentication/Authorization
    - Loggin/out
    - End point Statistic View.
    - End point links asociate to users
    - End point for campaings associate to users
    - End Point link details. (usesr, campiang, dates, links-short, metadata)
    - End point user details(name, links)

## DATA BASES

- Drivers to each DB (users/links)
- DTO show powerBI statisics.
- Posibility of create a databse for storing infomational data.

## STATISTIC:

- ¿How many users use the platform? (Clicks, time enlapse...)
- ¿How many links
- ¿How many links are created weekly?
- ¿How many of my users who access to the platform are converters as clients?
- ¿Cantidad de campañas por mes?
- ¿How many campaigns by month?
- ¿Views By Link Traffic?

## FRONT

- Set UP NEXT
- Material UI (Bootstrap)
    - Paleta de colores de UI platzily.
- Mockups. Views e Interface.
- Views Flow, give the logic of the application

## Consensos equipo.

## Git:

- Rama principal admin-dev.
    - Rama por tarea y luego hacer merge.
    - Nomenclatura:  admin-número de issue.