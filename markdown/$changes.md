|Object| What is new| Description|Feedback|
|:----|:----|:----|:----|
|[chart](../excel/chart.md)|_Property_ > showAllFieldButtons|Returns or sets whether to display all field buttons on a PivotChart. ReadWrite.|1.8|
|[chartAxis](../excel/chartaxis.md)|_Property_ > baseTimeUnit|Returns or sets the base unit for the specified category axis. Possible values are: Days, Months, Years.|1.8|
|[chartAxis](../excel/chartaxis.md)|_Property_ > categoryType|Returns or sets the category axis type. Possible values are: Automatic, TextAxis, DateAxis.|1.8|
|[chartAxis](../excel/chartaxis.md)|_Property_ > customDisplayUnit|Represents the custom axis display unit value.|1.8|
|[chartAxis](../excel/chartaxis.md)|_Property_ > displayUnit|Represents the axis display unit. Possible values are: None, Hundreds, Thousands, TenThousands, HundredThousands, Millions, TenMillions, HundredMillons, Billions, Trillions, Custom.|1.8|
|[chartAxis](../excel/chartaxis.md)|_Property_ > majorTimeUnitScale|Returns or sets the major unit scale value for the category axis when the CategoryType property is set to TimeScale. Possible values are: Days, Months, Years.|1.8|
|[chartAxis](../excel/chartaxis.md)|_Property_ > minorTimeUnitScale|Returns or sets the minor unit scale value for the category axis when the CategoryType property is set to TimeScale. Possible values are: Days, Months, Years.|1.8|
|[chartAxis](../excel/chartaxis.md)|_Property_ > showDisplayUnitLabel|Represents whether the axis display unit label is visible.|1.8|
|[chartAxis](../excel/chartaxis.md)|_Property_ > type|Represents the axis type. Read-only. Possible values are: Invalid, Category, Value, SeriesAxis.|1.8|
|[chartAxis](../excel/chartaxis.md)|_Method_ > [setCategoryNames(sourceData: Range)](../excel/chartaxis.md#setcategorynamessourcedata-range)|Sets all the category names for the specified axis.|1.8|
|[chartBorder](../excel/chartborder.md)|_Method_ > [clear()](../excel/chartborder.md#clear)|Clear the border color of a chart element.|1.8|
|[chartBorder](../excel/chartborder.md)|_Method_ > [setSolidColor(color: string)](../excel/chartborder.md#setsolidcolorcolor-string)|Sets the border formatting of a chart element to a uniform color.|1.8|
|[chartFormatString](../excel/chartformatstring.md)|_Relationship_ > font|Represents the font attributes, such as font name, font size, color, etc. of chart characters object. Read-only.|1.8|
|[chartLegend](../excel/chartlegend.md)|_Property_ > hasShadow|Represents if the legend has shadow on the chart.|1.8|
|[chartLegend](../excel/chartlegend.md)|_Property_ > height|Represents the height of the legend on the chart.|1.8|
|[chartLegend](../excel/chartlegend.md)|_Property_ > left|Represents the left of a chart legend.|1.8|
|[chartLegend](../excel/chartlegend.md)|_Property_ > top|Represents the top of a chart legend.|1.8|
|[chartLegend](../excel/chartlegend.md)|_Property_ > width|Represents the width of the legend on the chart.|1.8|
|[chartPointFormat](../excel/chartpointformat.md)|_Relationship_ > border|Represents the border format of a chart point, which includes border formating information. Read-only Read-only.|1.8|
|[chartPointsCollection](../excel/chartpointscollection.md)|_Method_ > [getFirst()](../excel/chartpointscollection.md#getfirst)|Gets the first point in the series.|1.7|
|[chartPointsCollection](../excel/chartpointscollection.md)|_Method_ > [getLast()](../excel/chartpointscollection.md#getlast)|Gets the last point in the series.|1.7|
|[chartSeries](../excel/chartseries.md)|_Relationship_ > trendlines|Represents a collection of Trendlines in the series. Read-only.|1.8|
|[chartSeries](../excel/chartseries.md)|_Method_ > [delete()](../excel/chartseries.md#delete)|Deletes the chart series.|1.8|
|[chartSeries](../excel/chartseries.md)|_Method_ > [setBubbleSizes(sourceData: Range)](../excel/chartseries.md#setbubblesizessourcedata-range)|Set bubble sizes for a chart series. Only works for bubble charts.|1.8|
|[chartSeries](../excel/chartseries.md)|_Method_ > [setValues(sourceData: Range)](../excel/chartseries.md#setvaluessourcedata-range)|Set values for a chart series. For scatter chart, it means Y axis values.|1.8|
|[chartSeries](../excel/chartseries.md)|_Method_ > [setXAxisValues(sourceData: Range)](../excel/chartseries.md#setxaxisvaluessourcedata-range)|Set values of X axis for a chart series. Only works for scatter charts.|1.8|
|[chartSeriesCollection](../excel/chartseriescollection.md)|_Method_ > [add(name: string, index: number)](../excel/chartseriescollection.md#addname-string-index-number)|Add a new series to the collection.|1.8|
|[chartSeriesCollection](../excel/chartseriescollection.md)|_Method_ > [getFirst()](../excel/chartseriescollection.md#getfirst)|Gets the first series in the collection.|1.7|
|[chartSeriesCollection](../excel/chartseriescollection.md)|_Method_ > [getLast()](../excel/chartseriescollection.md#getlast)|Gets the last series in the collection.|1.7|
|[chartTitle](../excel/charttitle.md)|_Property_ > height|Returns the height, in points, of the chart title. Read-only. Null if chart title's not visible. Read-only.|1.8|
|[chartTitle](../excel/charttitle.md)|_Property_ > horizontalAlignment|Represents the horizontal alignment for the specified objec Possible values are: Center, Left, Right, Justify, Distributed.|1.8|
|[chartTitle](../excel/charttitle.md)|_Property_ > left|Represents the distance, in points, from the left edge of chart title to the left edge of chart area. Null if chart title's not visible.|1.8|
|[chartTitle](../excel/charttitle.md)|_Property_ > top|Represents the distance, in points, from the top edge of chart title to the top of chart area. Null if chart title's not visible.|1.8|
|[chartTitle](../excel/charttitle.md)|_Property_ > verticalAlignment|Represents the vertical alignment of chart title. Possible values are: Center, Bottom, Top, Justify, Distributed.|1.8|
|[chartTitle](../excel/charttitle.md)|_Property_ > width|Returns the width, in points, of the chart title. Read-only. Null if chart title's not visible. Read-only.|1.8|
|[chartTitle](../excel/charttitle.md)|_Method_ > [getSubstring(start: number, start: number)](../excel/charttitle.md#getsubstringstart-number-start-number)|Get the characters of a chart title. Line break '\n' also counts one charater.|1.8|
|[chartTitle](../excel/charttitle.md)|_Method_ > [setFormula(formula: string)](../excel/charttitle.md#setformulaformula-string)|Sets a string value that represents the formula of chart title using A1-style notation.|1.8|
|[chartTrendline](../excel/charttrendline.md)|_Property_ > displayEquation|True if the equation for the trendline is displayed on the chart.|1.8|
|[chartTrendline](../excel/charttrendline.md)|_Property_ > displayRSquared|True if the R-squared for the trendline is displayed on the chart.|1.8|
|[chartTrendline](../excel/charttrendline.md)|_Property_ > movingAveragePeriod|Represents the MovingAveragePeriod of a chart trendline, specific for trendline with MovingAverage type.|1.8|
|[chartTrendline](../excel/charttrendline.md)|_Property_ > polynomialOrder|Represents the PolynomialOrder of a chart trendline, specific for trendline with Polynomial type.|1.8|
|[chartTrendline](../excel/charttrendline.md)|_Property_ > type|Represents the type of a chart trendline. Possible values are: Linear, Expontential, Logarithmic, MovingAvg, Polynomial, Power.|1.8|
|[chartTrendline](../excel/charttrendline.md)|_Relationship_ > format|Represents the formatting of a chart trendline. Read-only.|1.8|
|[chartTrendlineCollection](../excel/charttrendlinecollection.md)|_Property_ > items|A collection of chartTrendline objects. Read-only.|1.8|
|[chartTrendlineCollection](../excel/charttrendlinecollection.md)|_Method_ > [add(type: string)](../excel/charttrendlinecollection.md#addtype-string)|Adds a new trendline to trendline collection.|1.8|
|[chartTrendlineCollection](../excel/charttrendlinecollection.md)|_Method_ > [getCount()](../excel/charttrendlinecollection.md#getcount)|Returns the number of trendlines in the collection.|1.8|
|[chartTrendlineFormat](../excel/charttrendlineformat.md)|_Relationship_ > line|Represents chart line formatting. Read-only.|1.8|
|[tableDataChangedEvent](../excel/tabledatachangedevent.md)|_Property_ > changeType|Gets the change type that represents how the DataChanged event is triggered. Possible values are: Others, RangeEdited, RowInserted, RowDeleted, ColumnInserted, ColumnDeleted, CellInserted, CellDeleted.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../excel/tabledatachangedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../excel/tabledatachangedevent.md)|_Property_ > source|Gets the source of the event. Possible values are: Local, Remote.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../excel/tabledatachangedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../excel/tabledatachangedevent.md)|_Relationship_ > range|Gets the range that represents the changed area of a table on a specific worksheet.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../excel/tabledatachangedevent.md)|_Relationship_ > table|Gets the table in which the data changed.|ApiSet.InProgressFeatures.Event|
|[tableSelectionChangedEvent](../excel/tableselectionchangedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[tableSelectionChangedEvent](../excel/tableselectionchangedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[tableSelectionChangedEvent](../excel/tableselectionchangedevent.md)|_Relationship_ > range|Gets the range that represents the selected area of the table on a specific worksheet.|ApiSet.InProgressFeatures.Event|
|[tableSelectionChangedEvent](../excel/tableselectionchangedevent.md)|_Relationship_ > table|Gets the table in which the selection changed.|ApiSet.InProgressFeatures.Event|
|[worksheetActivatedEvent](../excel/worksheetactivatedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetActivatedEvent](../excel/worksheetactivatedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetActivatedEvent](../excel/worksheetactivatedevent.md)|_Relationship_ > worksheet|Gets the worksheet that is activated.|ApiSet.InProgressFeatures.Event|
|[worksheetAddedEvent](../excel/worksheetaddedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetAddedEvent](../excel/worksheetaddedevent.md)|_Property_ > source|Gets the source of the event. Possible values are: Local, Remote.|ApiSet.InProgressFeatures.Event|
|[worksheetAddedEvent](../excel/worksheetaddedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetAddedEvent](../excel/worksheetaddedevent.md)|_Relationship_ > worksheet|Gets the worksheet that is added to the workbook.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../excel/worksheetdatachangedevent.md)|_Property_ > changeType|Gets the change type that represents how the DataChanged event is triggered. Possible values are: Others, RangeEdited, RowInserted, RowDeleted, ColumnInserted, ColumnDeleted, CellInserted, CellDeleted.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../excel/worksheetdatachangedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../excel/worksheetdatachangedevent.md)|_Property_ > source|Gets the source of the event. Possible values are: Local, Remote.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../excel/worksheetdatachangedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../excel/worksheetdatachangedevent.md)|_Relationship_ > range|Gets the range that represents the changed area of a specific worksheet.|ApiSet.InProgressFeatures.Event|
|[worksheetDeactivatedEvent](../excel/worksheetdeactivatedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetDeactivatedEvent](../excel/worksheetdeactivatedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetDeactivatedEvent](../excel/worksheetdeactivatedevent.md)|_Relationship_ > worksheet|Gets the worksheet that is deactivated.|ApiSet.InProgressFeatures.Event|
|[worksheetSelectionChangedEvent](../excel/worksheetselectionchangedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetSelectionChangedEvent](../excel/worksheetselectionchangedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetSelectionChangedEvent](../excel/worksheetselectionchangedevent.md)|_Relationship_ > range|Gets the range that represents the selected area of a specific worksheet.|ApiSet.InProgressFeatures.Event|
