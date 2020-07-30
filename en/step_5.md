## Shrink button

You will now make another button but this time the button will shrink the fruit ingredients. Go back to grow sprite if you need a reminder on any of the following steps.

--- task ---

Go to Choose a Sprite and select another **Button3**.

You will now see the new second button sitting in the Stage area. Drag the button from the bowl to the menu area on the left-hand side of the screen and place it below the **Grow**  button.

--- /task ---

--- task ---

Go to the Costumes tab. 

Select a Fill colour of your choice. 

Select the text tool and type an <kbd>-</kbd> (minus) symbol on to the button. Resize the symbol.

--- /task ---

--- task ---

Change the name of **Button3** sprite to **Shrink**.

--- /task ---

You now need to add some code to the **Shrink** sprite.

--- task ---
Switch back to the **Shrink** sprite's Code tab and add the following code to broadcast a `shrink`{:class="block3events"} message when the sprite is clicked:

```blocks3
when this sprite clicked
broadcast [shrink v]
```
--- /task ---

--- task ---

And now add some code to the **Ingredients** sprite so it shrinks when it receives the message from **Shrink** sprite to shrink:

```blocks3
when I receive [shrink v]
change size by (-5)
```
--- /task ---

--- task ---
Take some time to enjoy your project and design a fruit salad. 
--- /task ---

--- save ---







 




 





