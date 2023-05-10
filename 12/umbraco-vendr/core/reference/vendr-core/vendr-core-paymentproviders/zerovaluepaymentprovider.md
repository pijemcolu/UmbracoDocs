---
title: ZeroValuePaymentProvider
description: API reference for ZeroValuePaymentProvider in Vendr, the eCommerce solution for Umbraco
---
## ZeroValuePaymentProvider

```csharp
public class ZeroValuePaymentProvider : AsyncPaymentProviderBase<ZeroValuePaymentProviderSettings>
```

**Inheritance**

* class [AsyncPaymentProviderBase&lt;TSettingsModel&gt;](../asyncpaymentproviderbase-1/)

**Namespace**
* [Vendr.Core.PaymentProviders](../)

### Constructors

#### ZeroValuePaymentProvider

```csharp
public ZeroValuePaymentProvider(VendrContext vendr)
```


### Properties

#### FinalizeAtContinueUrl

```csharp
public override bool FinalizeAtContinueUrl { get; }
```


### Methods

#### GenerateFormAsync

```csharp
public override Task<PaymentFormResult> GenerateFormAsync(
    PaymentProviderContext<ZeroValuePaymentProviderSettings> context, 
    CancellationToken cancellationToken = default(CancellationToken))
```


---

#### GetCancelUrl

```csharp
public override string GetCancelUrl(
    PaymentProviderContext<ZeroValuePaymentProviderSettings> context)
```


---

#### GetContinueUrl

```csharp
public override string GetContinueUrl(
    PaymentProviderContext<ZeroValuePaymentProviderSettings> context)
```


---

#### GetErrorUrl

```csharp
public override string GetErrorUrl(PaymentProviderContext<ZeroValuePaymentProviderSettings> context)
```


---

#### ProcessCallbackAsync

```csharp
public override Task<CallbackResult> ProcessCallbackAsync(
    PaymentProviderContext<ZeroValuePaymentProviderSettings> context, 
    CancellationToken cancellationToken = default(CancellationToken))
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->