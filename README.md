# 5eSchema for Editors
Just modified the actual 5e.tools Schema to one that can be used in your Editor.

## How to use it with VS Code
- Download the folder with the schema
- Put it into a another folder in your VS Code Workspace
- Go to Settings and search for Schema
- Edit the settings.json for the JSON: Schemas setting
- Put this into your `"json.schemas"` array with your correct paths:
``` 
{
    "fileMatch": [
        "*.json"
    ],
    "url": "./TheGiddyLimit TheGiddyLimit.github.io master test-schema/schema.json"
}
```
Every json file you make in this workplace folder now will use this schema.  
If somethings missing or wrong let me know on Discord.
