# elevator-challenge
Repository of a coding challenge developed by me.

## The Problem
In a bulding with 23 floors and 3 elevators, denominated Saturn, Earth and Mars, design an elevator system that uses the according rules:
  - When pressing the button to get the elevator, the program must get the most near one (the fastest); 
  - If any elevator is already moving when pressing the button to get the elevator, the program must 
  get the elevator that's already going on the same way (up or down) as the same way indicated on the button pressed;
  - The objective of this system it's do always deliver the fasted elevator and make the user get to it's
  destiny as fast as possible;
  - The distance between the floors is equal: 2 meters each floor;
  - The velocity of the elevator when in movement is 10 kilometers per hour (10km/h);
  - The input of the program must be: 
  ```
  Current floor: number of current floor
  Final Floor: number of the floor you want to get to
  Button position: up or down
  ```
  - The output of the program must be: 
  ```
     Fastest elevator: name of elevator
     Time elapsed: time elapsed in milliseconds
  ```

  ## Simulations: 

  1. 
  Current floor: 6
  Final Floor: 0
  Button position: down
  None of the elevators are moving at the moment.
  Saturn is on the floor 0, Earth is on 10th floor and Mars is on the floor 0.  
  I press the button (down) do get the elevator.
  <br> Output code: 
  ```
  Fastest elevator: Saturn
  Time elapsed: 3000
  ```
  2. I´m at the 23th floor and I want to go to de 2nd floor. 2 Elevators are moving. I press the button (down)
  to get the elevator. 
  <br>Output code: 
