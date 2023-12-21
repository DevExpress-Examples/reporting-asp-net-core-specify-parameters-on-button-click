<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/387731575/23.1.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1020315)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Reporting for ASP.NET Core - Specify Parameter Value on Button Click

This example demonstrates how to submit parameter values on button click and use the [Document Viewer's Client-Side API](https://docs.devexpress.com/XtraReports/401793?v=21.1) to pass the values to the report.

![](Images/asp-net-core-specify-parameters-on-button-click.png)

## How to Run the Example

1. Download the project and update NuGet packages.
2. Build and run the project.
3. Navigate to a page that contains the document viewer.
4. Enter a parameter value in the editor and click the *Submit* button.

 ## Files to Review

* [Viewer.cshtml](CS/ReportingApp/Views/Home/Viewer.cshtml)
* [CustomReportStorageWebExtension.cs](CS/ReportingApp/Services/CustomReportStorageWebExtension.cs#L45)

## Documentation

* [Specify Parameter Values in an ASP.NET Core Reporting Application](https://docs.devexpress.com/XtraReports/403229).
