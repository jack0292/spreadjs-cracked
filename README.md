# spreadjs-cracked
spreadjs cracked license-free version

Please contact telegram to crack the license-free version of spreadjs

![image](https://github.com/ruofeng001/spreadjs-cracked/assets/161565538/b038b47f-7f51-4f05-b36a-de5ea823dd6e)

SpreadJS V17 has many new exciting features and two new optional addon components:

NEW! GanttSheet Add-On
We are proud to introduce the new optional GanttSheet Add-On! This new sheet type is essentially a full Gantt implementation inside of SpreadJS, allowing you to create Work Breakdown Structures and Production Schedules, just to name a couple. It is a fast, data-bound DataTable view with Gantt Chart behavior and a spreadsheet user interface. Using GanttSheet provides several benefits:

Visual Planning: Provides a clear visual representation of project tasks, timelines, and dependencies, making it easier to plan and manage projects effectively.
Task Dependencies: Allows you to define and visualize task dependencies, helping you understand how different tasks are linked and the impact of delays on the overall project timeline.
Progress Tracking: Tracks the progress of each task and the overall project by marking completed tasks and comparing them with the planned timeline.
Deadline Management: Enables you to set and manage project milestones and deadlines, ensuring that the project stays on track and is completed within the specified time frame.
You can also manage tasks, sort, change calendar settings, and even import and export to SSJSON, SJS, and Excel.
![image](https://github.com/ruofeng001/spreadjs-cracked/assets/161565538/4ba76bd4-99fe-4e56-a018-869dc70fe6f7)

 

NEW JavaScript GanttSheet Add-On

NEW! ReportSheet Add-On

SpreadJS V17 marks the introduction of the new optional ReportSheet Add-On! This new sheet type for SpreadJS supports creating and managing reports. These reports can be important for creating marketing strategies, travel reports, sales track reports, employee reports, and more. Usually, this can take a lot of time and effort to put together, but ReportSheet makes it a simple and flexible process. This new add-on supports data entry, pagination, data filtering, sorting, and conditional formatting. Using ReportSheet can provide a lot of benefits to your application:

Integrated Template and Data Management: Allows seamless integration of report settings and data with the combination of ReportSheet and TemplateSheet. The TemplateSheet holds various report-related settings, which ReportSheet utilizes, alongside data from DataManager, to generate corresponding reports efficiently.
Enhanced Flexibility: Provides highly flexible syntax and API to bind source data. It follows easy data population rules in fields and also provides data entry APIs.
Ease of Customization: Ensures a standardized format and appearance for all generated reports, maintaining consistency across various data sets.
Comprehensive Data Handling Features: Manage and present data in a user-friendly manner. ReportSheet is not just about report generation; it's a comprehensive tool that supports data entry, pagination, data filtering, sorting, and conditional formatting.
JavaScript XLSX ReportSheet Add-on Component

Chart Enhancements

Waterfall Charts

We have added a new chart type to SpreadJS: the Waterfall chart. This shows a running total as values that are added or subtracted. These values are arranged as columns with positive and negative values and are color-coded to distinguish between the two. The initial and final columns are typically aligned against the horizontal axis, whereas the intermediate values are typically floating columns.

Waterfall charts added to JS Spreadsheet API

Smooth Lines Format for Line Charts

Line charts in SpreadJS now support formatting with smooth lines.

SpreadJS now supports Smooth Lines for Line Charts

Inserting Charts with Multi-Selections 

Similar to Excel, SpreadJS now supports inserting charts using multi-selections. In addition to selecting a continuous area of data, you can now also press the Ctrl key to select multiple, non-contiguous areas to create a chart. You can also specify multiple ranges in code by placing a comma between each range:

sheet.charts.add("chart1", GC.Spread.Sheets.Charts.ChartType.columnClustered, 0, 100, 400, 300, "Sheet1!$A$1:$C$4,Sheet1!$E$3:$G$3,Sheet2!$A$1:$A$3");
These ranges can be specified in multiple ways, and SpreadJS will create the chart accordingly:

Insert charts with multi-selections in JS Spreadsheet

Shape-Based Chart Rendering 

Charts have been reworked to be shape-based rather than DOM-based. This is more of an internal change, and existing charts will not be affected, but there is now more support for Z-Order management, grouping, and connecting with other shapes.

Workbook Enhancements
Additional Paste Special Options

SpreadJS now supports even more paste special options, including:

Comments - Paste only comments
Validation - Paste only data validation rules
All using Source theme - Paste all cell contents in the same worksheet theme
All except borders - Paste all cell contents and formatting except for the borders
Column Widths - Paste the width of one copied column or range of columns
Formulas and Number Formats - Paste only formulas and all number formatting options
Values and Number Formats - Paste only values and all number formatting options
Sheet Tabs Style Support

Sheet tabs now support styles that the user can set. The style includes the text style, background color, and icon.

Extending Custom Table Column Style

Custom table column styles are now propagated properly when tables auto-expand.

JS Custom Table Style Auto Extending to new row

TopRowChanged/LeftColumnChanged Event Enhancement

The TopRowChanged and LeftColumnChanged events now support pixel scrolling. Before this change, the entire row or column would have to be scrolled before the event would fire, but now it will fire and provide the scrolling status for any change in the scrolling when pixel scrolling is enabled.

Distributed Horizontal Alignment

SpreadJS now supports Distributed Horizontal Alignment for text. This is simple to the Center alignment, except it will also wrap text automatically.

Preserve Last Excel Sort State

When importing Excel files, SpreadJS now preserves the sort condition so that it is not lost.

Calculation Enhancements
IMAGE Function Update

The IMAGE function has been updated to match Excel’s implementation. This change includes changing the order of parameters as well as adding the alt_text and sizing parameters.

JavaScript Spreadsheet IMAGE function

Window Functions Enhancements

The TableSheet Window function has also been updated to include the FrameGroups frame type and the Exclude parameter. The FrameGroups frame type is defined by groups as the starting and ending boundaries of the frame. The Exclude parameter is an optional parameter that lets you exclude rows or groups from a frame.

PivotTable Enhancements
Split Font Options

We have split the font options into different properties to better support PivotTable and Table font options in Excel. Normally, the font property on a cell can be used to set all of the font options, but we have also provided API to set the individual font options like fontFamily, fontSize, fontWeight, and fontStyle:

// Font
activeSheet.getCell(2, 0).font('italic normal 12px Mangal');
activeSheet.getCell(4, 0).font('normal bold 15px Arial Black');
activeSheet.getCell(6, 0).font('normal normal 18px Georgia');
 
// FontFamily
activeSheet.getCell(2, 1).fontFamily('Mangal');
activeSheet.getCell(4, 1).fontFamily('Arial Black');
activeSheet.getCell(6, 1).fontFamily('Georgia');
 
// FontSize
activeSheet.getCell(2, 2).fontSize('12px');
activeSheet.getCell(4, 2).fontSize('20px');
activeSheet.getCell(6, 2).fontSize('28px');
 
// FontWeight
activeSheet.getCell(2, 3).fontWeight('bold');
activeSheet.getCell(4, 3).fontWeight('normal');
 
// Italic
activeSheet.getCell(2, 4).fontStyle('italic');
activeSheet.getCell(4, 4).fontStyle('normal');

PivotArea Offset Support 

SpreadJS now provides an offset property to style specific PivotAreas in a PivotTable. You can use this offset to specify the row, column, rowCount, and colCount of the area that you want to style:

let style = new GC.Spread.Sheets.Style();
    style.backColor = "rgb(247, 167, 17)";
    let labelPivotAreaWithOffset = {
        labelOnly: true,
        references: [{
            fieldName: "Salesperson",
            items: ["Alan"]
        }],
        offset: {
            row: 1,
            col: 0,
            rowCount: 3,
            colCount: 1
        }
    };
    pivotTable.setStyle(labelPivotAreaWithOffset, style);
    let cornerPivotAreaWithOffset = {
        type: GC.Spread.Pivot.PivotAreaType.corner,
        offset: {
            row: 0,
            col: 1,
            rowCount: 1,
            colCount: 1
        }
    };
    pivotTable.setStyle(cornerPivotAreaWithOffset, style);
    let topRightPivotAreaWithOffset = {
        type: GC.Spread.Pivot.PivotAreaType.topRight,
        offset: {
            row: 0,
            col: 0,
            rowCount: 1,
            colCount: 4
        }
    };
    pivotTable.setStyle(topRightPivotAreaWithOffset, style);

JavaScript PivotArea Offset Styling

TableSheet Enhancements
Reference Calculated Fields

The DataManager supports adding fields from a data source, but it also now supports virtual columns with a formula data type. These formula columns can then be used in the View of a TableSheet to show things like a Running Sum or a Stock Value Ratio:

JavaScript TableSheet Calculated Fields

// Add product table.
var productTable = dataManager.addTable("productTable", {
    remote: {
        read: {
            url: baseApiUrl + "/Product"
        }
    },
    schema: {
        columns: {
            TotalUnits: {
               dataType: "formula",
               value: "[@UnitsInStock] + [@UnitsOnOrder]"
            },
            StockValue: {
                dataType: "formula",
                value: "[@UnitPrice] * ([@TotalUnits])"
            }
        }
    }
});
 
// Bind a view to the table sheet
var myView = productTable.addView("myView", [
    { value: "Id", caption: "ID", width: 50 },
    { value: "ProductName", caption: "Name", width: 170 },
    { value: "UnitPrice", caption: "Unit Price", style: { formatter: "$#,##0.00" }, width: 120 },
    { value: "UnitsInStock", caption: "Units In Stock", width: 120 },
    { value: "TotalUnits", caption: "Total Units", width: 120 },
    { value: "StockValue", caption: "Stock Value", style: { formatter: "$#,##0.00" }, width: 120 },
    { value: "=SUM([#1:@[UnitPrice]]*([#1:@[UnitsInStock]]+[#1:@[UnitsOnOrder]])", caption: "Running SUM", style: { formatter: "$#,##0.00" }, width: 150 },
    { value: "=[@StockValue]/SUM([UnitPrice] * ([UnitsInStock] + [UnitsOnOrder]))", caption: "Stock Value Ratio", style: { formatter: "0.00%" }, width: 160 }
]);

Trigger Formulas for Columns

Trigger Formulas in a TableSheet are formulas that calculate according to specific conditions or triggers. This means you can recalculate data based on specific conditions, clean data when a new value is entered, or provide a default value for a column. Here are a few examples of trigger formulas:

var table = dataManager.addTable("Table", {
    schema: {
        columns: {
            createdDate: {
                dataType: "Date",
                trigger: {
                  when: "onNew",            <<------- apply the formula on created
                  formula: "=NOW()",        <<------- trigger formula to set current time
                  // fields: "*"            <<------- when triggered on new, there is no need to specify the affected fields
                },
            },
            updatedDate: {
                dataType: "Date",
                trigger: {
                  when: "onNewAndUpdate",   <<------- apply the formula on created and updated
                  formula: "=NOW()",        <<------- trigger formula to set current time
                  fields: "*"               <<------- all fields changed will have the formula applied to them
                },
            },
            label: {
                trigger: {
                    when: "onNewAndUpdate",      <<------- apply the formula on updated
                    formula: "=UPPER([@label])"  <<------- use the upper formula on the input text of the label field
                    fields: "label",             <<------- when the current column value is updated the formula will be applied
                  },
            },
            amount: {
                dataType: "number",
                trigger: {
                    when: "onNewAndUpdate",             <<------- apply the formula on updated
                    formula: "=[@price] * [@quantity]"  <<------- automatically evaluate the amount
                    fields: "price,quantity",           <<------- the changes of the price and quantity columns will cause the formula to calculate
                  },
            },
            price: { dataType: 'number' },
            quantity: { dataType: 'number' }
        },
    }
});

Sparkline Enhancement
Lollipop Variance Sparkline

The new Lollipop Variance Sparkline lets you show absolute and relative variances in a dataset. It is similar to a bar chart but reduces the display space by using lines instead of rectangles. As a result, they are more useful when dealing with large amounts of data.

Lollipop Variance Sparklines in a JS Spreadsheet
