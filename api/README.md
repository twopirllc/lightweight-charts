
Lightweight Charts
==================

## Index

### Enumerations

* [CrosshairMode](enums/crosshairmode.md)
* [LineStyle](enums/linestyle.md)
* [LineType](enums/linetype.md)
* [PriceScaleMode](enums/pricescalemode.md)

### Interfaces

* [AreaStyleOptions](interfaces/areastyleoptions.md)
* [BarData](interfaces/bardata.md)
* [BarStyleOptions](interfaces/barstyleoptions.md)
* [BusinessDay](interfaces/businessday.md)
* [CandleStyleOptions](interfaces/candlestyleoptions.md)
* [ChartOptions](interfaces/chartoptions.md)
* [CrosshairLineOptions](interfaces/crosshairlineoptions.md)
* [CrosshairOptions](interfaces/crosshairoptions.md)
* [GridLineOptions](interfaces/gridlineoptions.md)
* [GridOptions](interfaces/gridoptions.md)
* [HandleScaleOptions](interfaces/handlescaleoptions.md)
* [HandleScrollOptions](interfaces/handlescrolloptions.md)
* [HistogramData](interfaces/histogramdata.md)
* [HistogramStyleOptions](interfaces/histogramstyleoptions.md)
* [IChartApi](interfaces/ichartapi.md)
* [IPriceFormatter](interfaces/ipriceformatter.md)
* [IPriceScaleApi](interfaces/ipricescaleapi.md)
* [ISeriesApi](interfaces/iseriesapi.md)
* [ITimeScaleApi](interfaces/itimescaleapi.md)
* [LayoutOptions](interfaces/layoutoptions.md)
* [LineData](interfaces/linedata.md)
* [LineStyleOptions](interfaces/linestyleoptions.md)
* [LocalizationOptions](interfaces/localizationoptions.md)
* [MouseEventParams](interfaces/mouseeventparams.md)
* [NonOverlaySeriesSpecificOptions](interfaces/nonoverlayseriesspecificoptions.md)
* [OverlaySeriesSpecificOptions](interfaces/overlayseriesspecificoptions.md)
* [Point](interfaces/point.md)
* [PriceFormat](interfaces/priceformat.md)
* [PriceScaleMargins](interfaces/pricescalemargins.md)
* [PriceScaleOptions](interfaces/pricescaleoptions.md)
* [SeriesDataItemTypeMap](interfaces/seriesdataitemtypemap.md)
* [SeriesOptionsCommon](interfaces/seriesoptionscommon.md)
* [SeriesOptionsMap](interfaces/seriesoptionsmap.md)
* [SeriesPartialOptionsMap](interfaces/seriespartialoptionsmap.md)
* [TimeRange](interfaces/timerange.md)
* [TimeScaleOptions](interfaces/timescaleoptions.md)
* [WatermarkOptions](interfaces/watermarkoptions.md)

### Type aliases

* [AreaSeriesOptions](#areaseriesoptions)
* [AreaSeriesPartialOptions](#areaseriespartialoptions)
* [BarPrice](#barprice)
* [BarSeriesOptions](#barseriesoptions)
* [BarSeriesPartialOptions](#barseriespartialoptions)
* [CandleSeriesOptions](#candleseriesoptions)
* [CandleSeriesPartialOptions](#candleseriespartialoptions)
* [Coordinate](#coordinate)
* [DateFormat](#dateformat)
* [DeepPartial](#deeppartial)
* [HistogramSeriesOptions](#histogramseriesoptions)
* [HistogramSeriesPartialOptions](#histogramseriespartialoptions)
* [HorzAlign](#horzalign)
* [LineSeriesOptions](#lineseriesoptions)
* [LineSeriesPartialOptions](#lineseriespartialoptions)
* [LineWidth](#linewidth)
* [MouseEventHandler](#mouseeventhandler)
* [Nominal](#nominal)
* [PriceAxisPosition](#priceaxisposition)
* [PriceFormatterFn](#priceformatterfn)
* [SeriesOptions](#seriesoptions)
* [SeriesPartialOptions](#seriespartialoptions)
* [SeriesType](#seriestype)
* [Time](#time)
* [TimeFormatterFn](#timeformatterfn)
* [TimeRangeChangeEventHandler](#timerangechangeeventhandler)
* [UTCTimestamp](#utctimestamp)
* [VertAlign](#vertalign)

### Functions

* [createChart](#createchart)
* [isBusinessDay](#isbusinessday)
* [isUTCTimestamp](#isutctimestamp)
* [version](#version)

---

## Type aliases

<a id="areaseriesoptions"></a>

###  AreaSeriesOptions

**Ƭ AreaSeriesOptions**: *[SeriesOptions](#seriesoptions)<[AreaStyleOptions](interfaces/areastyleoptions.md)>*

Structure describing area series options.

___
<a id="areaseriespartialoptions"></a>

###  AreaSeriesPartialOptions

**Ƭ AreaSeriesPartialOptions**: *[SeriesPartialOptions](#seriespartialoptions)<[AreaStyleOptions](interfaces/areastyleoptions.md)>*

___
<a id="barprice"></a>

###  BarPrice

**Ƭ BarPrice**: *[Nominal](#nominal)<`number`, "BarPrice">*

___
<a id="barseriesoptions"></a>

###  BarSeriesOptions

**Ƭ BarSeriesOptions**: *[SeriesOptions](#seriesoptions)<[BarStyleOptions](interfaces/barstyleoptions.md)>*

Structure describing bar series options.

___
<a id="barseriespartialoptions"></a>

###  BarSeriesPartialOptions

**Ƭ BarSeriesPartialOptions**: *[SeriesPartialOptions](#seriespartialoptions)<[BarStyleOptions](interfaces/barstyleoptions.md)>*

___
<a id="candleseriesoptions"></a>

###  CandleSeriesOptions

**Ƭ CandleSeriesOptions**: *[SeriesOptions](#seriesoptions)<[CandleStyleOptions](interfaces/candlestyleoptions.md)>*

Structure describing candlesticks series options.

___
<a id="candleseriespartialoptions"></a>

###  CandleSeriesPartialOptions

**Ƭ CandleSeriesPartialOptions**: *[SeriesPartialOptions](#seriespartialoptions)<[CandleStyleOptions](interfaces/candlestyleoptions.md)>*

___
<a id="coordinate"></a>

###  Coordinate

**Ƭ Coordinate**: *[Nominal](#nominal)<`number`, "Coordinate">*

___
<a id="dateformat"></a>

###  DateFormat

**Ƭ DateFormat**: *"dd MMM &#x27;yy" \| "yyyy-MM-dd" \| "yy-MM-dd" \| "yy/MM/dd" \| "yyyy/MM/dd" \| "dd-MM-yyyy" \| "dd-MM-yy" \| "dd/MM/yy" \| "dd/MM/yyyy" \| "MM/dd/yy" \| "MM/dd/yyyy"*

___
<a id="deeppartial"></a>

###  DeepPartial

**Ƭ DeepPartial**: *`object`*

#### Type declaration

___
<a id="histogramseriesoptions"></a>

###  HistogramSeriesOptions

**Ƭ HistogramSeriesOptions**: *[SeriesOptions](#seriesoptions)<[HistogramStyleOptions](interfaces/histogramstyleoptions.md)>*

Structure describing histogram series options.

___
<a id="histogramseriespartialoptions"></a>

###  HistogramSeriesPartialOptions

**Ƭ HistogramSeriesPartialOptions**: *[SeriesPartialOptions](#seriespartialoptions)<[HistogramStyleOptions](interfaces/histogramstyleoptions.md)>*

___
<a id="horzalign"></a>

###  HorzAlign

**Ƭ HorzAlign**: *"left" \| "center" \| "right"*

___
<a id="lineseriesoptions"></a>

###  LineSeriesOptions

**Ƭ LineSeriesOptions**: *[SeriesOptions](#seriesoptions)<[LineStyleOptions](interfaces/linestyleoptions.md)>*

Structure describing line series options.

___
<a id="lineseriespartialoptions"></a>

###  LineSeriesPartialOptions

**Ƭ LineSeriesPartialOptions**: *[SeriesPartialOptions](#seriespartialoptions)<[LineStyleOptions](interfaces/linestyleoptions.md)>*

___
<a id="linewidth"></a>

###  LineWidth

**Ƭ LineWidth**: *`1` \| `2` \| `3` \| `4`*

___
<a id="mouseeventhandler"></a>

###  MouseEventHandler

**Ƭ MouseEventHandler**: *`function`*

#### Type declaration
▸(param: *[MouseEventParams](interfaces/mouseeventparams.md)*): `void`

**Parameters:**

| Name | Type |
| ------ | ------ |
| param | [MouseEventParams](interfaces/mouseeventparams.md) |

**Returns:** `void`

___
<a id="nominal"></a>

###  Nominal

**Ƭ Nominal**: *`T` & `object`*

This is the generic type useful for declaring a nominal type, which does not structurally matches with the base type and the other types declared over the same base type

Usage:

*__example__*: type Index = Nominal<number, 'Index'>; // let i: Index = 42; // this fails to compile let i: Index = 42 as Index; // OK

*__example__*: type TagName = Nominal<string, 'TagName'>;

___
<a id="priceaxisposition"></a>

###  PriceAxisPosition

**Ƭ PriceAxisPosition**: *"left" \| "right" \| "none"*

___
<a id="priceformatterfn"></a>

###  PriceFormatterFn

**Ƭ PriceFormatterFn**: *`function`*

#### Type declaration
▸(priceValue: *[BarPrice](#barprice)*): `string`

**Parameters:**

| Name | Type |
| ------ | ------ |
| priceValue | [BarPrice](#barprice) |

**Returns:** `string`

___
<a id="seriesoptions"></a>

###  SeriesOptions

**Ƭ SeriesOptions**: *`T` & [SeriesOptionsCommon](interfaces/seriesoptionscommon.md) & [OverlaySeriesSpecificOptions](interfaces/overlayseriesspecificoptions.md) \| `T` & [SeriesOptionsCommon](interfaces/seriesoptionscommon.md) & [NonOverlaySeriesSpecificOptions](interfaces/nonoverlayseriesspecificoptions.md)*

___
<a id="seriespartialoptions"></a>

###  SeriesPartialOptions

**Ƭ SeriesPartialOptions**: *`object` & [OverlaySeriesSpecificOptions](interfaces/overlayseriesspecificoptions.md) \| `object` & [NonOverlaySeriesSpecificOptions](interfaces/nonoverlayseriesspecificoptions.md)*

___
<a id="seriestype"></a>

###  SeriesType

**Ƭ SeriesType**: *`keyof SeriesOptionsMap`*

___
<a id="time"></a>

###  Time

**Ƭ Time**: *[UTCTimestamp](#utctimestamp) \| [BusinessDay](interfaces/businessday.md) \| `string`*

___
<a id="timeformatterfn"></a>

###  TimeFormatterFn

**Ƭ TimeFormatterFn**: *`function`*

#### Type declaration
▸(time: *[BusinessDay](interfaces/businessday.md) \| [UTCTimestamp](#utctimestamp)*): `string`

**Parameters:**

| Name | Type |
| ------ | ------ |
| time | [BusinessDay](interfaces/businessday.md) \| [UTCTimestamp](#utctimestamp) |

**Returns:** `string`

___
<a id="timerangechangeeventhandler"></a>

###  TimeRangeChangeEventHandler

**Ƭ TimeRangeChangeEventHandler**: *`function`*

#### Type declaration
▸(timeRange: *[TimeRange](interfaces/timerange.md) \| `null`*): `void`

**Parameters:**

| Name | Type |
| ------ | ------ |
| timeRange | [TimeRange](interfaces/timerange.md) \| `null` |

**Returns:** `void`

___
<a id="utctimestamp"></a>

###  UTCTimestamp

**Ƭ UTCTimestamp**: *[Nominal](#nominal)<`number`, "UTCTimestamp">*

___
<a id="vertalign"></a>

###  VertAlign

**Ƭ VertAlign**: *"top" \| "center" \| "bottom"*

___

## Functions

<a id="createchart"></a>

###  createChart

▸ **createChart**(container: *`string` \| `HTMLElement`*, options?: *[DeepPartial](#deeppartial)<[ChartOptions](interfaces/chartoptions.md)>*): [IChartApi](interfaces/ichartapi.md)

This function is the main entry point of the Lightweight Charting Library

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| container | `string` \| `HTMLElement` |  id of HTML element or element itself |
| `Optional` options | [DeepPartial](#deeppartial)<[ChartOptions](interfaces/chartoptions.md)> |  any subset of ChartOptions to be applied at start. |

**Returns:** [IChartApi](interfaces/ichartapi.md)
an interface to the created chart

___
<a id="isbusinessday"></a>

###  isBusinessDay

▸ **isBusinessDay**(time: *[Time](#time)*): `boolean`

**Parameters:**

| Name | Type |
| ------ | ------ |
| time | [Time](#time) |

**Returns:** `boolean`

___
<a id="isutctimestamp"></a>

###  isUTCTimestamp

▸ **isUTCTimestamp**(time: *[Time](#time)*): `boolean`

**Parameters:**

| Name | Type |
| ------ | ------ |
| time | [Time](#time) |

**Returns:** `boolean`

___
<a id="version"></a>

###  version

▸ **version**(): `string`

**Returns:** `string`

___

