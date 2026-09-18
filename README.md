# Row and Cell Customization in Blazor Data Grid

## Overview

This sample demonstrates how to customize the appearance and behavior of rows and cells in the Syncfusion Blazor DataGrid. The implementation showcases row-level customization techniques together with cell presentation options, enabling developers to control how data is displayed within the grid. These customization techniques can be used to highlight important information, improve usability, and adapt the grid layout to specific business requirements.

## Key Features

- Demonstrates row customization within the Syncfusion Blazor DataGrid.
- Demonstrates cell customization for presenting data with customized styling and formatting.
- Provides examples of improving data presentation through row-level and cell-level customization techniques.
- Uses the Syncfusion Blazor DataGrid component as the primary data visualization control.
- Serves as a reference implementation for customizing DataGrid rendering while preserving standard grid functionality.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file `RowCellCustomization.sln`.
3. Restore all NuGet packages.
4. Set the `Server` project as the startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the Server project directory.

```bash
cd Server
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `Client/Pages/Index.razor` — contains the Syncfusion Blazor DataGrid implementation, row customization logic, cell customization examples, text wrapping configuration, clip mode settings, and grid line configuration.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid Cell documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/cell#customize-cell-styles and Row Customization documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/row#customize-rows

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.