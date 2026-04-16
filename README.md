# ASP.NET Core Gantt Chart - Project View Demo

A sample ASP.NET Core 3.1 MVC repository demonstrating a Syncfusion EJ2 Gantt chart for project view scheduling, resources, and task editing.

This demo uses the Syncfusion Essential JS 2 Gantt control to render a hierarchical project schedule with editable tasks and resource assignments.

## Features

- Project view hierarchy with self-referential parent IDs
- Task dependencies, predecessors, and progress tracking
- Resource allocation and custom resource label templates
- Add, edit, and delete tasks using toolbar and dialog support
- Timeline view with week/day tiers and taskbar editing

## Prerequisites

- .NET Core SDK 3.1
- Visual Studio 2019 or Visual Studio 2022
- Internet access for Syncfusion CDN assets

## How to run

1. Clone or copy the repository to a local folder.
2. Open `ASPCoreGanttDemo.sln` in Visual Studio.
3. Restore NuGet packages.
4. Build the solution.
5. Run the project.

The home page displays the Syncfusion Gantt chart and sample task data.

## Notes

- The Gantt data is generated in code via `GanttData.SelfData()` and `GanttData.GetResources()`.
- The sample includes a custom resource label template and uses Syncfusion CDN assets.

## References

- Syncfusion Essential JS 2 Gantt: https://www.syncfusion.com/aspnet-core-ui-controls/gantt
