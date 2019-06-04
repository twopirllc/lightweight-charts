[lightweight-charts](../README.md) > [ISeriesApi](../interfaces/iseriesapi.md)

# Interface: ISeriesApi

## Type parameters
#### TSeriesType :  [SeriesType](../#seriestype)
## Hierarchy

**ISeriesApi**

## Index

### Methods

* [applyOptions](iseriesapi.md#applyoptions)
* [options](iseriesapi.md#options)
* [priceFormatter](iseriesapi.md#priceformatter)
* [priceToCoordinate](iseriesapi.md#pricetocoordinate)
* [setData](iseriesapi.md#setdata)
* [update](iseriesapi.md#update)

---

## Methods

<a id="applyoptions"></a>

###  applyOptions

▸ **applyOptions**(options: *`SeriesPartialOptionsMap[TSeriesType]`*): `void`

Applies new options to the existing series

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| options | `SeriesPartialOptionsMap[TSeriesType]` |  any subset of options |

**Returns:** `void`

___
<a id="options"></a>

###  options

▸ **options**(): `Readonly`<`SeriesOptionsMap[TSeriesType]`>

Returns currently applied options

**Returns:** `Readonly`<`SeriesOptionsMap[TSeriesType]`>
full set of currently applied options, including defaults

___
<a id="priceformatter"></a>

###  priceFormatter

▸ **priceFormatter**(): [IPriceFormatter](ipriceformatter.md)

Returns current price formatter

**Returns:** [IPriceFormatter](ipriceformatter.md)
*   interface to the price formatter object that can be used to format prices in the same way as the chart does

___
<a id="pricetocoordinate"></a>

###  priceToCoordinate

▸ **priceToCoordinate**(price: *[BarPrice](../#barprice)*): [Coordinate](../#coordinate) \| `null`

Converts specified series price to pixel coordinate according to the chart price scale

*__result__*: *   pixel coordinate of the price level on the chart

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| price | [BarPrice](../#barprice) |  input price to be converted |

**Returns:** [Coordinate](../#coordinate) \| `null`

___
<a id="setdata"></a>

###  setData

▸ **setData**(data: *`SeriesDataItemTypeMap[TSeriesType]`[]*): `void`

Sets or replaces series data

**Parameters:**

| Name | Type |
| ------ | ------ |
| data | `SeriesDataItemTypeMap[TSeriesType]`[] |

**Returns:** `void`

___
<a id="update"></a>

###  update

▸ **update**(bar: *`SeriesDataItemTypeMap[TSeriesType]`*): `void`

Adds or replaces a new bar

**Parameters:**

| Name | Type |
| ------ | ------ |
| bar | `SeriesDataItemTypeMap[TSeriesType]` |

**Returns:** `void`

___

