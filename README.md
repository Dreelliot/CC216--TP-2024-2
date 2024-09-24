# Trabajo Parcial Equipo Dinamita
### Integrantes:
- Andre Elliot Escalante Bueno

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

Link al documento original: https://pdf.sciencedirectassets.com/311593/1-s2.0-S2352340918X00079/1-s2.0-S2352340918315191/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJv//////////wEaCXVzLWVhc3QtMSJHMEUCIAt1TNrpFJbtw7RoKfqvwF6ZuVeQQbJywFKkjEu0GMgwAiEAuObsb9nu83lQocmIZ3SbMmzC5wIXi8TSnMLKJXWfzj0qvAUI1P//////////ARAFGgwwNTkwMDM1NDY4NjUiDHV95npAzGhBieU//SqQBUBIKiPp06YLLHM0tTgGe7eySOlX/95M6Fjq/u4G7zItRobRD6lovwsRNZczgCAasXjcISxE0evZL+wsElhikaOI6uUUNITccvms6AtBoNMWq9mGmXL6QDDGQZ2D+n5wRwEbYqlq8FP+rmZm82SvbeNcnGoxNojftuLRPwiEXqjF/hYvwQoExqo6hcWxXF/fkVmhn8V61UJPWqRde88IauT0hqd55lL5+fLteLXz58pyprQX8qr1l0io5UnAsT2N1RUVnyLB9ILXCkWlAeKntgFiX9cwtUAWPKPwYP2i6jAYVk+9S5RkBBX808NHlYy4KvwoFCeGpCN+Uvl25rnRZYxVtJCfWOixtWA+XOYhBiDjlKnTN+0WRZPg60ugFumeao0Pr13Tr/lCStIpVRag2mn0tmsdrxpVOBvthMumtI8hVA3AVaybj/ixe3ILTci3PYfCNrkgAAwXPUuVjfmGUCOxzuDZZv+3nHFELX5AEnlUOqcCHTu3an08dKmYBvGscKtMwb8DSnZLuuChXDtCk9+zCQdZDHHlR2Eery49MWP99ilTqEgyyb9Sxu267RwaF/5aDweKsxS+xcRUR8pdJ4t4N+YuyDC9Z+sJhpIHQAq1oedDiIIq6gNUeYCUl0C450LnPJkXtgnME29BySsO5f6PAn+1C+NdyMeLaGRG/bAs49FvNZDU/k7FjkjqTrtDfw/zkAzJFPL7/CMcfscgLrdWRCcRduvlP1jnPbjsFXfb+80qE551JyZ+w9LBkKcndGASBjL1cm7eazAPV+zBpGESyZoVsNUJbM6h82E1W+LTwAb1pTpDgZmSR45Pz+b9eQQ1RNs32Dml1t/4GKftRrM94O2pHU2F5z/3tT1/y84aMP62yrcGOrEBVc1JFPZIjSi/RoneMRQKx9wEXZ+bZ6EzshiBdqi3GXVQ9wBtmWV2Q2aflM/fF9u9/ScXUGzzqTsBShNNNmKx0x4wRglzmJsMAI0FS9XAKTG2rq9IYyJEbx4fY66bqsqQ45Jrw/Kf2CNCvVixx1xBzldG2uE+obh7mRsE1yqpzgMou28ps09LtZuyFQ8pPbGX/jEDb270At7IhNvyk6OfQEB1JT8vqerob6LuGJB4rJIJ&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240924T112345Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY6XP4XSCQ/20240924/us-east-1/s3/aws4_request&X-Amz-Signature=7cab48b68f36283e8b68ccd4097ff04cc81456abdbce215573a8b71e9b171ca9&hash=37a57f8b1d000b52e9187bd790a61b07e918b846f27ed74dfe8931c297a115e0&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2352340918315191&tid=spdf-fe72e14c-fb46-4922-a275-7eab25c3b17f&sid=450313eb950874485d99a000fde3d6855cf1gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=16035b035f505555545e&rr=8c82677828886dec&cc=pe


