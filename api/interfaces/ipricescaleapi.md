[lightweight-charts](../README.md) > [IPriceScaleApi](../interfaces/ipricescaleapi.md)

# Interface: IPriceScaleApi

Interface to control chart's price scale

## Hierarchy

**IPriceScaleApi**

## Index

### Methods

* [applyOptions](ipricescaleapi.md#applyoptions)
* [options](ipricescaleapi.md#options)

---

## Methods

<a id="applyoptions"></a>

###  applyOptions

▸ **applyOptions**(options: *[DeepPartial](../#deeppartial)<[PriceScaleOptions](pricescaleoptions.md)>*): `void`

Applies new options to the price scale

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| options | [DeepPartial](../#deeppartial)<[PriceScaleOptions](pricescaleoptions.md)> |  any subset of PriceScaleOptions |

**Returns:** `void`

___
<a id="options"></a>

###  options

▸ **options**(): `Readonly`<[PriceScaleOptions](pricescaleoptions.md)>

Returns currently applied options of the price scale

**Returns:** `Readonly`<[PriceScaleOptions](pricescaleoptions.md)>
full set of currently applied options, including defaults

___

