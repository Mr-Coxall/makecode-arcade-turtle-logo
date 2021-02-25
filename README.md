# Makecode Arcade - Turtle Logo

## Turtle Logo
To start with, go to the "Turtle" section to the left an pull out the top block.
Place it inside the "on start" block 
```blocks
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
