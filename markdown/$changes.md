|Object| What is new| Description|Feedback|
|:----|:----|:----|:----|
|[chart](../markdown/chart.md)|_Property_ > chartType|Represents the type of the chart. Possible values are: ColumnClustered, ColumnStacked, ColumnStacked100, BarClustered, BarStacked, BarStacked100, LineStacked, LineStacked100, LineMarkers, LineMarkersStacked, LineMarkersStacked100, PieOfPie, etc..|1.7|
|[chart](../markdown/chart.md)|_Property_ > id|The unique id of chart. Read-only.|1.7|
|[chart](../markdown/chart.md)|_Property_ > showAllFieldButtons|Represents whether to display all field buttons on a PivotChart.|1.7|
|[chartAreaFormat](../markdown/chartareaformat.md)|_Relationship_ > border|Represents the border format of chart area, which includes color, linestyle and weight. Read-only.|1.7|
|[chartAxes](../markdown/chartaxes.md)|_Method_ > [getItem(type: string, group: string)](../markdown/chartaxes.md#getitemtype-string-group-string)|Returns the specific axis identified by type and group.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > axisBetweenCategories|Represents whether value axis crosses the category axis between categories.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > axisGroup|Represents the group for the specified axis. Read-only. Possible values are: Primary, Secondary.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > baseTimeUnit|Returns or sets the base unit for the specified category axis. Possible values are: Days, Months, Years.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > categoryType|Returns or sets the category axis type. Possible values are: Automatic, TextAxis, DateAxis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > crossesAt|Represents the specified axis where the other axis crosses at. Read Only. Set to this property should use SetCrossesAt(double) method. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > customDisplayUnit|Represents the custom axis display unit value. Read Only. To set this property, please use the SetCustomDisplayUnit(double) method. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > displayUnit|Represents the axis display unit. Possible values are: None, Hundreds, Thousands, TenThousands, HundredThousands, Millions, TenMillions, HundredMillons, Billions, Trillions, Custom.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > height|Represents the height, in points, of the chart axis. Null if the axis's not visible. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > left|Represents the distance, in points, from the left edge of the axis to the left of chart area. Null if the axis's not visible. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > logBase|Represents the base of the logarithm when using logarithmic scales.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > majorTimeUnitScale|Returns or sets the major unit scale value for the category axis when the CategoryType property is set to TimeScale. Possible values are: Days, Months, Years.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > minorTimeUnitScale|Returns or sets the minor unit scale value for the category axis when the CategoryType property is set to TimeScale. Possible values are: Days, Months, Years.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > reversePlotOrder|Represents whether Microsoft Excel plots data points from last to first.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > scaleType|Represents the value axis scale type. Possible values are: Linear, Logarithmic.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > showDisplayUnitLabel|Represents whether the axis display unit label is visible.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > tickLabelSpacing|Represents the number of categories or series between tick-mark labels. Can be a value from 1 through 31999 or an empty string for automatic setting. The returned value is always a number.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > tickMarkSpacing|Represents the number of categories or series between tick marks.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > top|Represents the distance, in points, from the top edge of the axis to the top of chart area. Null if the axis's not visible. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > type|Represents the axis type. Read-only. Possible values are: Invalid, Category, Value, SeriesAxis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > visible|A boolean value represents the visibility of the axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > width|Represents the width, in points, of the chart axis. Null if the axis's not visible. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > crosses|Represents the specified axis where the other axis crosses.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > majorTickMark|Represents the type of major tick mark for the specified axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > minorTickMark|Represents the type of minor tick mark for the specified axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > tickLabelPosition|Represents the position of tick-mark labels on the specified axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Method_ > [setCategoryNames(sourceData: Range)](../markdown/chartaxis.md#setcategorynamessourcedata-range)|Sets all the category names for the specified axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Method_ > [setCrossesAt(value: double)](../markdown/chartaxis.md#setcrossesatvalue-double)|Set the specified axis where the other axis crosses at.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Method_ > [setCustomDisplayUnit(value: double)](../markdown/chartaxis.md#setcustomdisplayunitvalue-double)|Sets the axis display unit to a custom value.|1.7|
|[chartBorder](../markdown/chartborder.md)|_Property_ > color|HTML color code representing the color of borders in the chart.|1.7|
|[chartBorder](../markdown/chartborder.md)|_Property_ > weight|Represents weight of the border, in points.|1.7|
|[chartBorder](../markdown/chartborder.md)|_Relationship_ > lineStyle|Represents the line style of the border.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > position|DataLabelPosition value that represents the position of the data label. Possible values are: None, Center, InsideEnd, InsideBase, OutsideEnd, Left, Right, Top, Bottom, BestFit, Callout.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > separator|String representing the separator used for the data label on a chart.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showBubbleSize|Boolean value representing if the data label bubble size is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showCategoryName|Boolean value representing if the data label category name is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showLegendKey|Boolean value representing if the data label legend key is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showPercentage|Boolean value representing if the data label percentage is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showSeriesName|Boolean value representing if the data label series name is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showValue|Boolean value representing if the data label value is visible or not.|1.7|
|[chartFormatString](../markdown/chartformatstring.md)|_Relationship_ > font|Represents the font attributes, such as font name, font size, color, etc. of chart characters object. Read-only.|1.8|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > height|Represents the height of the legend on the chart.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > left|Represents the left of a chart legend.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > showShadow|Represents if the legend has shadow on the chart.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > top|Represents the top of a chart legend.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > width|Represents the width of the legend on the chart.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Relationship_ > legendEntries|Represents a collection of legendEntries in the legend. Read-only.|1.7|
|[chartLegendEntry](../markdown/chartlegendentry.md)|_Property_ > visible|Represents the visible of a chart legend entry.|1.7|
|[chartLegendEntryCollection](../markdown/chartlegendentrycollection.md)|_Property_ > items|A collection of chartLegendEntry objects. Read-only.|1.7|
|[chartLegendEntryCollection](../markdown/chartlegendentrycollection.md)|_Method_ > [getCount()](../markdown/chartlegendentrycollection.md#getcount)|Returns the number of legendEntry in the collection.|1.7|
|[chartLegendEntryCollection](../markdown/chartlegendentrycollection.md)|_Method_ > [getItemAt(index: number)](../markdown/chartlegendentrycollection.md#getitematindex-number)|Returns a legendEntry at the given index.|1.7|
|[chartLineFormat](../markdown/chartlineformat.md)|_Property_ > weight|Represents weight of the line, in points.|1.7|
|[chartLineFormat](../markdown/chartlineformat.md)|_Relationship_ > lineStyle|Represents the line style.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > hasDataLabel|Represents whether a data point has datalabel. Not applicable for surface charts.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > markerBackgroundColor|HTML color code representation of the marker background color of data point. E.g. #FF0000 represents Red.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > markerForegroundColor|HTML color code representation of the marker foreground color of data point. E.g. #FF0000 represents Red.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > markerSize|Represents marker size of data point.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > markerStyle|Represents marker style of a chart data point. Possible values are: Automatic, None, Square, Diamond, Triangle, X, Star, Dot, Dash, Circle, Plus, Picture.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Relationship_ > dataLabel|Returns the data label of a chart point. Read-only.|1.7|
|[chartPointFormat](../markdown/chartpointformat.md)|_Relationship_ > border|Represents the border format of a chart data point, which includes color, style and weight information. Read-only.|1.7|
|[chartPointsCollection](../markdown/chartpointscollection.md)|_Method_ > [getFirst()](../markdown/chartpointscollection.md#getfirst)|Gets the first point in the series.|1.7|
|[chartPointsCollection](../markdown/chartpointscollection.md)|_Method_ > [getLast()](../markdown/chartpointscollection.md#getlast)|Gets the last point in the series.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > chartType|Represents the chart type of a series. Possible values are: ColumnClustered, ColumnStacked, ColumnStacked100, BarClustered, BarStacked, BarStacked100, LineStacked, LineStacked100, LineMarkers, LineMarkersStacked, LineMarkersStacked100, PieOfPie, etc..|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > doughnutHoleSize|Represents the doughnut hole size of a chart series.  Only valid on doughnut and doughnutExploded charts.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > filtered|Boolean value representing if the series is filtered or not. Not applicable for surface charts.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > gapWidth|Represents the gap width of a chart series.  Only valid on bar and column charts, as well as|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > hasDataLabels|Boolean value representing if the series has data labels or not.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > markerBackgroundColor|Represents markers background color of a chart series.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > markerForegroundColor|Represents markers foreground color of a chart series.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > markerSize|Represents marker size of a chart series.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > markerStyle|Represents marker style of a chart series. Possible values are: Automatic, None, Square, Diamond, Triangle, X, Star, Dot, Dash, Circle, Plus, Picture.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > plotOrder|Represents the plot order of a chart series within the chart group.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > showShadow|Boolean value representing if the series has shadow or not.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > smooth|Boolean value representing if the series is smooth or not. Only for line and scatter charts.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Relationship_ > trendlines|Represents a collection of trendlines in the series. Read-only.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Method_ > [delete()](../markdown/chartseries.md#delete)|Deletes the chart series.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Method_ > [setBubbleSizes(sourceData: Range)](../markdown/chartseries.md#setbubblesizessourcedata-range)|Set bubble sizes for a chart series. Only works for bubble charts.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Method_ > [setValues(sourceData: Range)](../markdown/chartseries.md#setvaluessourcedata-range)|Set values for a chart series. For scatter chart, it means Y axis values.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Method_ > [setXAxisValues(sourceData: Range)](../markdown/chartseries.md#setxaxisvaluessourcedata-range)|Set values of X axis for a chart series. Only works for scatter charts.|1.7|
|[chartSeriesCollection](../markdown/chartseriescollection.md)|_Method_ > [add(name: string, index: number)](../markdown/chartseriescollection.md#addname-string-index-number)|Add a new series to the collection.|1.7|
|[chartSeriesCollection](../markdown/chartseriescollection.md)|_Method_ > [getFirst()](../markdown/chartseriescollection.md#getfirst)|Gets the first series in the collection.|ApiSet.InProgressFeatures.GetFirstGetLast|
|[chartSeriesCollection](../markdown/chartseriescollection.md)|_Method_ > [getLast()](../markdown/chartseriescollection.md#getlast)|Gets the last series in the collection.|ApiSet.InProgressFeatures.GetFirstGetLast|
|[chartTitle](../markdown/charttitle.md)|_Property_ > height|Returns the height, in points, of the chart title. Read-only. Null if chart title's not visible. Read-only.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Property_ > horizontalAlignment|Represents the horizontal alignment for chart title. Possible values are: Center, Left, Right, Justify, Distributed.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Property_ > left|Represents the distance, in points, from the left edge of chart title to the left edge of chart area. Null if chart title's not visible.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Property_ > showShadow|Represents a boolean value that determines if the chart title has a shadow.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Property_ > textOrientation|Represents the text orientation of chart title. The value should be an integer either from -90 to 90, or 180 for vertically-oriented text.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Property_ > top|Represents the distance, in points, from the top edge of chart title to the top of chart area. Null if chart title's not visible.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Property_ > verticalAlignment|Represents the vertical alignment of chart title. Possible values are: Center, Bottom, Top, Justify, Distributed.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Property_ > width|Returns the width, in points, of the chart title. Read-only. Null if chart title's not visible. Read-only.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Relationship_ > position|Represents the position of chart title.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Method_ > [getSubstring(start: number, length: number)](../markdown/charttitle.md#getsubstringstart-number-length-number)|Get the substring of a chart title. Line break '\n' also counts one charater.|ApiSet.InProgressFeatures.ChartingAPI|
|[chartTitle](../markdown/charttitle.md)|_Method_ > [setFormula(formula: string)](../markdown/charttitle.md#setformulaformula-string)|Sets a string value that represents the formula of chart title using A1-style notation.|1.7|
|[chartTitleFormat](../markdown/charttitleformat.md)|_Relationship_ > border|Represents the border format of chart title, which includes color, linestyle and weight. Read-only.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > backward|Represents the number of periods that the trendline extends backward.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > displayEquation|True if the equation for the trendline is displayed on the chart.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > displayRSquared|True if the R-squared for the trendline is displayed on the chart.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > forward|Represents the number of periods that the trendline extends forward.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > intercept|Represents the intercept value of the trendline. Can be set to a numeric value or an empty string (for automatic values). The returned value is always a number.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > movingAveragePeriod|Represents the period of a chart trendline, only for trendline with MovingAverage type.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > name|Represents the name of the trendline. Can be set to a string value, or can be set to null value represents automatic values. The returned value is always a string|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > polynomialOrder|Represents the order of a chart trendline, only for trendline with Polynomial type.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > type|Represents the type of a chart trendline. Possible values are: Linear, Expontential, Logarithmic, MovingAvg, Polynomial, Power.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Relationship_ > format|Represents the formatting of a chart trendline. Read-only.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Method_ > [delete()](../markdown/charttrendline.md#delete)|Delete the trendline object.|1.7|
|[chartTrendlineCollection](../markdown/charttrendlinecollection.md)|_Property_ > items|A collection of chartTrendline objects. Read-only.|1.7|
|[chartTrendlineCollection](../markdown/charttrendlinecollection.md)|_Method_ > [add(type: string)](../markdown/charttrendlinecollection.md#addtype-string)|Adds a new trendline to trendline collection.|1.7|
|[chartTrendlineCollection](../markdown/charttrendlinecollection.md)|_Method_ > [getCount()](../markdown/charttrendlinecollection.md#getcount)|Returns the number of trendlines in the collection.|1.7|
|[chartTrendlineCollection](../markdown/charttrendlinecollection.md)|_Method_ > [getItem(index: number)](../markdown/charttrendlinecollection.md#getitemindex-number)|Get trendline object by index, which is the insertion order in items array.|1.7|
|[chartTrendlineFormat](../markdown/charttrendlineformat.md)|_Relationship_ > line|Represents chart line formatting. Read-only.|1.7|
|[tableDataChangedEvent](../markdown/tabledatachangedevent.md)|_Property_ > changeType|Gets the change type that represents how the DataChanged event is triggered. Possible values are: Others, RangeEdited, RowInserted, RowDeleted, ColumnInserted, ColumnDeleted, CellInserted, CellDeleted.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../markdown/tabledatachangedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../markdown/tabledatachangedevent.md)|_Property_ > source|Gets the source of the event. Possible values are: Local, Remote.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../markdown/tabledatachangedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../markdown/tabledatachangedevent.md)|_Relationship_ > range|Gets the range that represents the changed area of a table on a specific worksheet.|ApiSet.InProgressFeatures.Event|
|[tableDataChangedEvent](../markdown/tabledatachangedevent.md)|_Relationship_ > table|Gets the table in which the data changed.|ApiSet.InProgressFeatures.Event|
|[tableSelectionChangedEvent](../markdown/tableselectionchangedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[tableSelectionChangedEvent](../markdown/tableselectionchangedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[tableSelectionChangedEvent](../markdown/tableselectionchangedevent.md)|_Relationship_ > range|Gets the range that represents the selected area of the table on a specific worksheet.|ApiSet.InProgressFeatures.Event|
|[tableSelectionChangedEvent](../markdown/tableselectionchangedevent.md)|_Relationship_ > table|Gets the table in which the selection changed.|ApiSet.InProgressFeatures.Event|
|[worksheetActivatedEvent](../markdown/worksheetactivatedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetActivatedEvent](../markdown/worksheetactivatedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetActivatedEvent](../markdown/worksheetactivatedevent.md)|_Relationship_ > worksheet|Gets the worksheet that is activated.|ApiSet.InProgressFeatures.Event|
|[worksheetAddedEvent](../markdown/worksheetaddedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetAddedEvent](../markdown/worksheetaddedevent.md)|_Property_ > source|Gets the source of the event. Possible values are: Local, Remote.|ApiSet.InProgressFeatures.Event|
|[worksheetAddedEvent](../markdown/worksheetaddedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetAddedEvent](../markdown/worksheetaddedevent.md)|_Relationship_ > worksheet|Gets the worksheet that is added to the workbook.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../markdown/worksheetdatachangedevent.md)|_Property_ > changeType|Gets the change type that represents how the DataChanged event is triggered. Possible values are: Others, RangeEdited, RowInserted, RowDeleted, ColumnInserted, ColumnDeleted, CellInserted, CellDeleted.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../markdown/worksheetdatachangedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../markdown/worksheetdatachangedevent.md)|_Property_ > source|Gets the source of the event. Possible values are: Local, Remote.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../markdown/worksheetdatachangedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetDataChangedEvent](../markdown/worksheetdatachangedevent.md)|_Relationship_ > range|Gets the range that represents the changed area of a specific worksheet.|ApiSet.InProgressFeatures.Event|
|[worksheetDeactivatedEvent](../markdown/worksheetdeactivatedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetDeactivatedEvent](../markdown/worksheetdeactivatedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetDeactivatedEvent](../markdown/worksheetdeactivatedevent.md)|_Relationship_ > worksheet|Gets the worksheet that is deactivated.|ApiSet.InProgressFeatures.Event|
|[worksheetSelectionChangedEvent](../markdown/worksheetselectionchangedevent.md)|_Property_ > context|Gets the context object that facilitates requests to the Excel application.|ApiSet.InProgressFeatures.Event|
|[worksheetSelectionChangedEvent](../markdown/worksheetselectionchangedevent.md)|_Property_ > type|Gets the type of the event. Possible values are: WorksheetDataChanged, WorksheetSelectionChanged, WorksheetAdded, WorksheetActivated, WorksheetDeactivated, TableDataChanged, TableSelectionChanged.|ApiSet.InProgressFeatures.Event|
|[worksheetSelectionChangedEvent](../markdown/worksheetselectionchangedevent.md)|_Relationship_ > range|Gets the range that represents the selected area of a specific worksheet.|ApiSet.InProgressFeatures.Event|
