# Blazor DataGrid Cell Edit Template

This example shows how to render custom component for particular column in [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

This sample application demonstrates the power of `EditTemplate` feature for the Blazor DataGrid. It provides a real-world example of an orders management grid where the shipping city is edited using a custom dropdown component instead of the default text input.

The project includes:

- A responsive **DataGrid** with sample order data
- **Inline editing** with custom cell edit templates
- A **dropdown selector** for the ShipCity column
- Complete order details model with typed properties

## Features

- **Custom Cell Editors**: Use the `EditTemplate` component to add custom controls for specific columns
- **Inline Editing**: Edit records directly in the grid with Add, Edit, Delete, and Cancel actions
- **Data Binding**: Strongly-typed model binding with `ModelType` parameter
- **Paging**: Built-in pagination support (5 records per page)
- **Context Access**: Access row data within templates using the implicit `context` parameter

## Prerequisites

* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)
* [.NET SDK 9.0](https://dotnet.microsoft.com/download/dotnet/9.0) or later

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/EJ2-DataGrid-Blazor-Editing-CellEditTemplate.git
cd EJ2-DataGrid-Blazor-Editing-CellEditTemplate
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/edit-types#render-custom-cell-editors

**Online example**: https://blazor.syncfusion.com/demos/datagrid/inline-editing?theme=bootstrap5