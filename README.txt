Demonstration of a possible bug in DevExpress Blazor's DataGrid component.

To reproduce, start the application, open http://localhost:5000/ in the
browser and press the buttons Select, Hide and Unhide in turn.

The Select button selects a subset of the rows in the grid.
The Hide button removes some rows from the grid and also removes
corresponding rows from the selection.
The Unhide button adds all rows again and selects the same rows as the
select button. But after this button is pressed, all rows are selected, not
just the rows added to SelectedItems.

Note: The value of the devexpress-blazor key in NuGet.config has been
masked. A valid key must be inserted.
