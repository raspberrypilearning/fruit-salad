## Add a Rotate button
At the moment, each piece of fruit faces in the same direction, which will limit the design that users can create with your fruit salad app. To improve your app, you will add a **Rotate** button that users can click to rotate the ingredient before they stamp it.

--- task ---
Create a **Rotate** button sprite. To do this, select a **Button3** sprite once more.

Drag the new button to below the **Grow** and **Shrink** buttons in the menu.

Rename it `Rotate`.

--- /task ---

--- task ---
Click on the **Rotate** sprite's **Costumes** tab.

Select the **Brush** tool.

![image showing Paintbrush tool](images/fruit-paintbrush-tool.png){:width="150px"}

Adjust the **Fill** colour. 

Draw an arrow on the button. 

--- no-print ---
![Arrow on button in Costume editor](images/fruit-arrow.gif)

--- /no-print ---

**Tip:** If you make a mistake, click on **Undo** and then have another go.


--- /task ---

--- task ---
Now, add code to the **Rotate** sprite so that it `broadcasts`{:class="block3events"} a `rotate` message `when the sprite is clicked`{:class="block3events"}:

```blocks3
when this sprite clicked
broadcast [rotate v]
```
--- /task ---

--- task ---
Now, select the **Ingredients** sprite and click on the **Code** tab. 

Add code to rotate the **Ingredients** sprite when it receives a message to rotate `turn right 45 degrees`{:class="block3motion"}. Check that you have selected the correct `turn`{:class="block3motion"} right motion block.:

```blocks3
when I receive [rotate v]
turn [45] degrees :: motion
```

You do not have to rotate the ingredients 45 degrees each time the **Rotate** button is clicked. You can choose any angle of rotation. 
--- /task ---

--- task ---
Try your project again. Choose an ingredient, rotate it, stamp it as many times as you like, and keep adding ingredients to create a fruit salad. What patterns can you create with fruit?

--- /task ---

--- save ---
