Download Link: https://assignmentchef.com/product/solved-list-maintainer
<br>
Write a program that allows the user to add, delete and organize the items in a list. The program should not allow duplicate values in the list. Your program will provide the following options: Append: adds an items, input by the user, at the end of the list.

Delete: removes an item indicated by the user from the list.

Move up: moves an item indicated by the user, to the previous position in the list.

Move Down: moves an item indicated by the user to the next position in the list.

Move Top: moves an item indicated by the user to the the first spot in the list.

Move Bottom: moves an item indicated by the user to the last position in the list.

Swap: swaps two items indicated by the user in the list.

List all: display the items in the list; one item per line.

Quit: allows the user to end the program.

Your program shall show appropriate error messages when trying to move, swap, or delete items not found in the list. You program shall also properly handle invalid actions, like trying to move up the first item in the list or trying to move down the last item in the list. In order to get you started, download the file list_maintainer_base.py which you can find at the bottom of this page. Here is a sample run.

Let’s assume we already added the following items (in this order): cake, cookies, ice cream. Adding “donuts” List Maintainer 3000 Menu:

[A]dd item to the list,

[R]emove item from list,

[U] move an item up,

[D] move an item down,

[T] move item to the top,

[B] move item to the bottom.

[L]ist all items,

[Q]uit program,

[S]wap two items

Enter an option:

A [Add Item] Enter item: donuts …Item added.

Listing all items List Maintainer 3000 Menu:

[A]dd item to the list,

[R]emove item from list,

[U] move an item up,

[D] move an item down,

[T] move item to the top,

[B] move item to the bottom.

[L]ist all items,

[Q]uit program,

[S]wap two items

Enter an option:

L [List All] 01 cake 02 cookies 03 ice cream 04 donuts Moving ice cream up List Maintainer 3000 Menu:

[A]dd item to the list,

[R]emove item from list, [U] move an item up, [D] move an item down, [T] move item to the top, [B] move item to the bottom. [L]ist all items, [Q]uit program, [S]wap two items Enter an option: U [Move Up] Which item to move? ice cream …Item moved List Maintainer 3000 Menu: [A]dd item to the list, [R]emove item from list, [U] move an item up, [D] move an item down, [T] move item to the top, [B] move item to the bottom. [L]ist all items, [Q]uit program, [S]wap two items. Enter an option: L [List All] 01 cake 02 ice cream 03 cookies 04 donuts Move ‘cake’ to the bot***** *****st Maintainer 3000 Menu: [A]dd item to the list, [R]emove item from list, [U] move an item up, [D] move an item down, [T] move item to the top, [B] move item to the bottom. [L]ist all items, [Q]uit program, [S]wap two items. Enter an option: B [Move Bottom] Which item to move? cake …Item moved List Maintainer 3000 Menu: [A]dd item to the list, [R]emove item from list, [U] move an item up, [D] move an item down, [T] move item to the top, [B] move item to the bottom. [L]ist all items, [Q]uit program. Enter an option: L [List all] 01 ice cream 02 cookies 03 donuts 04 cake Swap “cookies” and “cake” List Maintainer 3000 Menu: [A]dd item to the list, [R]emove item from list, [U] move an item up, [D] move an item down, [T] move item to the top, [B] move item to the bottom. [L]ist all items, [Q]uit program, [S]wap two items. Enter an option: S [Swap Items] First item: cookies Second item: cake …Items swapped List Maintainer 3000 Menu: [A]dd item to the list, [R]emove item from list, [U] move an item up, [D] move an item down, [T] move item to the top, [B] move item to the bottom. [L]ist all items, [Q]uit program. Enter an option: L [List all] 01 ice cream 02 cake 03 donuts 04 cookies Use our Coding Style Guide and Documentation guidelines.