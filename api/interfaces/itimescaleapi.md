[lightweight-charts](../README.md) > [ITimeScaleApi](../interfaces/itimescaleapi.md)

# Interface: ITimeScaleApi

Interface to chart time scale

## Hierarchy

**ITimeScaleApi**

## Index

### Methods

* [applyOptions](itimescaleapi.md#applyoptions)
* [fitContent](itimescaleapi.md#fitcontent)
* [getVisibleRange](itimescaleapi.md#getvisiblerange)
* [options](itimescaleapi.md#options)
* [resetTimeScale](itimescaleapi.md#resettimescale)
* [scrollPosition](itimescaleapi.md#scrollposition)
* [scrollToPosition](itimescaleapi.md#scrolltoposition)
* [scrollToRealTime](itimescaleapi.md#scrolltorealtime)
* [setVisibleRange](itimescaleapi.md#setvisiblerange)

---

## Methods

<a id="applyoptions"></a>

###  applyOptions

▸ **applyOptions**(options: *[DeepPartial](../#deeppartial)<[TimeScaleOptions](timescaleoptions.md)>*): `void`

Applies new options to the time scale.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| options | [DeepPartial](../#deeppartial)<[TimeScaleOptions](timescaleoptions.md)> |  any subset of options |

**Returns:** `void`

___
<a id="fitcontent"></a>

###  fitContent

▸ **fitContent**(): `void`

Automatically calculates the visible range to fit all data from all series This is a momentary operation.

**Returns:** `void`

___
<a id="getvisiblerange"></a>

###  getVisibleRange

▸ **getVisibleRange**(): [TimeRange](timerange.md) \| `null`

Returns current visible time range of the chart

**Returns:** [TimeRange](timerange.md) \| `null`
*   visible range or null if the chart has no data at all

___
<a id="options"></a>

###  options

▸ **options**(): `Readonly`<[TimeScaleOptions](timescaleoptions.md)>

Returns current options

**Returns:** `Readonly`<[TimeScaleOptions](timescaleoptions.md)>
*   currently applied options

___
<a id="resettimescale"></a>

###  resetTimeScale

▸ **resetTimeScale**(): `void`

Restores default zooming and scroll position of the time scale

**Returns:** `void`

___
<a id="scrollposition"></a>

###  scrollPosition

▸ **scrollPosition**(): `number`

Returns current scroll position of the chart

**Returns:** `number`
a distance from the right edge to the latest bar, measured in bars

___
<a id="scrolltoposition"></a>

###  scrollToPosition

▸ **scrollToPosition**(position: *`number`*, animated: *`boolean`*): `void`

Scrolls the chart to the specified position

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| position | `number` |  target data position |
| animated | `boolean` |  setting this to true makes the chart scrolling smooth and adds animation |

**Returns:** `void`

___
<a id="scrolltorealtime"></a>

###  scrollToRealTime

▸ **scrollToRealTime**(): `void`

Restores default scroll position of the chart. This process is always animated.

**Returns:** `void`

___
<a id="setvisiblerange"></a>

###  setVisibleRange

▸ **setVisibleRange**(range: *[TimeRange](timerange.md)*): `void`

Sets visible range of data

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| range | [TimeRange](timerange.md) |  target visible range of data |

**Returns:** `void`

___

