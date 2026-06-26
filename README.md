# ASP.NET Core Gantt Chart - Project View Demo

This repository contains a sample ASP.NET Core MVC application that demonstrates how to implement a project scheduling interface using the [ASP.NET Core Gantt Chart](https://www.syncfusion.com/aspnet-core-ui-controls/gantt-chart) component.

## Features

- Hierarchical project view using self-referential task data
- Task dependencies, predecessors, and progress tracking
- Resource allocation with custom resource label templates
- Add, edit, and delete tasks using built-in toolbar and dialog editing
- Timeline view with configurable week/day tiers and taskbar editing


## Prerequisites

- .NET Core SDK 8.0 or later
- Visual Studio 2022 or later
- Internet access for Syncfusion CDN assets

## How to run

1. Clone or copy the repository to a local folder.
2. Open `ASPCoreGanttDemo.sln` in Visual Studio.
3. Restore NuGet packages.
4. Build the solution to ensure all dependencies are resolved

## Notes

- The Gantt data is generated in code via `GanttData.SelfData()` and `GanttData.GetResources()`.
- The sample includes a custom resource label template and uses Syncfusion CDN assets.

## References

- [Explore ASP.NET Core Gantt Chart](https://www.syncfusion.com/aspnet-core-ui-controls/gantt-chart)
- [Documentation](https://ej2.syncfusion.com/aspnetcore/documentation/gantt/resources)
- [ASP.NET Core Gantt Chart Getting Started Guide](https://ej2.syncfusion.com/aspnetcore/documentation/gantt/getting-started)
- [ASP.NET Core Gantt Chart Live Demos](https://ej2.syncfusion.com/aspnetcore/gantt/resources#/fluent2)
