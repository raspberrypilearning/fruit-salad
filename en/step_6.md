## Rotate button
At the moment each piece of fruit faces in the same direction which  will limit the design you create with your fruit salad. To improve your app, you will add a rotate button which you can click to rotate your ingredient before stamping it.

--- task ---
Create a **Rotate** sprite button by selecting Button3 one final time.

Drag the new button to below the grow and shrink buttons in the menu.

Rename it **Rotate** sprite.

--- /task ---

--- task ---
Click the **Rotate** sprite's Costumes tab.

Select the Paintbrush tool.

![image showing Paintbrush tool](images/fruit-paintbrush-tool.png){:width="200px"}

Adjust the Fill colour. 

Draw an arrow on the button. 

--- no-print ---
![Arrow on button in Costume editor](images/fruit-arrow.gif)

--- /no-print ---

**Tip:** If you make a mistake click on undo and then have another go.


--- /task ---

--- task ---
Now add code to the **Rotate** sprite so it broadcasts a message when it is clicked:

```blocks3
when this sprite clicked
broadcast [rotate v]
```
--- /task ---

--- task ---
Now select the **Ingredient** sprite and click on the Code tab. 

Add code to rotate the ingredient when a `rotate`{:class="block3events"} message is received. 

```blocks3
when I receive [rotate v]
turn [45] degrees :: motion
```

You don't have to rotate the ingredients 45 degrees each time the rotate button is clicked. You can choose any angle. 
--- /task ---

--- task ---
Try your project again. Choose an ingredient, rotate it, stamp it as many times and you like and keep adding ingredients to create a fruit salad. What patterns can you create with fruit?

--- /task ---

--- save ---
