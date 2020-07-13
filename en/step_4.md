## Grow button
Not all pieces of fruit are the same size. Now you're going to add a button to grow your fruit ingredients before adding them. 

--- task ---
To add a button sprite go to Choose a Sprite.

![image showing Choose a Sprite](images/fruit-choose-sprite.png){:width="400px"}

Search for Button3 by beginning to type 'Button3' in the search menu. Select Button3.

![image showing Button3 sprite](images/fruit-button3-sprite.png){:width="400px"}

--- /task ---

You will now see the button sitting in the Stage area. You need to move the button off the plate otherwise someone may eat it!

--- no-print ---
![gif showing Button3 in menu](images/fruit-button3-menu.gif).

--- /no-print ---

--- task ---

Drag the button from the plate in to position in the menu area on the left-hand side of the screen.

--- /task ---

--- task ---

Change the name of Button3 to **Grow** sprite.

--- /task ---

--- task ---

Click on the **Grow** sprite's Costumes tab. 

![image showing Grow sprite paint editor](images/fruit-grow-paint.png){:width="400px"}

Choose the Text tool and select any Fill colour you like. 

![image showing text and fill tools](images/fruit-text-fill-tool.png){:width="100px"}

Add a '+' symbol to your button by selecting the 'plus' key on your keyboard.

Use the 'handles' around the button to change '+' size. Make sure it fits the button and can be seen clearly on your button. 

![image showing plus enlarging](images/fruit-grow-plus.png){:width="400px"}

--- /task ---

You now need to add some code to the **Grow** sprite.

--- task ---
Switch back to the Code tab. 
![image showing code tab](images/fruit-code-tab.gif){:width="300px"}

Add the following code to the **Grow** sprite to broadcast a 'grow' message when it is clicked. 

```blocks3
when this sprite clicked
broadcast grow
```
--- /task ---

And now need to add some code to the **Ingredients sprite** so it can recieve the message from **Grow** sprite to grow.

--- task ---

Select the **Ingredients sprite**.

--- /task ---

--- task ---

Add the following code to the **Ingredients sprite** to enable it to grow:

```blocks3
when I receive [grow v]
change size by (10)
```
--- /task ---

--- task ---
Run your program. Make sure that you can grow your pieces of fruit before stamping them. 
--- /task ---

--- save ---

