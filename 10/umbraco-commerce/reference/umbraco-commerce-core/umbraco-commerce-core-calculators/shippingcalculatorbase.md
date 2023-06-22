---
title: ShippingCalculatorBase
description: API reference for ShippingCalculatorBase in Umbraco Commerce
---
## ShippingCalculatorBase

```csharp
public abstract class ShippingCalculatorBase : IShippingCalculator
```

**Inheritance**

* interface [IShippingCalculator](ishippingcalculator.md)

**Namespace**
* [Umbraco.Commerce.Core.Calculators](README.md)

### Methods

#### CalculateShippingMethodPrice

```csharp
public Price CalculateShippingMethodPrice(ShippingMethodReadOnly shippingMethod, Guid currencyId, 
    Guid? countryId, Guid? regionId, TaxRate taxRate)
```


---

#### CalculateShippingMethodPrice

```csharp
public abstract Price CalculateShippingMethodPrice(ShippingMethodReadOnly shippingMethod, 
    Guid currencyId, Guid? countryId, Guid? regionId, TaxRate taxRate, 
    ShippingCalculatorContext context)
```


---

#### CalculateShippingMethodTaxRate

```csharp
public TaxRate CalculateShippingMethodTaxRate(ShippingMethodReadOnly shippingMethod, 
    TaxSource taxSource, TaxRate fallbackTaxRate)
```


---

#### CalculateShippingMethodTaxRate

```csharp
public abstract TaxRate CalculateShippingMethodTaxRate(ShippingMethodReadOnly shippingMethod, 
    TaxSource taxSource, TaxRate fallbackTaxRate, ShippingCalculatorContext context)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->