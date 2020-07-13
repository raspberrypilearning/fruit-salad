## Grow button
Not all pieces of fruit are the same size. Now you're going to add buttons to grow and shrink your ingredient before adding it. 

--- task ---
To add a button sprite go to Choose a Sprite.

![image showing Choose a Sprite](images/fruit-choose-sprite.png){:width="400px"}

Search for Button3 by typing 'Button3' in the search menu and select it.

![image showing Button3 sprite](images/fruit-button3-sprite.png){:width="400px"}

--- /task ---

You will now see button sitting in the Stage area. You need to move the button otherwise someone may eat it!

--- no-print ---
![gif showing Button3 in menu](images/fruit-button3-menu.gif).

--- /no-print ---

--- task ---

Drag the button in to position from the plate to the menu area on the left-hand side of the screen.

--- /task ---

--- task ---

Change the name of 'Button3' to **Grow** sprite.

--- /task ---

--- task ---

Click on the **Grow** sprite's Costumes tab. 

![image showing Grow sprite paint editor](images/fruit-grow-paint.png){:width="400px"}

Choose the Text tool and select any Fill colour you like. 

![image showing text and fill tools](images/fruit-text-fill-tool.png){:width="100px"}

Add a '+' symbol to your button by selecting the 'plus' key on your keyboard.

Use the 'handles' to make the '+' the right size for your button. 

![image showing plus enlarging](images/fruit-grow-plus.png){:width="400px"}

--- /task ---

--- task ---
Switch back to the Code tab. 
![image showing code tab](images/fruit-code-tab.gif){:width="300px"}

--- /task ---

--- task ---

Add code to the **Grow** sprite to broadcast a 'grow' message when it is clicked. 

```blocks3
when this sprite clicked
broadcast grow
```
--- /task ---

You now need to add some code to the **Ingredients sprite** so it can recieve the message to grow.

--- task ---

Select the **Ingredients sprite**.

--- /task ---

--- task ---

Add the following code to the **Ingredients sprite** for it to grow:

```blocks3
when I receive [grow v]
change size by (10)
```
--- /task ---

--- task ---
Run your program. Make sure that you can grow your pieces of fruit before stamping them. 
--- /task ---


