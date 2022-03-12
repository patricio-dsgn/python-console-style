# UXI module for python console

This module is create for add styles to print elements

___

## Texts

create styles for strings with function **f()**

Suport 2 parameters string at any order, **style** and **color**

Style:
>empty, "normal", "bold", "light", "italic", "underline", "inverse", "hide", "strikeout"

Colors (font color):
>empty, "black", "red", "green", "yellow", "blue", "purple", "cyan", "white".

Colors (background):
>empty, "BLACK", "RED", "GREEN", "YELLOW", "BLUE", "PURPLE", "CYAN", "WHITE".

    import python_console_style as uxi

    print( uxi.f("hello im a red text", "red"))
    print( uxi.f("hello im a text with green background", "GREEN"))
    print( uxi.f("hello im a cyan text in bold", "bold", "cyan"))

___

## Jumbo

create block for strings with function **jumbo()**

Suport 1 parameters _integer_ for size of block

Size:
> empty(1), 2, 3

    import python_console_style as uxi

    print(uxi.jumbo("hello im a jumbo block normal", 1))
    print(uxi.jumbo("hello im a jumbo block medium", 2))
    print(uxi.jumbo("hello im a jumbo block large", 3))
