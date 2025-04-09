# Death by lightswitches
In my introductory course in algorithms and datastructures, there was this neat logic puzzle, called death by lightswitches. There are a number of variations of the puzzle, varying greatly in difficulty, here I want to show some of them to you, and try guide you through them.

## The puzzle
A prison warden recieves $32$ prisoners. They are to live in solitary confinement. But the prison warden finds that this would be a bit boring, so he wants to play a game with the prisoners: Each day he will bring one of the prisoners into a room. In the room there are a number of lightswitches, that can be set to either *on* or *off*. The lightswitches do not control anything, they are only there for communicating their current state. If at any time a prisoner knows that *all* $32$ prisoners have been in the room, then that prisoner can tell the warden, and every prisoner will be released. The prisoners are allowed to come up with a strategy before they are jailed. But afterwards, they can only communicate through the state of the lightswitches.

### 32 Lightswitches
As a fairly easy warmup, try to come up with a strategy that the prisoners can use when there are $32$ lighswitches. You may assume that initially they are all turned off.
If you get stuck, I have left a few hints:
<details> 
  <summary>Hint 1 </summary>
   You may notice that there are as many light switches as prisoners
</details>
<details> 
  <summary>Hint 2 </summary>
   How many light switches does a prisoner need to communicate to everyone else that they have been in the room?
</details>
<details> 
  <summary>Solution</summary>
  A simple solution, is that every prisoner turns on exactly one light switch, the first time they enter the room.
  If a prisoner sees that all $32$ light switches are on, there must have been $32$ different prisoners that have been in the room. 
</details>



Text that is not a quote

> Text that is a quote