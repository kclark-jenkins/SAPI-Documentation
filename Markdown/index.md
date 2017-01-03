## Classes

<dl>
<dt><a href="#Birt">Birt</a></dt>
<dd><p>Birt</p>
</dd>
<dt><a href="#BirtData">BirtData</a></dt>
<dd></dd>
<dt><a href="#BirtLabel">BirtLabel</a></dt>
<dd></dd>
<dt><a href="#BirtText">BirtText</a></dt>
<dd></dd>
<dt><a href="#BirtChart">BirtChart</a></dt>
<dd></dd>
<dt><a href="#BirtTable">BirtTable</a></dt>
<dd></dd>
<dt><a href="#BirtGrid">BirtGrid</a></dt>
<dd></dd>
<dt><a href="#BirtDataProperties">BirtDataProperties</a></dt>
<dd><p>BirtDataProperties</p>
</dd>
<dt><a href="#BirtLabelProperties">BirtLabelProperties</a></dt>
<dd><p>BirtLabelProperties</p>
</dd>
<dt><a href="#BirtTextProperties">BirtTextProperties</a></dt>
<dd><p>BirtTextProperties</p>
</dd>
<dt><a href="#BirtChartProperties">BirtChartProperties</a></dt>
<dd><p>BirtChartProperties</p>
</dd>
<dt><a href="#BirtTableProperties">BirtTableProperties</a></dt>
<dd><p>BirtTableProperties</p>
</dd>
<dt><a href="#BirtGridProperties">BirtGridProperties</a></dt>
<dd><p>BirtGridProperties</p>
</dd>
</dl>

## Functions

<dl>
<dt><a href="#getProperties">getProperties()</a> ⇒ <code><a href="#BirtDataProperties">BirtDataProperties</a></code></dt>
<dd><p>Properties for BirtData</p>
</dd>
<dt><a href="#getProperties">getProperties()</a></dt>
<dd><p>Properties for BirtLabel</p>
</dd>
<dt><a href="#getProperties">getProperties()</a> ⇒ <code><a href="#BirtTextProperties">BirtTextProperties</a></code></dt>
<dd><p>Properties for BirtText</p>
</dd>
<dt><a href="#getProperties">getProperties()</a> ⇒ <code><a href="#BirtChartProperties">BirtChartProperties</a></code></dt>
<dd><p>Properties for BirtChart</p>
</dd>
<dt><a href="#getProperties">getProperties()</a> ⇒ <code><a href="#BirtTableProperties">BirtTableProperties</a></code></dt>
<dd><p>Properties for BirtTable</p>
</dd>
<dt><a href="#getProperties">getProperties()</a> ⇒ <code><a href="#BirtGridProperties">BirtGridProperties</a></code></dt>
<dd><p>Properties for BirtGrid</p>
</dd>
<dt><a href="#getProperties">getProperties()</a> ⇒ <code>BirtItemProperties</code></dt>
<dd><p>Generic BIRT item properties</p>
</dd>
<dt><a href="#setProperties">setProperties(dataProperties)</a></dt>
<dd><p>Properties setter for BirtData object</p>
</dd>
<dt><a href="#setProperties">setProperties(labelProperties)</a></dt>
<dd><p>Properties setter for BirtLabel object</p>
</dd>
<dt><a href="#setProperties">setProperties(textProperties)</a></dt>
<dd><p>Properties setter for BirtText object</p>
</dd>
<dt><a href="#setProperties">setProperties(chartProperties)</a></dt>
<dd><p>Properties setter for BirtChart object</p>
</dd>
<dt><a href="#setProperties">setProperties(tableProperties)</a></dt>
<dd><p>Properties setter for BirtTable object</p>
</dd>
<dt><a href="#setProperties">setProperties(gridProperties)</a></dt>
<dd><p>Properties setter for BirtGrid object</p>
</dd>
<dt><a href="#initNewReport">initNewReport()</a></dt>
<dd><p>Creates a new empty report design</p>
</dd>
<dt><a href="#saveReport">saveReport(qualifiedReportName, overwrite)</a></dt>
<dd><p>Saves a report design in XML format to the defined iHub for report generation</p>
</dd>
<dt><a href="#listDataModels">listDataModels(qulifiedPath)</a> ⇒ <code>Object</code></dt>
<dd><p>Retireves a list of available data objects at the given location</p>
</dd>
</dl>

<a name="Birt"></a>

## Birt
Birt

**Kind**: global class  
<a name="new_Birt_new"></a>

### new Birt()
Class used for created BIRT items to be used in a report

<a name="BirtData"></a>

## BirtData
**Kind**: global class  
<a name="new_BirtData_new"></a>

### new BirtData(dataProperties)
Class used to create a BIRT Data Object connection definition


| Param |
| --- |
| dataProperties | 

<a name="BirtLabel"></a>

## BirtLabel
**Kind**: global class  
<a name="new_BirtLabel_new"></a>

### new BirtLabel(labelProperties)
Class used to create a label to be used in a report


| Param |
| --- |
| labelProperties | 

<a name="BirtText"></a>

## BirtText
**Kind**: global class  
<a name="new_BirtText_new"></a>

### new BirtText(textProperties)
Class used to create a text item to be used in a report


| Param |
| --- |
| textProperties | 

<a name="BirtChart"></a>

## BirtChart
**Kind**: global class  
<a name="new_BirtChart_new"></a>

### new BirtChart(chartProperties)
Class used to create a chart item to be used in a report


| Param |
| --- |
| chartProperties | 

<a name="BirtTable"></a>

## BirtTable
**Kind**: global class  
<a name="new_BirtTable_new"></a>

### new BirtTable(tableProperties)
Class used to create a table to be used in a report


| Param |
| --- |
| tableProperties | 

<a name="BirtGrid"></a>

## BirtGrid
**Kind**: global class  
<a name="new_BirtGrid_new"></a>

### new BirtGrid(gridProperties)
Class ussed to create a grid to be used in a report


| Param |
| --- |
| gridProperties | 

<a name="BirtDataProperties"></a>

## BirtDataProperties
BirtDataProperties

**Kind**: global class  
<a name="new_BirtDataProperties_new"></a>

### new BirtDataProperties()
Properties class for BirtData

<a name="BirtLabelProperties"></a>

## BirtLabelProperties
BirtLabelProperties

**Kind**: global class  
<a name="new_BirtLabelProperties_new"></a>

### new BirtLabelProperties()
Properties class for BirtLabel

<a name="BirtTextProperties"></a>

## BirtTextProperties
BirtTextProperties

**Kind**: global class  
<a name="new_BirtTextProperties_new"></a>

### new BirtTextProperties()
Properties class for BirtText

<a name="BirtChartProperties"></a>

## BirtChartProperties
BirtChartProperties

**Kind**: global class  
<a name="new_BirtChartProperties_new"></a>

### new BirtChartProperties()
Properties class for BirtChart

<a name="BirtTableProperties"></a>

## BirtTableProperties
BirtTableProperties

**Kind**: global class  
<a name="new_BirtTableProperties_new"></a>

### new BirtTableProperties()
Properties class for BirtTable

<a name="BirtGridProperties"></a>

## BirtGridProperties
BirtGridProperties

**Kind**: global class  
<a name="new_BirtGridProperties_new"></a>

### new BirtGridProperties()
Properties class for BirtGrid

<a name="getProperties"></a>

## getProperties() ⇒ <code>[BirtDataProperties](#BirtDataProperties)</code>
Properties for BirtData

**Kind**: global function  
**Returns**: <code>[BirtDataProperties](#BirtDataProperties)</code> - dataProperties  
**For**: BirtData  
<a name="getProperties"></a>

## getProperties()
Properties for BirtLabel

**Kind**: global function  
**For**: BirtLabel@ return {BirtLabelProperties} labelProperties  
<a name="getProperties"></a>

## getProperties() ⇒ <code>[BirtTextProperties](#BirtTextProperties)</code>
Properties for BirtText

**Kind**: global function  
**Returns**: <code>[BirtTextProperties](#BirtTextProperties)</code> - textProperties  
**For**: BirtText  
<a name="getProperties"></a>

## getProperties() ⇒ <code>[BirtChartProperties](#BirtChartProperties)</code>
Properties for BirtChart

**Kind**: global function  
**Returns**: <code>[BirtChartProperties](#BirtChartProperties)</code> - chartProperties  
**For**: BirtChart  
<a name="getProperties"></a>

## getProperties() ⇒ <code>[BirtTableProperties](#BirtTableProperties)</code>
Properties for BirtTable

**Kind**: global function  
**Returns**: <code>[BirtTableProperties](#BirtTableProperties)</code> - tableProperties  
**For**: BirtTable  
<a name="getProperties"></a>

## getProperties() ⇒ <code>[BirtGridProperties](#BirtGridProperties)</code>
Properties for BirtGrid

**Kind**: global function  
**Returns**: <code>[BirtGridProperties](#BirtGridProperties)</code> - gridProperties  
**For**: BirtGrid  
<a name="getProperties"></a>

## getProperties() ⇒ <code>BirtItemProperties</code>
Generic BIRT item properties

**Kind**: global function  
**Returns**: <code>BirtItemProperties</code> - birtItemProperties  
**For**: BirtItemProperties  
<a name="setProperties"></a>

## setProperties(dataProperties)
Properties setter for BirtData object

**Kind**: global function  
**For**: BirtData  

| Param | Type | Description |
| --- | --- | --- |
| dataProperties | <code>[BirtDataProperties](#BirtDataProperties)</code> | Argument 1 |

<a name="setProperties"></a>

## setProperties(labelProperties)
Properties setter for BirtLabel object

**Kind**: global function  
**For**: BirtLabel  

| Param | Type | Description |
| --- | --- | --- |
| labelProperties | <code>[BirtLabelProperties](#BirtLabelProperties)</code> | Argument 1 |

<a name="setProperties"></a>

## setProperties(textProperties)
Properties setter for BirtText object

**Kind**: global function  
**For**: BirtText  

| Param | Type | Description |
| --- | --- | --- |
| textProperties | <code>[BirtTextProperties](#BirtTextProperties)</code> | Argument 1 |

<a name="setProperties"></a>

## setProperties(chartProperties)
Properties setter for BirtChart object

**Kind**: global function  
**For**: BirtChart  

| Param | Type | Description |
| --- | --- | --- |
| chartProperties | <code>[BirtChartProperties](#BirtChartProperties)</code> | Argument 1 |

<a name="setProperties"></a>

## setProperties(tableProperties)
Properties setter for BirtTable object

**Kind**: global function  
**For**: BirtTable  

| Param | Type | Description |
| --- | --- | --- |
| tableProperties | <code>[BirtTableProperties](#BirtTableProperties)</code> | Argument 1 |

<a name="setProperties"></a>

## setProperties(gridProperties)
Properties setter for BirtGrid object

**Kind**: global function  
**For**: BirtGrid  

| Param | Type | Description |
| --- | --- | --- |
| gridProperties | <code>[BirtGridProperties](#BirtGridProperties)</code> | Argument 1 |

<a name="initNewReport"></a>

## initNewReport()
Creates a new empty report design

**Kind**: global function  
**For**: Birt  
<a name="saveReport"></a>

## saveReport(qualifiedReportName, overwrite)
Saves a report design in XML format to the defined iHub for report generation

**Kind**: global function  
**For**: Birt  

| Param |
| --- |
| qualifiedReportName | 
| overwrite | 

<a name="listDataModels"></a>

## listDataModels(qulifiedPath) ⇒ <code>Object</code>
Retireves a list of available data objects at the given location

**Kind**: global function  
**Returns**: <code>Object</code> - availableDataModels  
**For**: BirtData  

| Param |
| --- |
| qulifiedPath | 

