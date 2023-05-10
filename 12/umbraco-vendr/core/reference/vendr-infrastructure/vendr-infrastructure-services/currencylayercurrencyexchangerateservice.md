---
title: CurrencyLayerCurrencyExchangeRateService
description: API reference for CurrencyLayerCurrencyExchangeRateService in Vendr, the eCommerce solution for Umbraco
---
## CurrencyLayerCurrencyExchangeRateService

```csharp
public class CurrencyLayerCurrencyExchangeRateService : CurrencyExchangeRateServiceBase
```

**Inheritance**

* class [CurrencyExchangeRateServiceBase](../currencyexchangerateservicebase/)

**Namespace**
* [Vendr.Infrastructure.Services](../)

### Constructors

#### CurrencyLayerCurrencyExchangeRateService

```csharp
public CurrencyLayerCurrencyExchangeRateService(string apiKey)
```


### Methods

#### FetchExchangeRate

```csharp
public override decimal FetchExchangeRate(string fromCurrencyIsoCode, string toCurrencyIsoCode, 
    DateTime date)
```


---

#### FetchExchangeRates

```csharp
public override Dictionary<string, Dictionary<string, decimal>> FetchExchangeRates(
    string fromCurrencyIsoCode, string[] toCurrencyIsoCodes, DateTime dateFrom, DateTime dateTo)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Infrastructure.dll -->