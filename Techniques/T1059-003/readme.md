# T1059-003 Command and Scripting Interpreter: Windows Command Shell

## Execution Methods

	This method only has one execution method.

## Parameters
	1 - command - Required
    	Command to be executed by cmd.exe. If your command has spaces, make sure to surround them with double quotes.
   
## Examples

Creates a directory on Bob's desktop:

```json
{
    "Technique": "T1059-003",
    "Parameters": [
    "mkdir c:\\Users\\Bob\\Desktop\\important"
    ]
}
```