### @explicitHints true

```template
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
```

# Turtle Logo

## Step 1
**Turtle Logo**

Code your solution below.

```ghost
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.moveDirection(TurtleDirection.Forward, 25)
myTurtle.turnDirectionByDegrees(TurtleTurnDirection.Right, 90)
myTurtle.say("Hello, World!")
myTurtle.pen(TurtlePenMode.Up)
myTurtle.setPenColor(0)
turtle.clearScreen()
myTurtle.home()
myTurtle.setPositionCartesian(0, 0)
myTurtle.stamp(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `)
myTurtle.setSpeed(50)

controller.A.onEvent(ControllerButtonEvent.Pressed, function () {
})

game.splash("")
game.showLongText("", DialogLayout.Bottom)

effects.confetti.startScreenEffect()

forever(function () {
})
pause(1000)

while (false) { 
}
for (let value of list) { 
}
break;
continue;

for (let index = 0; index < Math.min(Math.sqrt(4), randint(3, 10)) + 5 % Math.abs(2); index++) {
	
}
if (!(true && false)) {
	
} else if (0 == 0) {
	
} else if ("" == "") {
	
} else {
	
}


list = [0, 1]
text_list = ["a", "b", "c"]
```
