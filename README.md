# DynamicObject-data-binding-with-EditTemplate-in-Blazor-DataGrid
This sample demonstrates how to bind a Syncfusion Blazor DataGrid to a `DynamicObject` and use the `EditTemplate` feature for editing fields like dropdowns dynamically.

## Overview

In this example:

- The DataGrid is bound to a list of dynamic objects (`OrdersDetails` inherits from `DynamicObject`).
- A custom `EditTemplate` is used to render a dropdown (`SfComboBox`) in the `Account` column.
- Changes made via the dropdown are captured and updated using the `RowUpdating` event.
- Dynamic member access and mutation is implemented via `TryGetMember` and `TrySetMember`.

## Getting Started

### Prerequisites

- [.NET 6.0 SDK or later](https://dotnet.microsoft.com/en-us/download)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or any IDE that supports Blazor
- Syncfusion Blazor NuGet packages

### Project Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/SyncfusionExamples/DynamicObject-data-binding-with-EditTemplate-in-Blazor-DataGrid.git
   ```
2. Navigate to the project folder:

    ```bash
    cd DynamicObject-data-binding-with-EditTemplate-in-Blazor-DataGrid
    ```
3. Restore the NuGet packages:

    ```bash
    dotnet restore
    ```
4. Build and run the application:

    ```bash
    dotnet run
    ```
5. Open the browser at https://localhost:port (port varies).