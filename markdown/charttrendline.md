# ChartTrendline Object (JavaScript API for Excel)

This object represents the attributes for a chart trendline object.

## Properties

| Property	   | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|displayEquation|bool|True if the equation for the trendline is displayed on the chart.|[1.8](../requirement-sets/excel-api-requirement-sets.md)|
|displayRSquared|bool|True if the R-squared for the trendline is displayed on the chart.|[1.8](../requirement-sets/excel-api-requirement-sets.md)|
|movingAveragePeriod|int|Represents the MovingAveragePeriod of a chart trendline, specific for trendline with MovingAverage type.|[1.8](../requirement-sets/excel-api-requirement-sets.md)|
|polynomialOrder|int|Represents the PolynomialOrder of a chart trendline, specific for trendline with Polynomial type.|[1.8](../requirement-sets/excel-api-requirement-sets.md)|
|type|string|Represents the type of a chart trendline. Possible values are: Linear, Expontential, Logarithmic, MovingAvg, Polynomial, Power.|[1.8](../requirement-sets/excel-api-requirement-sets.md)|

_See property access [examples.](#property-access-examples)_

## Relationships
| Relationship | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|format|[ChartTrendlineFormat](charttrendlineformat.md)|Represents the formatting of a chart trendline. Read-only.|[1.8](../requirement-sets/excel-api-requirement-sets.md)|

## Methods
None

