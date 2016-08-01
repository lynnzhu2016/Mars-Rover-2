# Mars-Rover-2
1. Grid origin starts from top, left, and the edge is preset to (x:25, y:25). The edge is actually also the position of (x:0, y:0). 
This design wraps the edge to make the grid has no end in each x and y coordinates. You can change the grid size in the code at line 17
2. The obstacles are preset at position [10, 6], [6, 3], [4, 10]. You can change the obstacleList postions in the code at line 21. 
3. You can choose start position from the page. 
4. To create a command list, you need to click add button every time when you choose turn value or set move steps. 
You can see the command list in the command list textarea. Negative number means move backward
3. Example command list: 
    ['left', 4, 'right', 10, 28] for obstacle test. This command list will put the Rover at postion (x: 4, y: 9) and facing South. 
    ['left', -6, 'right', 28] will for wrapping edge test. This command list put the rover at position (x: 19, y: 3) and facing South. 
