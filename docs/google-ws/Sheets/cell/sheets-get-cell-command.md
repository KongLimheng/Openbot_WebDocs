<!--TITLE: Sheets Get Cell Command -->
<!-- SUBTITLE: a command in the Google Workspace Commands\Sheets\Cell group. -->

# Sheets Get Cell Command


## What does this command do?
This command gets text from a specific cell in an Sheets Sheet.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Sheets Instance Name|Enter the unique instance that was specified in the **Create Session** command.|MySheetsInstance|Failure to enter the correct instance or failure to first call the **Create Session** command will cause an error.|
|Sheet Name|Specify the Sheet within the Spreadsheet to use.|"Sheet1" \|\| vSheet||
|Cell Location|Enter the location of the cell to extract.|"A1" \|\| vCellLocation||
|Output Cell Value Variable|Create a new variable or select a variable from the list.|vUserVariable|New variables/arguments may be instantiated by utilizing the Ctrl+K/Ctrl+J shortcuts.|
|Private (Optional)|Optional field to mark the command as private (data sensitive) in order to avoid its logging.|||
|Remote (Optional)|Optional field to mark the command as remote in order to execute it on a remote machine.|||
|Error Handling|Optional field for how to handle errors encountered.|||
|Comment (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command.|I am using this command to...||


## Developer/Additional Reference
Automation Class Name: SheetsGetCellCommand
Parent Namespace: OpenBots.Commands.GoogleWorkspace.Sheets.Cell
This page was generated on 07/19/23 09:51 AM


## Help
[Open/Report an issue on GitHub](https://github.com/OpenBotsAI/OpenBots.Studio/issues/new)
[Ask a question on the OpenBots Forum](https://openbots.ai/forums/)
