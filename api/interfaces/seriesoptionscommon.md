[lightweight-charts](../README.md) > [SeriesOptionsCommon](../interfaces/seriesoptionscommon.md)

# Interface: SeriesOptionsCommon

Structure describing options common for all types of series

## Hierarchy

**SeriesOptionsCommon**

## Index

### Properties

* [baseLineColor](seriesoptionscommon.md#baselinecolor)
* [baseLineStyle](seriesoptionscommon.md#baselinestyle)
* [baseLineVisible](seriesoptionscommon.md#baselinevisible)
* [baseLineWidth](seriesoptionscommon.md#baselinewidth)
* [lastValueVisible](seriesoptionscommon.md#lastvaluevisible)
* [priceFormat](seriesoptionscommon.md#priceformat)
* [priceLineColor](seriesoptionscommon.md#pricelinecolor)
* [priceLineStyle](seriesoptionscommon.md#pricelinestyle)
* [priceLineVisible](seriesoptionscommon.md#pricelinevisible)
* [priceLineWidth](seriesoptionscommon.md#pricelinewidth)
* [title](seriesoptionscommon.md#title)

---

## Properties

<a id="baselinecolor"></a>

###  baseLineColor

**● baseLineColor**: *`string`*

Color of the base line in IndexedTo100 mode

___
<a id="baselinestyle"></a>

###  baseLineStyle

**● baseLineStyle**: *[LineStyle](../enums/linestyle.md)*

Base line style. Suitible for percentage and indexedTo100 scales. Ignored if baseLineVisible is not set

___
<a id="baselinevisible"></a>

###  baseLineVisible

**● baseLineVisible**: *`boolean`*

Visibity of base line. Suitible for percentage and indexedTo100 scales

___
<a id="baselinewidth"></a>

###  baseLineWidth

**● baseLineWidth**: *[LineWidth](../#linewidth)*

Base line width. Suitible for percentage and indexedTo100 scales. Ignored if baseLineVisible is not set

___
<a id="lastvaluevisible"></a>

###  lastValueVisible

**● lastValueVisible**: *`boolean`*

Visibility of the label with the latest visible price on the price scale

___
<a id="priceformat"></a>

###  priceFormat

**● priceFormat**: *[PriceFormat](priceformat.md)*

Formatting settings associated with the series

___
<a id="pricelinecolor"></a>

###  priceLineColor

**● priceLineColor**: *`string`*

Color of the price line. Ignored if priceLineVisible is false

___
<a id="pricelinestyle"></a>

###  priceLineStyle

**● priceLineStyle**: *[LineStyle](../enums/linestyle.md)*

Price line style. Suitible for percentage and indexedTo100 scales

___
<a id="pricelinevisible"></a>

###  priceLineVisible

**● priceLineVisible**: *`boolean`*

Visibility of the price line. Price line is a horizontal line indicating the last price of the series

___
<a id="pricelinewidth"></a>

###  priceLineWidth

**● priceLineWidth**: *[LineWidth](../#linewidth)*

Width of the price line. Ignored if priceLineVisible is false

___
<a id="title"></a>

###  title

**● title**: *`string`*

Title of the series. This label is placed with price axis label

___

