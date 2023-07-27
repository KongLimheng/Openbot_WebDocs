<!--TITLE: Sheets Delete Empty Rows Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Sheets\Row group. -->

# Sheets Delete Empty Rows Command


## What does this command do?
"This command deletes all empty Rows from a given range in an Sheets Sheet.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Sheets Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MySheetsInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Sheet Name|Specify the Sheet within the Spreadsheet to use.|"Sheet1" \|\| vSheet||
|Range|Enter the location of the cell or range to delete.|"A1" \|\| "A1:B10" \|\| "A1:" \|\| vRange \|\| vStart + ":" + vEnd \|\| vStart + ":"||
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||
