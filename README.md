# Customize Axes in Syncfusion Blazor Chart

## Overview

This sample demonstrates how to customize axes in a Syncfusion [Blazor Chart](https://www.syncfusion.com/blazor-components/blazor-charts). The application focuses on chart axis customization scenarios including axis crossing, multiple-axis configuration, and inverted-axis rendering. These features help developers improve chart readability and create analytical visualizations that require custom axis positioning and orientation. The sample is implemented as a Blazor WebAssembly hosted application and provides practical examples of configuring chart axes for different business and data visualization requirements.

## Key Features

- Demonstrates customization of chart axes using the Syncfusion chart component.
- Shows axis crossing configuration to position one axis relative to another axis.
- Implements multiple-axis scenarios for displaying different data scales within a single chart.
- Demonstrates inverted-axis rendering to change the default chart orientation.
- Includes chart-axis customization examples contained in `Client/Pages/Index.razor`.
- Supports common axis presentation requirements used in reporting and dashboard applications.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `CustomChartAxis.sln`

3. Restore all NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root.

```bash
cd how-to-customize-blazor-chart-axis
dotnet restore
dotnet run
```

If the repository uses a hosted Blazor structure, navigate to the startup project before execution.

```bash
cd Server
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Project Structure

- `Client/Pages/Index.razor` — contains the Syncfusion chart axis customization sample including multiple-axis, axis-crossing, and inverted-axis scenarios.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation for this feature: https://help.syncfusion.com/chart-sdk/blazor/charts/axis-customization

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.