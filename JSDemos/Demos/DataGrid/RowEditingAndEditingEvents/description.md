The **DataGrid** allows users to edit data in multiple modes. This demo shows the *"row"* edit mode. To start editing any row, click *"Edit"* in it. Only one row can be in the edit state at a time.

To enable row edit mode, set the [mode](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/editing/#mode) option to "row" and assign true to the editing object's [allowUpdating](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/editing/#allowUpdating), [allowAdding](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/editing/#allowAdding), and [allowDeleting](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/editing/#allowDeleting) options.

Edit operations raise events that you can handle with the following functions:    
- [onEditingStart](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onEditingStart)
- [onInitNewRow](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onInitNewRow)
- [onRowInserting](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onRowInserting) / [onRowInserted](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onRowInserted)
- [onRowUpdating](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onRowUpdating) / [onRowUpdated](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onRowUpdated)
- [onRowRemoving](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onRowRemoving) / [onRowRemoved](/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#onRowRemoved)
 
This demo shows an event log under the grid.