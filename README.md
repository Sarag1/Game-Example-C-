# Game-Example-C-
small game created in c++ that uses arrays, conditionals and loops made during my first semester of computer engineering

### C++ libraries used

-  stdlib.h
- time.h
- windows.h
- cstdlib
- iostream
- sstream

##Process

|  **Procces** | **Description **  |
| :------------: | :------------: |
|  rem_item(id,amount) | Remove a item from the inventory |
| add_item(id,amount)  | Add items to the inventory  |
|  print_mercader() | Print the merchant shop array |
| inv_space() | check if the inventory is full |
| print_item(pos)  | Print item from the player inventory |
| print_inv("name") | Print the player inventory |
| search_items(item_id, item_min)  | searches the player inventory to see if they have an item or a specific amount of it |
| Craft(crafted, craft_amount, need1, need1_amount, need2, need2_amount)  | Allows crafting of objects  |
| Craftings() | Shows crafting options and checks whether or not an item can be crafted | 
| Drop_item() | throw selected items from inventory | 
| inventory_ops() | The function defined to open the inventory submenu | 
| contador("action", tim)  | a countdown used to give a touch to certain processes |
| loot_tables(n1, n2, n3, n4) | Function used to pseudo randomize the obtained objects | 
| explore()  | action of leaving an expedition which uses the aforementioned loot table as rewards |
| mine_table(n1, n2) | Loot table for mine option |
| mine()  | action of going to mine, the rewards are based on the previous table |
| wood_table(n1, n2)  | Loot table for cut down option|
| talar() | action of go to cut down in the forest, the rewards are based on the previous table |
| menu() | This is the main part of the game and where all the rest of the function goes and some important data is stored. |
| main() | the program main is only used to get the player name and initialize the random seed |
