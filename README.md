Steps:
1. create directory ~/Library/KeyBindings/
2. create file `DefaultKeyBinding.dict`
3. add contents:
```json
{
    "£"  = ("insertText:", "#");
}
```
4. Restart any application that needs it
5. Now Shift + 3 becomes #
