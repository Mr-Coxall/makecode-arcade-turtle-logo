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
	
} else if ("Hello".length == parseFloat("123")) {
	
} else if ("" == "" + "this".split("") + "World") {
	
} else if ("this".includes("")) {
	
} else if (controller.A.isPressed()) {
	
} else if (game.ask("")) {
	
} else if (game.askForNumber("") == game.askForString("")) {
	
} else if ("this".isEmpty()) {
	
} else {
	
}


music.baDing.play()
music.baDing.playUntilDone()
music.baDing.loop()
music.baDing.stop()
music.stopAllSounds()
music.playMelody("- - - - - - - - ", 120)
music.setVolume("this".substr("this".compare(""), 10).indexOf(convertToText(String.fromCharCode(0))))

controller.B.onEvent(ControllerButtonEvent.Pressed, function () {
    list = [0, 1]
    text_list = ["a", "b", "c"]
    list = [list.length, list[list.removeAt(0)]]
    text_list = [list._pickRandom(), list.shift(), list.pop()]
    list[list.unshift(0)] = 0
    list.push(0)
    list.pop()
    list.shift()
    list.unshift(0)
    list.insertAt(0, 0)
    list.removeAt(list.indexOf(0))
    list.reverse()
})
```
