|Object| What is new| Description|Req. Set|
|:----|:----|:----|:----|
|[chart](../markdown/chart.md)|_Property_ > categoryLabelLevel|Returns or sets a ChartCategoryLabelLevel enumeration constant referring to the level of where the category labels are being sourced from. ReadWrite.|1.8|
|[chart](../markdown/chart.md)|_Property_ > chartType|Represents the type of the chart. Possible values are: ColumnClustered, ColumnStacked, ColumnStacked100, BarClustered, BarStacked, BarStacked100, LineStacked, LineStacked100, LineMarkers, LineMarkersStacked, LineMarkersStacked100, PieOfPie, etc..|1.7|
|[chart](../markdown/chart.md)|_Property_ > colorScheme|Returns or sets an integer that represents the color scheme for the chart. ReadWrite.|1.8|
|[chart](../markdown/chart.md)|_Property_ > displayBlanksAs|Returns or sets the way that blank cells are plotted on a chart. ReadWrite. Possible values are: NotPlotted, Zero, Interplotted.|1.8|
|[chart](../markdown/chart.md)|_Property_ > id|The unique id of chart. Read-only.|1.7|
|[chart](../markdown/chart.md)|_Property_ > plotBy|Returns or sets the way columns or rows are used as data series on the chart. ReadWrite. Possible values are: Rows, Columns.|1.8|
|[chart](../markdown/chart.md)|_Property_ > plotVisibleOnly|True if only visible cells are plotted. False if both visible and hidden cells are plotted. ReadWrite.|1.8|
|[chart](../markdown/chart.md)|_Property_ > roundedCorners|True if the chart area of the chart has rounded corners. ReadWrite.|1.8|
|[chart](../markdown/chart.md)|_Property_ > seriesNameLevel|Returns or sets a ChartSeriesNameLevel enumeration constant referring to|1.8|
|[chart](../markdown/chart.md)|_Property_ > showAllFieldButtons|Represents whether to display all field buttons on a PivotChart.|1.7|
|[chart](../markdown/chart.md)|_Property_ > showAxisFieldButtons|Represents whether to display axis field buttons on a PivotChart. The ShowAxisFieldButtons property corresponds to the Show Axis Field Buttons command on the Field Buttons drop-down list of the Analyze tab, which is available when a PivotChart is selected.|1.8|
|[chart](../markdown/chart.md)|_Property_ > showDataLabelsOverMaximum|Represents whether to to show the data labels when the value is greater than the maximum value on the value axis. If value axis became smaller than the size of data points, you can use this property to set whether to show the data labels. This property applies to 2-D charts only.|1.8|
|[chart](../markdown/chart.md)|_Property_ > showLegendFieldButtons|Represents whether to display legend field buttons on a PivotChart.|1.8|
|[chart](../markdown/chart.md)|_Property_ > showReportFilterFieldButtons|Represents whether to display report filter field buttons on a PivotChart.|1.8|
|[chart](../markdown/chart.md)|_Property_ > showValueFieldButtons|Represents whether to display show value field buttons on a PivotChart.|1.8|
|[chart](../markdown/chart.md)|_Property_ > style|Returns or sets the chart style for the chart. ReadWrite.|1.8|
|[chart](../markdown/chart.md)|_Relationship_ > plotArea|Represents the plotArea for the chart. Read-only.|1.8|
|[chartAreaFormat](../markdown/chartareaformat.md)|_Relationship_ > border|Represents the border format of chart area, which includes color, linestyle and weight. Read-only.|1.7|
|[chartAxes](../markdown/chartaxes.md)|_Method_ > [getItem(type: string, group: string)](../markdown/chartaxes.md#getitemtype-string-group-string)|Returns the specific axis identified by type and group.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > baseTimeUnit|Returns or sets the base unit for the specified category axis. Possible values are: Days, Months, Years.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > categoryType|Returns or sets the category axis type. Possible values are: Automatic, TextAxis, DateAxis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > customDisplayUnit|Represents the custom axis display unit value. Read Only. To set this property, please use the SetCustomDisplayUnit(double) method. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > displayUnit|Represents the axis display unit. Possible values are: None, Hundreds, Thousands, TenThousands, HundredThousands, Millions, TenMillions, HundredMillons, Billions, Trillions, Custom.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > height|Represents the height, in points, of the chart axis. Null if the axis's not visible. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > isBetweenCategories|Represents whether value axis crosses the category axis between categories.|1.8|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > left|Represents the distance, in points, from the left edge of the axis to the left of chart area. Null if the axis's not visible. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > logBase|Represents the base of the logarithm when using logarithmic scales.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > majorTimeUnitScale|Returns or sets the major unit scale value for the category axis when the CategoryType property is set to TimeScale. Possible values are: Days, Months, Years.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > minorTimeUnitScale|Returns or sets the minor unit scale value for the category axis when the CategoryType property is set to TimeScale. Possible values are: Days, Months, Years.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > multiLevel|Represents whether an axis is multilevel or not.|1.8|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > numberFormat|Represents the format code for the axis tick label.|1.8|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > numberFormatLinked|Represents whether the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells).|1.8|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > offset|Represents the distance between the levels of labels, and the distance between the first level and the axis line. The value should be an integer from 0 to 1000.|1.8|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > positionAt|Represents the specified axis position where the other axis crosses at. Read Only. Set to this property should use SetPositionAt(double) method. Read-only.|1.8|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > reversePlotOrder|Represents whether Microsoft Excel plots data points from last to first.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > showDisplayUnitLabel|Represents whether the axis display unit label is visible.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > textOrientation|Represents the text orientation of the axis tick label. The value should be an integer either from -90 to 90, or 180 for vertically-oriented text.|1.8|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > tickLabelSpacing|Represents the number of categories or series between tick-mark labels. Can be a value from 1 through 31999 or an empty string for automatic setting. The returned value is always a number.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > tickMarkSpacing|Represents the number of categories or series between tick marks.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > top|Represents the distance, in points, from the top edge of the axis to the top of chart area. Null if the axis's not visible. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > visible|A boolean value represents the visibility of the axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Property_ > width|Represents the width, in points, of the chart axis. Null if the axis's not visible. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > alignment|Represents the alignment for the specified axis tick label. Possible values are: Center, Left, Right, Justify, Distributed.|1.8|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > axisGroup|Represents the group for the specified axis. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > majorTickMark|Represents the type of major tick mark for the specified axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > minorTickMark|Represents the type of minor tick mark for the specified axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > position|Represents the specified axis position where the other axis crosses.|1.8|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > scaleType|Represents the value axis scale type.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > tickLabelPosition|Represents the position of tick-mark labels on the specified axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Relationship_ > type|Represents the axis type. Read-only.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Method_ > [setCategoryNames(sourceData: Range)](../markdown/chartaxis.md#setcategorynamessourcedata-range)|Sets all the category names for the specified axis.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Method_ > [setCustomDisplayUnit(value: double)](../markdown/chartaxis.md#setcustomdisplayunitvalue-double)|Sets the axis display unit to a custom value.|1.7|
|[chartAxis](../markdown/chartaxis.md)|_Method_ > [setPositionAt(value: double)](../markdown/chartaxis.md#setpositionatvalue-double)|Set the specified axis position where the other axis crosses at.|1.8|
|[chartAxisFormat](../markdown/chartaxisformat.md)|_Relationship_ > fill|Represents chart fill formatting. Read-only.|1.8|
|[chartAxisTitle](../markdown/chartaxistitle.md)|_Method_ > [setFormula(formula: string)](../markdown/chartaxistitle.md#setformulaformula-string)|A string value that represents the formula of chart axis title using A1-style notation.|1.8|
|[chartAxisTitleFormat](../markdown/chartaxistitleformat.md)|_Relationship_ > border|Represents the border format, which includes color, linestyle and weight. Read-only.|1.8|
|[chartAxisTitleFormat](../markdown/chartaxistitleformat.md)|_Relationship_ > fill|Represents chart fill formatting. Read-only.|1.8|
|[chartBorder](../markdown/chartborder.md)|_Property_ > color|HTML color code representing the color of borders in the chart.|1.7|
|[chartBorder](../markdown/chartborder.md)|_Property_ > weight|Represents weight of the border, in points.|1.7|
|[chartBorder](../markdown/chartborder.md)|_Relationship_ > lineStyle|Represents the line style of the border.|1.7|
|[chartBorder](../markdown/chartborder.md)|_Method_ > [clear()](../markdown/chartborder.md#clear)|Clear the border format of a chart element.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > autoText|Boolean value representing if data label automatically generates appropriate text based on context.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > formula|String value that represents the formula of chart data label using A1-style notation.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > height|Returns the height, in points, of the chart data label. Read-only. Null if chart data label is not visible. Read-only.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > horizontalAlignment|Represents the horizontal alignment for chart data label. Possible values are: Center, Left, Right, Justify, Distributed.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > left|Represents the distance, in points, from the left edge of chart data label to the left edge of chart area. Null if chart data label is not visible.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > numberFormat|String value that represents the format code for data label.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > numberFormatLinked|Boolean value representing if the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells).|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > position|DataLabelPosition value that represents the position of the data label. Possible values are: None, Center, InsideEnd, InsideBase, OutsideEnd, Left, Right, Top, Bottom, BestFit, Callout.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > separator|String representing the separator used for the data label on a chart.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showBubbleSize|Boolean value representing if the data label bubble size is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showCategoryName|Boolean value representing if the data label category name is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showLegendKey|Boolean value representing if the data label legend key is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showPercentage|Boolean value representing if the data label percentage is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showSeriesName|Boolean value representing if the data label series name is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > showValue|Boolean value representing if the data label value is visible or not.|1.7|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > text|String representing the text of the data label on a chart.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > textOrientation|Represents the text orientation of chart data label. The value should be an integer either from -90 to 90, or 180 for vertically-oriented text.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > top|Represents the distance, in points, from the top edge of chart data label to the top of chart area. Null if chart data label is not visible.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > verticalAlignment|Represents the vertical alignment of chart data label. Possible values are: Center, Bottom, Top, Justify, Distributed.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Property_ > width|Returns the width, in points, of the chart data label. Read-only. Null if chart data label is not visible. Read-only.|1.8|
|[chartDataLabel](../markdown/chartdatalabel.md)|_Relationship_ > format|Represents the format of chart data label. Read-only.|1.8|
|[chartDataLabelFormat](../markdown/chartdatalabelformat.md)|_Relationship_ > border|Represents the border format, which includes color, linestyle and weight. Read-only.|1.8|
|[chartDataLabels](../markdown/chartdatalabels.md)|_Property_ > autoText|Represents whether data labels automatically generates appropriate text based on context.|1.8|
|[chartDataLabels](../markdown/chartdatalabels.md)|_Property_ > horizontalAlignment|Represents the horizontal alignment for chart data label. Possible values are: Center, Left, Right, Justify, Distributed.|1.8|
|[chartDataLabels](../markdown/chartdatalabels.md)|_Property_ > numberFormat|Represents the format code for data labels.|1.8|
|[chartDataLabels](../markdown/chartdatalabels.md)|_Property_ > numberFormatLinked|Represents whether the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells).|1.8|
|[chartDataLabels](../markdown/chartdatalabels.md)|_Property_ > textOrientation|Represents the text orientation of data labels. The value should be an integer either from -90 to 90, or 180 for vertically-oriented text.|1.8|
|[chartDataLabels](../markdown/chartdatalabels.md)|_Property_ > verticalAlignment|Represents the vertical alignment of chart data label. Possible values are: Center, Bottom, Top, Justify, Distributed.|1.8|
|[chartErrorBars](../markdown/charterrorbars.md)|_Property_ > endStyleCap|Represents whether have the end style cap for the error bars.|1.8|
|[chartErrorBars](../markdown/charterrorbars.md)|_Property_ > visible|Represents whether shown error bars.|1.8|
|[chartErrorBars](../markdown/charterrorbars.md)|_Relationship_ > format|Represents the formatting of chart ErrorBars. Read-only.|1.8|
|[chartErrorBars](../markdown/charterrorbars.md)|_Relationship_ > include|Represents which error-bar parts to include.|1.8|
|[chartErrorBars](../markdown/charterrorbars.md)|_Relationship_ > type|Represents the range marked by error bars.|1.8|
|[chartErrorBarsFormat](../markdown/charterrorbarsformat.md)|_Relationship_ > line|Represents chart line formatting. Read-only.|1.8|
|[chartFormatString](../markdown/chartformatstring.md)|_Relationship_ > font|Represents the font attributes, such as font name, font size, color, etc. of chart characters object. Read-only.|1.8|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > height|Represents the height of the legend on the chart.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > left|Represents the left of a chart legend.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > showShadow|Represents if the legend has shadow on the chart.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > top|Represents the top of a chart legend.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Property_ > width|Represents the width of the legend on the chart.|1.7|
|[chartLegend](../markdown/chartlegend.md)|_Relationship_ > legendEntries|Represents a collection of legendEntries in the legend. Read-only.|1.7|
|[chartLegendEntry](../markdown/chartlegendentry.md)|_Property_ > height|Represents the height of the legendEntry on the chart Legend. Read-only.|1.8|
|[chartLegendEntry](../markdown/chartlegendentry.md)|_Property_ > index|Represents the index of the LegendEntry in the Chart Legend. Read-only.|1.8|
|[chartLegendEntry](../markdown/chartlegendentry.md)|_Property_ > left|Represents the left of a chart legendEntry. Read-only.|1.8|
|[chartLegendEntry](../markdown/chartlegendentry.md)|_Property_ > top|Represents the top of a chart legendEntry. Read-only.|1.8|
|[chartLegendEntry](../markdown/chartlegendentry.md)|_Property_ > visible|Represents the visible of a chart legend entry.|1.7|
|[chartLegendEntry](../markdown/chartlegendentry.md)|_Property_ > width|Represents the width of the legendEntry on the chart Legend. Read-only.|1.8|
|[chartLegendEntryCollection](../markdown/chartlegendentrycollection.md)|_Property_ > items|A collection of chartLegendEntry objects. Read-only.|1.7|
|[chartLegendEntryCollection](../markdown/chartlegendentrycollection.md)|_Method_ > [getCount()](../markdown/chartlegendentrycollection.md#getcount)|Returns the number of legendEntry in the collection.|1.7|
|[chartLegendEntryCollection](../markdown/chartlegendentrycollection.md)|_Method_ > [getItemAt(index: number)](../markdown/chartlegendentrycollection.md#getitematindex-number)|Returns a legendEntry at the given index.|1.7|
|[chartLegendFormat](../markdown/chartlegendformat.md)|_Relationship_ > border|Represents the border format, which includes color, linestyle and weight. Read-only.|1.8|
|[chartLineFormat](../markdown/chartlineformat.md)|_Property_ > weight|Represents weight of the line, in points.|1.7|
|[chartLineFormat](../markdown/chartlineformat.md)|_Relationship_ > lineStyle|Represents the line style.|1.7|
|[chartPlotArea](../markdown/chartplotarea.md)|_Property_ > height|Represents the height value of plotArea.|1.8|
|[chartPlotArea](../markdown/chartplotarea.md)|_Property_ > insideHeight|Represents the insideHeight value of plotArea.|1.8|
|[chartPlotArea](../markdown/chartplotarea.md)|_Property_ > insideLeft|Represents the insideLeft value of plotArea.|1.8|
|[chartPlotArea](../markdown/chartplotarea.md)|_Property_ > insideTop|Represents the insideTop value of plotArea.|1.8|
|[chartPlotArea](../markdown/chartplotarea.md)|_Property_ > insideWidth|Represents the insideWidth value of plotArea.|1.8|
|[chartPlotArea](../markdown/chartplotarea.md)|_Property_ > left|Represents the left value of plotArea.|1.8|
|[chartPlotArea](../markdown/chartplotarea.md)|_Property_ > top|Represents the top value of plotArea.|1.8|
|[chartPlotArea](../markdown/chartplotarea.md)|_Property_ > width|Represents the width value of plotArea.|1.8|
|[chartPlotArea](../markdown/chartplotarea.md)|_Relationship_ > format|Represents the formatting of a chart plotArea. Read-only.|1.8|
|[chartPlotArea](../markdown/chartplotarea.md)|_Relationship_ > position|Represents the position of plotArea.|1.8|
|[chartPlotAreaFormat](../markdown/chartplotareaformat.md)|_Relationship_ > border|Represents the border attributes of a chart plotArea. Read-only.|1.8|
|[chartPlotAreaFormat](../markdown/chartplotareaformat.md)|_Relationship_ > fill|Represents the fill format of an object, which includes background formating information. Read-only.|1.8|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > hasDataLabel|Represents whether a data point has datalabel. Not applicable for surface charts.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > markerBackgroundColor|HTML color code representation of the marker background color of data point. E.g. #FF0000 represents Red.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > markerForegroundColor|HTML color code representation of the marker foreground color of data point. E.g. #FF0000 represents Red.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > markerSize|Represents marker size of data point.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Property_ > markerStyle|Represents marker style of a chart data point. Possible values are: Automatic, None, Square, Diamond, Triangle, X, Star, Dot, Dash, Circle, Plus, Picture.|1.7|
|[chartPoint](../markdown/chartpoint.md)|_Relationship_ > dataLabel|Returns the data label of a chart point. Read-only.|1.7|
|[chartPointFormat](../markdown/chartpointformat.md)|_Relationship_ > border|Represents the border format of a chart data point, which includes color, style and weight information. Read-only.|1.7|
|[chartPointsCollection](../markdown/chartpointscollection.md)|_Method_ > [getFirst()](../markdown/chartpointscollection.md#getfirst)|Gets the first point in the series.|1.7|
|[chartPointsCollection](../markdown/chartpointscollection.md)|_Method_ > [getLast()](../markdown/chartpointscollection.md#getlast)|Gets the last point in the series.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > axisGroup|Returns or sets the group for the specified series. ReadWrite Possible values are: Primary, Secondary.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > bubbleScale|Returns or sets the scale factor for bubbles in the specified chart group. Can be an integer value from 0 (zero) to 300, corresponding to a percentage of the default size. Applies only to bubble charts. ReadWrite.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > chartType|Represents the chart type of a series. Possible values are: ColumnClustered, ColumnStacked, ColumnStacked100, BarClustered, BarStacked, BarStacked100, LineStacked, LineStacked100, LineMarkers, LineMarkersStacked, LineMarkersStacked100, PieOfPie, etc..|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > doughnutHoleSize|Represents the doughnut hole size of a chart series.  Only valid on doughnut and doughnutExploded charts.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > explosion|Returns or sets the explosion value for a pie-chart or doughnut-chart slice. Returns 0 (zero) if there's no explosion (the tip of the slice is in the center of the pie). ReadWrite.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > filtered|Boolean value representing if the series is filtered or not. Not applicable for surface charts.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > firstSliceAngle|Returns or sets the angle of the first pie-chart or doughnut-chart slice, in degrees (clockwise from vertical). Applies only to pie, 3-D pie, and doughnut charts. Can be a value from 0 through 360. ReadWrite|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > gapWidth|Represents the gap width of a chart series.  Only valid on bar and column charts, as well as|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > hasDataLabels|Boolean value representing if the series has data labels or not.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > hasLeaderLines|True if Microsoft Excel show leaderlines for each datalabel in series. ReadWrite.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > invertIfNegative|True if Microsoft Excel inverts the pattern in the item when it corresponds to a negative number. ReadWrite.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > markerBackgroundColor|Represents markers background color of a chart series.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > markerForegroundColor|Represents markers foreground color of a chart series.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > markerSize|Represents marker size of a chart series.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > markerStyle|Represents marker style of a chart series. Possible values are: Automatic, None, Square, Diamond, Triangle, X, Star, Dot, Dash, Circle, Plus, Picture.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > overlap|Specifies how bars and columns are positioned. Can be a value between ╬ô├ç├┤ 100 and 100. Applies only to 2-D bar and 2-D column charts. ReadWrite.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > plotOrder|Represents the plot order of a chart series within the chart group.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > secondPlotSize|Returns or sets the size of the secondary section of either a pie of pie chart or a bar of pie chart, as a percentage of the size of the primary pie. Can be a value from 5 to 200. ReadWrite.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > showShadow|Boolean value representing if the series has shadow or not.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > smooth|Boolean value representing if the series is smooth or not. Only for line and scatter charts.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Property_ > splitType|Returns or sets the way the two sections of either a pie of pie chart or a bar of pie chart are split. ReadWrite. Possible values are: SplitByPosition, SplitByValue, SplitByPercentValue, SplitByCustomSplit.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > splitValue|Returns or sets the threshold value separating the two sections of either a pie of pie chart or a bar of pie chart. ReadWrite.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > type|Returns the value that represents the series type. Read-only. Possible values are: Column, Bar, Bar3D, Line, Pie, XYScatter, Area, Area3D, Doughnut, Radar, Surface3D, Column3D.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Property_ > varyByCategories|True if Microsoft Excel assigns a different color or pattern to each data marker. The chart must contain only one series. ReadWrite.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Relationship_ > dataLabels|Represents a collection of all dataLabels in the series. Read-only.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Relationship_ > trendlines|Represents a collection of trendlines in the series. Read-only.|1.7|
|[chartSeries](../markdown/chartseries.md)|_Relationship_ > xErrorBars|Represents the error bar object for a chart series. Read-only.|1.8|
|[chartSeries](../markdown/chartseries.md)|_Relationship_ > yErrorBars|Represents the error bar object for a chart series. Read-only.|1.8|
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
|[chartTitle](../markdown/charttitle.md)|_Method_ > [getSubstring(start: number, length: number)](../markdown/charttitle.md#getsubstringstart-number-length-number)|Get the substring of a chart title. Line break '\n' also counts one charater.|1.7|
|[chartTitle](../markdown/charttitle.md)|_Method_ > [setFormula(formula: string)](../markdown/charttitle.md#setformulaformula-string)|Sets a string value that represents the formula of chart title using A1-style notation.|1.7|
|[chartTitleFormat](../markdown/charttitleformat.md)|_Relationship_ > border|Represents the border format of chart title, which includes color, linestyle and weight. Read-only.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > backwardPeriod|Represents the number of periods that the trendline extends backward.|1.8|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > forwardPeriod|Represents the number of periods that the trendline extends forward.|1.8|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > intercept|Represents the intercept value of the trendline. Can be set to a numeric value or an empty string (for automatic values). The returned value is always a number.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > movingAveragePeriod|Represents the period of a chart trendline, only for trendline with MovingAverage type.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > name|Represents the name of the trendline. Can be set to a string value, or can be set to null value represents automatic values. The returned value is always a string|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > polynomialOrder|Represents the order of a chart trendline, only for trendline with Polynomial type.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > showEquation|True if the equation for the trendline is displayed on the chart.|1.8|
|[chartTrendline](../markdown/charttrendline.md)|_Property_ > showRSquared|True if the R-squared for the trendline is displayed on the chart.|1.8|
|[chartTrendline](../markdown/charttrendline.md)|_Relationship_ > format|Represents the formatting of a chart trendline. Read-only.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Relationship_ > label|Represents the label of a chart trendline. Read-only.|1.8|
|[chartTrendline](../markdown/charttrendline.md)|_Relationship_ > type|Represents the type of a chart trendline.|1.7|
|[chartTrendline](../markdown/charttrendline.md)|_Method_ > [delete()](../markdown/charttrendline.md#delete)|Delete the trendline object.|1.7|
|[chartTrendlineCollection](../markdown/charttrendlinecollection.md)|_Property_ > items|A collection of chartTrendline objects. Read-only.|1.7|
|[chartTrendlineCollection](../markdown/charttrendlinecollection.md)|_Method_ > [add(type: string)](../markdown/charttrendlinecollection.md#addtype-string)|Adds a new trendline to trendline collection.|1.7|
|[chartTrendlineCollection](../markdown/charttrendlinecollection.md)|_Method_ > [getCount()](../markdown/charttrendlinecollection.md#getcount)|Returns the number of trendlines in the collection.|1.7|
|[chartTrendlineCollection](../markdown/charttrendlinecollection.md)|_Method_ > [getItem(index: number)](../markdown/charttrendlinecollection.md#getitemindex-number)|Get trendline object by index, which is the insertion order in items array.|1.7|
|[chartTrendlineFormat](../markdown/charttrendlineformat.md)|_Relationship_ > line|Represents chart line formatting. Read-only.|1.7|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > autoText|Boolean value representing if trendline label automatically generates appropriate text based on context.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > formula|String value that represents the formula of chart trendline label using A1-style notation.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > height|Returns the height, in points, of the chart trendline label. Read-only. Null if chart trendline label is not visible. Read-only.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > horizontalAlignment|Represents the horizontal alignment for chart trendline label. Possible values are: Center, Left, Right, Justify, Distributed.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > left|Represents the distance, in points, from the left edge of chart trendline label to the left edge of chart area. Null if chart trendline label is not visible.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > numberFormat|String value that represents the format code for trendline label.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > numberFormatLinked|Boolean value representing if the number format is linked to the cells (so that the number format changes in the labels when it changes in the cells).|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > text|String representing the text of the trendline label on a chart.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > textOrientation|Represents the text orientation of chart trendline label. The value should be an integer either from -90 to 90, or 180 for vertically-oriented text.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > top|Represents the distance, in points, from the top edge of chart trendline label to the top of chart area. Null if chart trendline label is not visible.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > verticalAlignment|Represents the vertical alignment of chart trendline label. Possible values are: Center, Bottom, Top, Justify, Distributed.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Property_ > width|Returns the width, in points, of the chart trendline label. Read-only. Null if chart trendline label is not visible. Read-only.|1.8|
|[chartTrendlineLabel](../markdown/charttrendlinelabel.md)|_Relationship_ > format|Represents the format of chart trendline label. Read-only.|1.8|
|[chartTrendlineLabelFormat](../markdown/charttrendlinelabelformat.md)|_Relationship_ > border|Represents the border format, which includes color, linestyle and weight. Read-only.|1.8|
|[chartTrendlineLabelFormat](../markdown/charttrendlinelabelformat.md)|_Relationship_ > fill|Represents the fill format of the current chart trendline label. Read-only.|1.8|
|[chartTrendlineLabelFormat](../markdown/charttrendlinelabelformat.md)|_Relationship_ > font|Represents the font attributes (font name, font size, color, etc.) for a chart trendline label. Read-only.|1.8|
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
