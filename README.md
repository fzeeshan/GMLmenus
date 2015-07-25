#GMLmenus
GMLmenus is a menu system that aims to allow for easy implementation, as well as markup to help make the system as versatile as possible.  

![Image from the example](https://slimgur.com/images/2015/07/25/1c4b72db25b973635c52dd8d813d519a.png)

There is 1 command:  
>draw_menu(str,background,foreground,x,y,width,height)

Str: This is the string that contains the code to be parsed, currently there are 2 codes:  
**|n** = New item  
**|s** = Separator  

Background: This is the color of the background  
  
Foreground: This is the color of the foreground  

x: The x start position of the menu (this will be the top left)  

y: The y start position of the menu (this will be the top left)  
  
Width: This will be the width of the menu  
  
Height: This will be the height of 1 cell of the menu

To do:  
1) |s has issues when placed next to any other code (e.g:|n), so I gotta fix it   
2) Add the following codes:  
**|c** = Color  
**||** = Insert a single