## Add a rotate button
At the moment each piece of fruit faces in the same direction. This limits the designs you can create with your fruit salad. To improve this, you'll add a rotate button which you can click to rotate your ingredient before stamping it.

emma: This could be made into a challenge, or could use hints as it just repeats skills that have already been introduced. Instead of using the paintbrush you could just use the '*' with the Text tool?

--- task ---
Add a Button3 sprite to your project. 
--- /task ---

--- task ---
Click on the Costumes tab. You are going to add an arrow to show that this button will rotate the Ingredient.

Select the Paintbrush tool and adjust the Fill and Brush width settings - you can choose the colour and width of the brush. 

Draw an arrow on the button. 

**Tip:** If you make a mistake click on undo and then have another go.

![Arrow on button in Costume editor]()

--- /task ---

--- task ---
Drag the rotate button onto the menu, under the ingredient. 

![Rotate button on menu]()

--- /task ---

--- task ---
Click on Code tab so you can add code to the button.
--- /task ---

--- task ---
Do you think the button is too big? If so you can reduce it by changing the number below the stage or by using a code block. 

emma: Do we want to explain exactly how to do this or do we assume they know by this point in the pathway?
--- /task ---

--- task ---
Now add code to the button so it broadcasts a message when it is clicked:

```blocks3
when this sprite clicked
broadcast [rotate v]
```
--- /task ---

--- task ---
Now select the Ingredient sprite and click on the Code tab. 

Add code to rotate the ingredient when a `rotate` message is received. 

```blocks3
when I recieve [rotate v]
turn 45
```

You don't have to rotate the Ingredient 45 degrees (half a right angle) each time the rotate button is clicked, you could choose a different number. 
--- /task ---

--- task ---
Try your project now. Choose an ingredient, rotate it, stamp it as many times and you like and keep adding ingredients to create a fruit salad. 

--- /task ---

--- save ---

 







 




 





