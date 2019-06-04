[lightweight-charts](../README.md) > [IChartApi](../interfaces/ichartapi.md)

# Interface: IChartApi

## Hierarchy

**IChartApi**

## Index

### Methods

* [addAreaSeries](ichartapi.md#addareaseries)
* [addBarSeries](ichartapi.md#addbarseries)
* [addCandleSeries](ichartapi.md#addcandleseries)
* [addHistogramSeries](ichartapi.md#addhistogramseries)
* [addLineSeries](ichartapi.md#addlineseries)
* [applyOptions](ichartapi.md#applyoptions)
* [disableBranding](ichartapi.md#disablebranding)
* [options](ichartapi.md#options)
* [priceScale](ichartapi.md#pricescale)
* [remove](ichartapi.md#remove)
* [removeSeries](ichartapi.md#removeseries)
* [resize](ichartapi.md#resize)
* [subscribeClick](ichartapi.md#subscribeclick)
* [subscribeCrosshairMove](ichartapi.md#subscribecrosshairmove)
* [subscribeVisibleTimeRangeChange](ichartapi.md#subscribevisibletimerangechange)
* [timeScale](ichartapi.md#timescale)
* [unsubscribeClick](ichartapi.md#unsubscribeclick)
* [unsubscribeCrosshairMove](ichartapi.md#unsubscribecrosshairmove)
* [unsubscribeVisibleTimeRangeChange](ichartapi.md#unsubscribevisibletimerangechange)

---

## Methods

<a id="addareaseries"></a>

###  addAreaSeries

▸ **addAreaSeries**(areaParams?: *[AreaSeriesPartialOptions](../#areaseriespartialoptions)*): [ISeriesApi](iseriesapi.md)<"Area">

Creates an area series with specified parameters

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` areaParams | [AreaSeriesPartialOptions](../#areaseriespartialoptions) |

**Returns:** [ISeriesApi](iseriesapi.md)<"Area">
an interface of the created series

___
<a id="addbarseries"></a>

###  addBarSeries

▸ **addBarSeries**(barParams?: *[BarSeriesPartialOptions](../#barseriespartialoptions)*): [ISeriesApi](iseriesapi.md)<"Bar">

Creates a bar series with specified parameters

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` barParams | [BarSeriesPartialOptions](../#barseriespartialoptions) |

**Returns:** [ISeriesApi](iseriesapi.md)<"Bar">
an interface of the created series

___
<a id="addcandleseries"></a>

###  addCandleSeries

▸ **addCandleSeries**(candleParams?: *[CandleSeriesPartialOptions](../#candleseriespartialoptions)*): [ISeriesApi](iseriesapi.md)<"Candle">

Creates a candle series with specified parameters

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` candleParams | [CandleSeriesPartialOptions](../#candleseriespartialoptions) |

**Returns:** [ISeriesApi](iseriesapi.md)<"Candle">
an interface of the created series

___
<a id="addhistogramseries"></a>

###  addHistogramSeries

▸ **addHistogramSeries**(histogramParams?: *[HistogramSeriesPartialOptions](../#histogramseriespartialoptions)*): [ISeriesApi](iseriesapi.md)<"Histogram">

Creates a histogram series with specified parameters

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` histogramParams | [HistogramSeriesPartialOptions](../#histogramseriespartialoptions) |

**Returns:** [ISeriesApi](iseriesapi.md)<"Histogram">
an interface of the created series

___
<a id="addlineseries"></a>

###  addLineSeries

▸ **addLineSeries**(lineParams?: *[LineSeriesPartialOptions](../#lineseriespartialoptions)*): [ISeriesApi](iseriesapi.md)<"Line">

Creates a line series with specified parameters

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` lineParams | [LineSeriesPartialOptions](../#lineseriespartialoptions) |

**Returns:** [ISeriesApi](iseriesapi.md)<"Line">
an interface of the created series

___
<a id="applyoptions"></a>

###  applyOptions

▸ **applyOptions**(options: *[DeepPartial](../#deeppartial)<[ChartOptions](chartoptions.md)>*): `void`

Applies new options to the chart

**Parameters:**

| Name | Type |
| ------ | ------ |
| options | [DeepPartial](../#deeppartial)<[ChartOptions](chartoptions.md)> |

**Returns:** `void`

___
<a id="disablebranding"></a>

###  disableBranding

▸ **disableBranding**(): `void`

Removes branding text from the chart. Please read the description of this method in the documentation to learn more about the conditions of branding removal.

**Returns:** `void`

___
<a id="options"></a>

###  options

▸ **options**(): `Readonly`<[ChartOptions](chartoptions.md)>

Returns currently applied options

**Returns:** `Readonly`<[ChartOptions](chartoptions.md)>
*   full set of currently applied options, including defaults

___
<a id="pricescale"></a>

###  priceScale

▸ **priceScale**(): [IPriceScaleApi](ipricescaleapi.md)

Returns API to manipulate the price scale

**Returns:** [IPriceScaleApi](ipricescaleapi.md)
*   target API

___
<a id="remove"></a>

###  remove

▸ **remove**(): `void`

Removes the chart object including all DOM elements. This is an irreversible operation, you cannot do anything with the chart after removing it.

**Returns:** `void`

___
<a id="removeseries"></a>

###  removeSeries

▸ **removeSeries**(seriesApi: *[ISeriesApi](iseriesapi.md)<[SeriesType](../#seriestype)>*): `void`

Removes a series of any type. This is an irreversible operation, you cannot do anything with the series after removing it

**Parameters:**

| Name | Type |
| ------ | ------ |
| seriesApi | [ISeriesApi](iseriesapi.md)<[SeriesType](../#seriestype)> |

**Returns:** `void`

___
<a id="resize"></a>

###  resize

▸ **resize**(height: *`number`*, width: *`number`*, forceRepaint?: *`undefined` \| `false` \| `true`*): `void`

Sets fixed size of the chart. By default chart takes up 100% of its container

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| height | `number` |  target height of the chart |
| width | `number` |  target width of the chart |
| `Optional` forceRepaint | `undefined` \| `false` \| `true` |

**Returns:** `void`

___
<a id="subscribeclick"></a>

###  subscribeClick

▸ **subscribeClick**(handler: *[MouseEventHandler](../#mouseeventhandler)*): `void`

**Parameters:**

| Name | Type |
| ------ | ------ |
| handler | [MouseEventHandler](../#mouseeventhandler) |

**Returns:** `void`

___
<a id="subscribecrosshairmove"></a>

###  subscribeCrosshairMove

▸ **subscribeCrosshairMove**(handler: *[MouseEventHandler](../#mouseeventhandler)*): `void`

Adds a subscription to crosshair movement to receive notifications on crosshair movements

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| handler | [MouseEventHandler](../#mouseeventhandler) |  handler (function) to be called on crosshair move |

**Returns:** `void`

___
<a id="subscribevisibletimerangechange"></a>

###  subscribeVisibleTimeRangeChange

▸ **subscribeVisibleTimeRangeChange**(handler: *[TimeRangeChangeEventHandler](../#timerangechangeeventhandler)*): `void`

Adds a subscription to visible range changes to receive notification about visible range of data changes

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| handler | [TimeRangeChangeEventHandler](../#timerangechangeeventhandler) |  handler (function) to be called on changing visible data range |

**Returns:** `void`

___
<a id="timescale"></a>

###  timeScale

▸ **timeScale**(): [ITimeScaleApi](itimescaleapi.md)

Returns API to manipulate the time scale

**Returns:** [ITimeScaleApi](itimescaleapi.md)
*   target API

___
<a id="unsubscribeclick"></a>

###  unsubscribeClick

▸ **unsubscribeClick**(handler: *[MouseEventHandler](../#mouseeventhandler)*): `void`

Removes mouse click subscription

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| handler | [MouseEventHandler](../#mouseeventhandler) |  previously subscribed handler |

**Returns:** `void`

___
<a id="unsubscribecrosshairmove"></a>

###  unsubscribeCrosshairMove

▸ **unsubscribeCrosshairMove**(handler: *[MouseEventHandler](../#mouseeventhandler)*): `void`

Removes a subscription on crosshair movement

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| handler | [MouseEventHandler](../#mouseeventhandler) |  previously subscribed handler |

**Returns:** `void`

___
<a id="unsubscribevisibletimerangechange"></a>

###  unsubscribeVisibleTimeRangeChange

▸ **unsubscribeVisibleTimeRangeChange**(handler: *[TimeRangeChangeEventHandler](../#timerangechangeeventhandler)*): `void`

Removes a subscription to visible range changes

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| handler | [TimeRangeChangeEventHandler](../#timerangechangeeventhandler) |  previously subscribed handler |

**Returns:** `void`

___

