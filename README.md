# Trabajo Parcial Equipo Dinamita
### Integrantes:
- Andre Elliot Escalante Bueno
- Diego Fernando Meléndez Marín
- Leonardo Leoncio Bravo Ricapa
- Jhamil Brijan Peña Cardenas
- Alejandra Gallo Riofrio

## Objetivo del Trabajo:
  Realizar un analisis EDA sobre el dataset hotel_bookings.csv. 
  Para esto se realizo la limpieza de datos utilizando el lenguaje R reemplazando los datos faltantes y atipicos mientras se mantenia un margen de error de menos del 4%.
  Despues de este proceso se realizo el analisis utilizando las funciones de graficacion del lenguaje R.

## Descripcion del Dataset 

  El dataset consta de 32 columnas con 119390 filas de datos.
  Las variables que contempla son:
  - Hotel
  - ADR
  - Adults
  - Agent
  - ArrivalDateDayOfMonth
  - ArrivalDateMonth
  - ArrivalDateWeekNumber
  - ArrivalDateYear
  - AssignedRoomType
  - Babies
  - BookingChanges
  - Children
  - Company
  - Country
  - CustomerType
  - DaysInWaitingList
  - DepositType
  - DistributionChannel
  - IsCanceled
  - IsRepeatedGuest
  - LeadTime
  - MarketSegment
  - Meal
  - PreviousBookingsNotCanceled
  - RequiredCardParkingSpaces
  - ReservationStatus
  - ReservationStatusDate 
  - ReservedRoomType
  - StaysInWeekendNights
  - StaysInWeekNights
  - TotalOfSpecialRequest

Title: “Hotel booking demand datasets”
Author: Nuno Antonio, Ana de Almeida, Luis Nunes
Source: https://doi.org/10.1016/j.dib.2018.11.126
License: CC BY 4.0

## Conclusiones
El análisis exploratorio de datos (EDA) realizado sobre el conjunto de datos "Hotel Booking Demand" permitió extraer varios hallazgos importantes después de un proceso riguroso de limpieza de los datos. Uno de los principales desafíos encontrados fue la presencia de valores faltantes en varias columnas importantes, como "country", "agent" y "company". El código mostró que se manejaron estos valores mediante la imputación de la moda en el caso de "country" y la eliminación de las columnas "agent" y "company", que presentaban demasiados datos faltantes. Este proceso permitió obtener un conjunto de datos más limpio y robusto para el análisis posterior.

También se observó la necesidad de manejar valores atípicos, particularmente en la columna de tarifas diarias promedio (ADR), que contenía outliers significativos. Estos outliers fueron detectados y eliminados utilizando el rango intercuartílico (IQR), lo cual mejoró la calidad del análisis al proporcionar una visión más precisa de las tarifas de los hoteles. En cuanto al tiempo de anticipación de las reservas (lead_time), se evidenció una variabilidad considerable, con algunos clientes planificando sus estancias con muchos meses de antelación, mientras que otros realizaban reservas de última hora. Esta variabilidad sugiere la necesidad de que los hoteles adopten estrategias flexibles para captar ambos tipos de clientes.

Otro hallazgo clave fue la tasa de cancelación, que mostró diferencias entre los tipos de hotel. Los hoteles urbanos experimentaron un mayor número de cancelaciones en comparación con los resorts, lo que puede estar relacionado con la naturaleza del cliente urbano, que tiende a realizar reservas más flexibles o de última hora. Esta información puede ser valiosa para que los hoteles ajusten sus políticas de cancelación y tarifas para mitigar pérdidas económicas.

Adicionalmente, el análisis bivariado mostró una clara relación entre el tipo de hotel y la tarifa diaria promedio (ADR). Los hoteles tipo resort generalmente ofrecieron tarifas más altas que los hoteles urbanos, lo que está en línea con las expectativas, ya que los resorts suelen atraer a un perfil de cliente dispuesto a gastar más en experiencias completas. Esto puede ayudar a los hoteles a ajustar sus precios y promociones según la temporada y el perfil del cliente.

## Licencia
Este trabajo esta licenciado bajo el estandar CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/)

