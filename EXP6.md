# EXP-06: Implement the AI random movement.
### Aim:
Implement the AI random movement.
### Algorithm:
Step:01 Create a Character Blueprint.

Step:02 Create a Blackboard.

Step:03 Open the Behavior Tree editor.

Step:04 Create Behavior Tree nodes for the following,

 "Selector" node: Controls the execution of child nodes.

 "Service" node: Monitors and updates values in the Blackboard.

 "Sequence" node: Executes child nodes in sequential order.

 "Random" decorator: Randomly selects a child node to execute.

 "Move To" task: Moves the AI character to a specified location.

Step:05 Set up the Blackboard with vector key and bool keys and save it.

Step:06 Set up the AI character Blueprint with the help of AI controller component.

Step:07 Set the AI controller and behavior treeiIn the Possess node, select the AICharacter

Blueprint you created and drag off the AICharacter reference and search for “Use Blackboard”

Step:08 Set up the NavMesh and boundaries, we can adjust the size and position to cover the
desired play area.

### Output:
![image](https://github.com/user-attachments/assets/8a56d282-177f-47c9-9673-e88e4d3c9f2e)

### Blackboard Event graph:
![image](https://github.com/user-attachments/assets/eb664146-ef89-4cf6-a0a8-55c95b1059d0)

### Behaviour Tree:
![image](https://github.com/user-attachments/assets/5305b52b-7084-4b03-91d0-220e5c5c8684)

### Result:
Thus, the AI concept to the actor for a random movement is implemented.
