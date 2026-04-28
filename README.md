# Blazor DataGrid Cell Edit Template

This example shows how to render custom component for particular column.

The cell edit template is used to add a custom component for a particular column. You can use the **EditTemplate** of the GridColumn component to add the custom component. You can access the parameters passed to the templates using implicit parameter named **context**.

## Features

* Fast rendering with virtualization and row/column virtualization
* Sorting, filtering, grouping, and searching capabilities
* Inline, batch, and dialog editing modes
* Template columns, column resizing, reordering, and freezing
* Excel and PDF export (requires additional Syncfusion export packages)

## Prerequisites

* Visual Studio 2022 or later
* Visual Studio Code

## How to run the project

1. Clone or download this repository to a location in your system.
2. Open the solution file using the Visual Studio or Visual Studio code.
3. Restore the NuGet packages by rebuilding the solution or run `dotnet restore`.
4. Build the project to ensure there are no compilation errors.
5. Run the project.

Optional CLI Commands:

```powershell
dotnet restore
dotnet build
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/edit-types#render-custom-cell-editors

**Online example**: https://blazor.syncfusion.com/demos/datagrid/inline-editing?theme=bootstrap5