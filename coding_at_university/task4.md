# Task #4
### @flyoutOnly true
### @hideIteration false
### @explicitHints false

``` ghost
    for (let index = 0; index < 1; index++) {
        agent.move(FORWARD, 1)
        agent.destroy(FORWARD)
        agent.collectAll()
    }
```
```template
   //     
```

## Gather the Materials

Navigate the Agent through the maze and gather all the necessary parts! To take an item, use the command ``||agent.destroy||``. After your robot collect needed items, talk with ``||Professor Assistant||``.

### ~ Hint 

Feel free to make your own robot path to gather all necessary parts. If you talk again with Professor Artur, you can reset your task and spawn items on ground again. 


```typescript-valid
Path for "glowstone_dust" item
```
``` blocks
agent.move(FORWARD, 4)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.destroy(FORWARD)
agent.collectAll()
```
```
```
```typescript-valid
Path for "iron_ingot" item
```
``` blocks
agent.move(FORWARD, 5)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 5)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 4)
agent.destroy(FORWARD)
agent.collectAll()
```
```
```
```typescript-valid
Path for "stick" item
```
``` blocks
agent.move(FORWARD, 3)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 3)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 5)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.destroy(FORWARD)
agent.collectAll()
```
```package
github:kwakong/ai-cosmic_coding_at_university
```
