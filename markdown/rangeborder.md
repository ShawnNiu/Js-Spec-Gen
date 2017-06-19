# RangeBorder Object (JavaScript API for Excel)

Represents the border of an object.

## Properties

| Property	   | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|color|string|HTML color code representing the color of the border line, of the form #RRGGBB (e.g. "FFA500") or as a named HTML color (e.g. "orange").|[1.1](../requirement-sets/excel-api-requirement-sets.md)|
|id|string|Represents border identifier. Read-only. Possible values are: EdgeTop, EdgeBottom, EdgeLeft, EdgeRight, InsideVertical, InsideHorizontal, DiagonalDown, DiagonalUp.|[1.1](../requirement-sets/excel-api-requirement-sets.md)|
|sideIndex|string|Constant value that indicates the specific side of the border. Read-only. Possible values are: EdgeTop, EdgeBottom, EdgeLeft, EdgeRight, InsideVertical, InsideHorizontal, DiagonalDown, DiagonalUp.|[1.1](../requirement-sets/excel-api-requirement-sets.md)|
|style|string|One of the constants of line style specifying the line style for the border. Possible values are: None, Continuous, Dash, DashDot, DashDotDot, Dot, Double, SlantDashDot.|[1.1](../requirement-sets/excel-api-requirement-sets.md)|
|weight|string|Specifies the weight of the border around a range. Possible values are: Hairline, Thin, Medium, Thick.|[1.1](../requirement-sets/excel-api-requirement-sets.md)|

_See property access [examples.](#property-access-examples)_

## Relationships
None


## Methods
None

