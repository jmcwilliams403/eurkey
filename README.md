The [EurKEY keyboard layout](https://eurkey.steffen.bruentjen.eu/start.html) 
source for the [Keyboard Layout Files Creator]( https://github.com/39aldo39/klfc)

Build with:

```
$ klfc us.json eurkey.json -o output
```  

The layout is split into multiple files:
- `us.json`, the main file, includes the None and Shift shift-states
- `eurkey.json`, includes the AltGr and Shift-AltGr shift-states
