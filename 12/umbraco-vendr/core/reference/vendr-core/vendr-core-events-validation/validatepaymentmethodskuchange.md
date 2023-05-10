---
title: ValidatePaymentMethodSkuChange
description: API reference for ValidatePaymentMethodSkuChange in Vendr, the eCommerce solution for Umbraco
---
## ValidatePaymentMethodSkuChange

```csharp
public class ValidatePaymentMethodSkuChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../../vendr-common/vendr-common-events/validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidatePaymentMethodSkuChange

```csharp
public ValidatePaymentMethodSkuChange(PaymentMethodReadOnly paymentMethod, 
    ChangingValue<string> sku)
```


### Properties

#### PaymentMethod

```csharp
public PaymentMethodReadOnly PaymentMethod { get; }
```


---

#### Sku

```csharp
public ChangingValue<string> Sku { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->