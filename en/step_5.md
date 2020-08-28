## Add a Shrink button

In this step, you will make another button, but this button will shrink the ingredients. If you need a reminder of any of the following steps, go back to the instructions for the **Grow** button.

--- task ---

Click on **Choose a Sprite** and select another **Button3** sprite.

You will now see the new **Button3** sprite on the Stage. Drag the button from the bowl to the menu area on the left-hand side of the Stage and place it below the **Grow**  button.

--- /task ---

--- task ---

Go to the **Costumes** tab. 

Select a **Fill** colour of your choice. 

Select the **Text** tool and type a `-` (minus) symbol onto the button. Resize the symbol.

--- /task ---

--- task ---

Change the name of the **Button3** sprite to `Shrink`.

--- /task ---

Now, you need to add some code to the **Shrink** sprite.

--- task ---
Switch back to the **Shrink** sprite's **Code** tab and add the following code to `broadcast`{:class="block3events"} a `shrink` message `when the sprite is clicked`{:class="block3events"}:

```blocks3
when this sprite clicked
broadcast [shrink v]
```
--- /task ---

--- task ---

Now, add some code to the **Ingredients** sprite so that it shrinks when it receives the message to shrink from the **Shrink** sprite:

```blocks3
when I receive [shrink v]
change size by (-5)
```
--- /task ---

--- task ---
Take some time to enjoy your project and design a fruit salad. 
--- /task ---

--- save ---







 




 





