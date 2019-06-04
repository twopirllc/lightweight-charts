[lightweight-charts](../README.md) > [PriceFormat](../interfaces/priceformat.md)

# Interface: PriceFormat

Structure describing series values formatting Fields precision and minMove allow wide customization of formatting

*__example__*: minMove = 0.01 , precision is not specified. Prices will change like 1.13, 1.14, 1.15 etc. minMove = 0.01 , precision = 3. Prices will change like 1.130, 1.140, 1.150 etc. minMove = 0.05 , precision is not specified. Prices will change like 1.10, 1.15, 1.20

## Hierarchy

**PriceFormat**

## Index

### Properties

* [minMove](priceformat.md#minmove)
* [precision](priceformat.md#precision)
* [type](priceformat.md#type)

---

## Properties

<a id="minmove"></a>

###  minMove

**● minMove**: *`number`*

Minimal step of the price. This value shouldn't have more decimal digits than the precision

___
<a id="precision"></a>

###  precision

**● precision**: *`number`*

Number of digits after the decimal point. If it is not set, then its value is calculated automatically based on minMove

___
<a id="type"></a>

###  type

**● type**: *"price" \| "volume" \| "percent"*

Enum of possible modes of price formatting 'price' is the most common choice; it allows customization of precision and rounding of prices 'volume' uses abbreviation for formatting prices like '1.2K' or '12.67M' 'percent' uses '%' sign at the end of prices.

___

