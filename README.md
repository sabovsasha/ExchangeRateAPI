# ExchangeRateAPI
Swagger URL:
http://localhost:8080/swagger-ui.html

Download and synchronize provider's exchange rates with local Postgres DB:

http://localhost:8080/synchExchangeRates/?provider=monobank
http://localhost:8080/synchExchangeRates/?provider=bankgovua
http://localhost:8080/synchExchangeRates/?provider=privatbank

Request for a list of average exchange rates for all sources on the current day.

http://localhost:8080/getAvgExchRatesForToday/?provider=monobank
http://localhost:8080/getAvgExchRatesForToday/?provider=bankgovua
http://localhost:8080/getAvgExchRatesForToday/?provider=privatbank

Request for a list of average exchange rates for all sources for the period

http://localhost:8080/getAvgExchRatesForPeriod?provider=monobank&prevDate=07/05/2023&nextDate=10/05/2023
http://localhost:8080/getAvgExchRatesForPeriod?provider=bankgovua&prevDate=07/05/2023&nextDate=10/05/2023
http://localhost:8080/getAvgExchRatesForPeriod?provider=privatbank&prevDate=07/05/2023&nextDate=10/05/2023
