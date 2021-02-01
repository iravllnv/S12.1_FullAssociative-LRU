# CSARCH2 Full Associative Cache Mapping (LRU)

### S12.1 Members
- CARANDANG, Pauline Gayle
- CORTEL, Lorraine Renee
- PASCUAL, Jeremy Nathan
- VILLANUEVA, Ira

### About the Project
This project simulates a Full Associative Cache Mapping function that uses Least Recently Used (LRU) replacement algorithm technique. The project is able to support the following:
- Simpleton (where the user inputs all the necessary data including the values for the main memory sequence)
- Random (where the values for the main memory sequence are generated by the computer)
- Sequential, that runs for _x_ loops and provided the ending main memory value _n_ for the iteration (where _x_ is the number of iterations for the mapping and memory is to be iterated from 0 to _n_)

## How to Use the Application
### A. Main Menu
![mainmenu](https://i.imgur.com/AZu1ih4.png)

Upon loading the self-executable jar file, the user will encounter the main menu prompt where they can choose which type of cache mapping they can perform, with the choices being limited to Random, Simpleton, and Sequential. Upon being clicked, the user will be redirected to the corresponding page for the chosen cache mapping.

### B. Random Menu
![random](https://i.imgur.com/UPLfY3O.png)

When Random input mapping is clicked, the user will be redirected to the input page where they are required to fill in the necessary fields before being allowed to simulate cache mapping.

The user is expected to fill in the following fields:
1. **Block Size**: Size of the block in words.
2. **Cache Memory Size**: Size of the cache memory (user can choose between block or word).
3. **Main Memory Size**: Size of the main memory (user can choose between block or word).
4. **Cache Access Time**: Time used for accessing the cache (represented in nanoseconds).
5. **Memory Access Time**: Time used for accessing the memory (represented in nanoseconds).

In the **Main Memory Sequence Values** field, the numbers are randomly generated by the computer upon the page being loaded. The user can opt to change the random number sequence by clicking _Generate Values_ button found on the upper right corner of the input fields.

Additionally, there are three (3) buttons that the user is free to click.
- **Menu**: Brings back the user to the previous page (main menu) where they can choose a different type of cache mapping.
- **Reset**: Removes all the values inputted in the field.
- **Simulate**: Performs the algorithm for the chosen simulation and the results will be displayed on the right panel of the page.

### C. Simpleton Menu
![simpleton](https://i.imgur.com/phVEEvu.png)

When Simpleton input mapping is clicked, the user will be redirected to the input page where they are required to fill in the necessary fields before being allowed to simulate cache mapping.

The user is expected to fill in the following fields:
1. **Block Size**: Size of the block in words.
2. **Cache Memory Size**: Size of the cache memory (user can choose between block or word).
3. **Main Memory Size**: Size of the main memory (user can choose between block or word).
4. **Cache Access Time**: Time used for accessing the cache (represented in nanoseconds).
5. **Memory Access Time**: Time used for accessing the memory (represented in nanoseconds).
6. **Main Memory Sequence Values**: Values to be used in the simulation of the function.

In this page, the Main Memory Sequence Values are manually inputted by the user as a string of characters. 

Similar to the previous page, there are still three (3) buttons that the user can interact with.

### D. Sequential Menu
![sequential](https://i.imgur.com/vsoRoCX.png)

When Sequential input mapping is clicked, the user will be redirected to the input page where they are required to fill in the necessary fields before being allowed to simulate cache mapping.

The user is expected to fill in the following fields:
1. **Block Size**: Size of the block in words.
2. **Cache Memory Size**: Size of the cache memory (user can choose between block or word).
3. **Main Memory Size**: Size of the main memory (user can choose between block or word).
4. **Cache Access Time**: Time used for accessing the cache (represented in nanoseconds).
5. **Memory Access Time**: Time used for accessing the memory (represented in nanoseconds).
6. **Value Range? (0-n)**: End value of the sequence.
7. **No. of Iterations**: Value for how many times the sequence range should be accessed by the program.
