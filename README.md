### documentation-toggle-keyboard-internal

1. Open CMD (Run As Administration)
2. ```disabled keyboard
   sc config i8042prt start= disabled
   ```
3. ```active keyboard
   sc config i8042prt start= auto
   ```
