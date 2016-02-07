# throwerCircle

a [Sails](http://sailsjs.org) application

# Models

 - User
  - Name
  - Email
  - Address
 - ItemType
  - Name
 - Item
  - Age
  - Make
  - Model
  - Owner ID (User)
  - Possessor ID (User)
 - TradeGroup
 - TradeSeries
  - Current TradeSeriesEntry ID
 - TradeSeriesEntry
  - Order Position
  - User ID
  - TradeSeries ID
 - TradeAgreementType
 - TradeAgreement
  - Start Date
  - End Date
  - Item ID
  - TradeGroup ID
  - TradeSeries ID
  - TradeAgreementType ID
 - TradeEvent
  - Date
  - Status
  - TradeAgreement ID
