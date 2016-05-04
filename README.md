##ArduinoSimpleButton
___

You can use it in simple manner:
```c++
#include <Button.h>
Button upButton = Button(32); //where 32 is pin, button connected to
upButton.processState(); 
```
* 0 - button is released
* 1 - button was in short press
* 2 - button is in long press
* 3 - button was pressed and now waits to become in short or long or released state (additional state to ajust timings).


