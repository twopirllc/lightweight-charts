[lightweight-charts](../README.md) > [LocalizationOptions](../interfaces/localizationoptions.md)

# Interface: LocalizationOptions

## Hierarchy

**LocalizationOptions**

## Index

### Properties

* [dateFormat](localizationoptions.md#dateformat)
* [locale](localizationoptions.md#locale)
* [priceFormatter](localizationoptions.md#priceformatter)
* [timeFormatter](localizationoptions.md#timeformatter)

---

## Properties

<a id="dateformat"></a>

###  dateFormat

**● dateFormat**: *[DateFormat](../#dateformat)*

One of predefined options to format time. Ignored if timeFormatter has been specified.

___
<a id="locale"></a>

###  locale

**● locale**: *`string`*

Current locale, which will be used for formatting dates.

*__see__*: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global\_Objects/Intl#Locale\_identification\_and\_negotiation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl#Locale_identification_and_negotiation)

___
<a id="priceformatter"></a>

### `<Optional>` priceFormatter

**● priceFormatter**: *[PriceFormatterFn](../#priceformatterfn)*

User-defined function for price formatting. Could be used for some specific cases, that could not be covered with PriceFormat

___
<a id="timeformatter"></a>

### `<Optional>` timeFormatter

**● timeFormatter**: *[TimeFormatterFn](../#timeformatterfn)*

User-defined function for time formatting.

___

