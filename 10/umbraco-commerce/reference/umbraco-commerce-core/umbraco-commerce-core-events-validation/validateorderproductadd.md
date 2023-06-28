---
title: ValidateOrderProductAdd
description: API reference for ValidateOrderProductAdd in Umbraco Commerce
---
## ValidateOrderProductAdd

```csharp
public class ValidateOrderProductAdd : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateOrderProductAdd (1 of 2)

```csharp
public ValidateOrderProductAdd(OrderReadOnly order, string productReference, decimal qty, 
    IDictionary<string, string> properties, string bundleId, string parentBundleId)
```

---

#### ValidateOrderProductAdd (2 of 2)

```csharp
public ValidateOrderProductAdd(OrderReadOnly order, IProductSnapshot productSnapshot, 
    string productReference, string productVariantReference, decimal qty, 
    IDictionary<string, string> properties, string bundleId, string parentBundleId)
```


### Properties

#### BundleId

```csharp
public string BundleId { get; }
```


---

#### Order

```csharp
public OrderReadOnly Order { get; }
```


---

#### ParentBundleId

```csharp
public string ParentBundleId { get; }
```


---

#### ProductReference

```csharp
public string ProductReference { get; }
```


---

#### ProductSnapshot

```csharp
public IProductSnapshot ProductSnapshot { get; }
```


---

#### ProductVariantReference

```csharp
public string ProductVariantReference { get; }
```


---

#### Properties

```csharp
public IDictionary<string, string> Properties { get; }
```


---

#### Quantity

```csharp
public decimal Quantity { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->