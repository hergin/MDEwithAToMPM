Here is the Maze environment: [Maze.zip](../files/Maze.zip "Maze.zip")    (Extract this file under your **atompm/users/[your_user_name]/Formalisms** folder.)

### Tasks

*   Create a maze generator
    *   Should be a valid maze
    *   Size will be 10x10
*   Solve the maze.
    *   Put the ball to the start of the maze
    *   Guide the ball to the end of the maze
    *   Avoid loops
        *   If stuck in a loop, you have to escape
    *   Must work with the mazes provided in the assignment
    *   Must work with any maze that can be generated

### Details

*   A valid maze:
    *   All outside walls are closed except one entry and one exit.
    *   It doesn't necessarily have to have a path from entry to exit.
*   Addition to the metamodel
    *   You can add some elements to the metamodel if you see a need.
    *   But only ADDITION is allowed, no modification or deletion of existing elements.
    *   This is your responsibility to keep the system still running after adding your custom elements.
    *   Seek advice from me anyway before doing this.

### Additional Files

*   Mazes
    *   [4x4_NoLoop.model](../models/4x4_NoLoop.model "4x4_NoLoop.model")
    *   [4x4_Loop.model](../models/4x4_Loop.model "4x4_Loop.model")
*   Mazes by Bradley
    *   [10x10_NoLoop.model](../models/10x10_NoLoop.model "10x10_NoLoop.model")
    *   [10x10_Loop.model](../models/10x10_Loop.model "10x10_Loop.model")

### Submission

*   You will zip and submit the Maze folder under your Formalisms.
*   This folder should have two transformations (along with other existing and necessary files)
    *   **T_Generate.model** for maze generation in an empty model.
    *   **T_Solve.model** to solve the existing open and valid maze with a ball.