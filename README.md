# TopHat Scripting API
## Functions
### onEnable
```lua
function onEnable()
    -- Perform initialization tasks here
end
```
### onDisable
```lua
function onDisable()
    -- Perform cleanup tasks here
end
```
### onUpdate
```lua
function onUpdate()
    -- Perform tasks that will run until the script is disabled
end
```
## Methods
### Printing to chat
```lua
chat:print("message")
```
### Setting player speed
```lua
player:setSpeed(doubleValue)
```
### Setting the player's X position
```lua
player:setX(intValue)
```
### Setting the player's Y position
```lua
player:setY(intValue)
```
### Setting the player's Z position
```lua
player:setZ(intValue)
```
### Setting the player's rotation pitch
```lua
player:setPitch(floatValue)
```
### Setting the player's rotation yaw
```lua
player:setYaw(floatValue)
```
### Setting the player's motion X
```lua
player:setMotionX(doubleValue)
```
### Setting the player's motion Y
```lua
player:setMotionY(doubleValue)
```
### Setting the player's motion Z
```lua
player:setMotionZ(doubleValue)
```
### Setting the player's onGround value
```lua
player:setGround(booleanValue)
```
### Making the player sprint
```lua
player:setSprint(booleanValue)
```
### Making the player jump
```lua
player:jump()
```
### Making the player swing it's arm
```lua
player:swing()
```
