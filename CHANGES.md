### V1.6 October 1st, 2013
* Implement all options changes for HighCharts and FusionCharts. User can 
  customize all aspects of Highcharts and Fusioncharts and export them.
* Redeign all layouts, levegage multiple tabs to use screen more efficiently.
  Dynamic create and remove Report tabs and drill through tabs.
* Sepearte widget layout and widget creation so that all widgets can be 
  recreated anytime. This allows future implementation of dynamic changing 
  language setting.
* Implement Drill through for both CSV and OLAP.
* Clean data strcture design, implemented saving everything of WebPivotTable 
  (data and options) to a file and restore it anytime. 
* Implement sort Fields values.
* Add pivot fields setting and sorting at pivot bar.
* Enable/Disable file proxy and xmla proxy at UI.


### V1.5 September 1st, 2013
* Implement most fuctionalities of OLAP support, include cross-tab grid, expand 
  and collpase, charts, slice, non empty.
* Redeign the csv grid layout and csvService to fully concide with Microsoft 
  Excel, support compact form and tabular form, expand/collapse both columns 
  and rows, show/hide row/column totals/subtotals.   
* Show tooltip for all data cell and support drill through for csv.
* Redesign pivot toolbar, grid toolbar and chart toolbar.
* Pivot grid and charts share exactly the same data set and refresh 
  automaticlaly for any change together. 
* Fix 25 fields limit issue and add support of locale number style.


### V1.4 August 2nd, 2013

* Seperate all modules into different files to easy future development.
* Create dojo build profile to build a single layer loadable customize dojo.js 
  to improve the loading performance, also make it very easy for all kinds of 
  web application integarte this component.    
* The first implementation of OLAP support, now this component can be used as 
  a front end UI for all kinds of business intelligence projects.
* Create an unify XmlaService to support Microsoft Analysis Service (SSAS), 
  Mondrian OLAP server and icCube OLAP server.
* Unify the support of different chart libraries. Currently dojo chart library  
  is default chart library, it will be always avaiable. FusionCharts library 
  and Highcharts library will be avaiable when those chart libraries file has 
  been loaded.
* Fix issues related to touch screen device, now this component can be run at 
  all touch Screen laptops and tablets like ipad.


### V1.3 July 5th, 2013

* Replace FusionChart library with dojo chart library
* Use filepicker.io to load csv file from cloud drive
* replace xmla4js with own xmla service, no dependence on xmla4js
* Redeisgn pivot control pane to support tree structure (for OLAP)
* Redeign pivot grid layout engine to support values within columns and rows
  and can be moved up and down.
* Implement the function of expanding and collapsing columns tree
* Redesign the calculation engine to improve performance 
* Implement Fullscreen Mode using HTML5 FullScreen API 



### V1.2 June 8th, 2013

* Redeisgn layout to allow change control pane position
* Upgrade to dojo1.9 and remove dependence of Expandpane and floatingPane
* Put grid pane and chart pane inside one container to easily control layout
* Redeign Import Module and implement change CSV content before import
* Implement Zoom in and Zoom out Grid and charts
* Implement Export to excel functionality 
* Replace webkitHTmltopdf with phantomjs to output report to pdf
* Move xmla4js to client side (ready to replace xmla4js with own js lib)
* Use node.js request module at backend to do tranparent proxy



### V1.1 May 3rd, 2013

* The biggest improvement to make it production ready
* Redeign the calculation engine and grid layout to support filters
* Redesign UI to use standard menu and improve User experience
* Redeign fields pivot grid to support OLAP
* Move data input and report export as individual module 
* Add more customize options for integration 


### V1.0 April 3rd, 2013

* Redeign the grid to better control the style  
* Fix all issues after 1.0beta2 review
* Improve the calculation engine to support larger source dataset
* Redeisgn the chart to improve the performance
* Add more customize API to easy integration 


### V1.0b2 March 13th, 2013

* Change to based on dojo1.8.3 and use pure AMD 
* Fix all issues after 1.0beta review
* Totally Support IE8,9,10, Firefox, Chrome, Safari
* Change to use 
  [put-selector](https://github.com/kriszyp/put-selector) and
  [xstyle](https://github.com/kriszyp/xstyle)
* Separate Core modules into an independent pure javascript component and put on 
  [Github](https://github.com/) and 
  [Cloud 9 IDE](https://c9.io), create
  [node.js](http://nodejs.org/) server to test component.
* Clean code to satisfy CLoud9 IDE Code Quality Check.
* Reorginaize code to follow javascript code standard best practice.
* Use online javascript compressor [jscompress.com](http://jscompress.com/)


### V1.0b1 Aug 26th, 2012 

* Change pivot chart from dojo chart to 
  [FusionCharts](http://www.fusioncharts.com/). 
* Create a demo wordpress website 
  [webpivottable.com](http://webpivottable.com/) for public review.

### V0.3 June 13th, 2012 

* Implement PHP backend export HTML to pdf. 
* Implement PHP backend to load excel data. 
* Add pivot charts based on dojo chart library.


### V0.2 May 25th, 2012 

* Solve the long run script issue while hirechary of rows or columns becomes 
  complicate. 
* Change lazy-load cells to one-time loading. 
* Add grid options to change pivotGrid layout
* Add filter functions.


### V0.1 April 29th, 2012

* Implement basic functions of pivot controls & pivot grid, all based on 
  [dojo](http://dojotoolkit.org/) and 
  [dgrid](https://github.com/SitePen/dgrid) widget.



