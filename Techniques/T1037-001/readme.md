# T1037-001 - Boot or Logon Initialization Scripts: Logon Script

## Execution Methods

	This method only has one execution method.

## Parameters
	1 - Script Path - Required
		Path to the derired logon script. i.e. \Users\Public\script.bat

	2 - User - Optional
		User to be used during execution, defaults to current user.

	Requires Admin privileges

## Examples

Alters Bob's Logon Script to "\Users\Public\script.bat":

```json
{
    "Technique": "T1037-001",
    "Parameters": [
    "\\Users\\Public\\script.bat",
    "Bob"
    ]
		}
```

Alters the current user's Logon Script to "\Users\Dylan\Desktop\logon.bat":

```json
{
    "Technique": "T1059-001",
    "Parameters": [
        "\\Users\\Dylan\\Desktop\\logon.bat"
    ]
}
```

