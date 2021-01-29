# piano_titles_bot

This bot can play piano titles with unlimited speed

Firstly, you need to run:

`import pyautogui`

`pyautogui.displayMousePosition()`

And them find a X, Y and first colour of each "paino road" using you cursour 

`Position: X:  581 Y:  400 RGB: ( 77,  80, 115)`
(just an example)

Then put your X and Y in 23, 26, 29, 32 lines

`if pyautogui.pixel(X, Y)[0] == 0:`
(and also in method "click")

Then, put a colour (almost its black) in 23, 26, 29, 32 lines

`if pyautogui.pixel(X, Y)[0] == (value of color):`
[0] - red colour; 
[1] - green colour; 
[2] - blue colour; 

Any questions?? Contact me

t.me/snappy
