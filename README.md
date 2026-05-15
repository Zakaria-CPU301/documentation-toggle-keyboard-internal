### documentation-toggle-keyboard-internal

1. Open CMD (Run As Administration)
2. ```bash
   sc config i8042prt start= disabled
   ```
3. ```php
   sc config i8042prt start= auto
   ```
