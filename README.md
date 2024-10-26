# h-diminished
really bad c#-like programming language
please dont use this for any actual purpose
the name doesnt mean anything its just a wrong extrapolation of the musical note c sharp

# background
i got really bored in school and decided to make a compiler
i figured that making a language that compiles to a custom il would be the best option for working with typescript, so thats what i did
i also built this entire thing in a single [typescriptlang.org playground](typescriptlang.org/playground) file and mostly from my school device lmao

# documentation
its basically just c# but it doesnt have the following basic programming ideas
- inheritance (i will probably do this one next)
- a good compiler error logging system
- anything fancy at all
- any helper functions (math library, array manipulation, type reflection)
- you have to use a lot more symbols so the tokens -> tree stage is easier for me

example of the last one:
```
Console:WriteLine$(Buh~("yeah", "no??").buhs#1);
```

it does some of the following really weird specific things out of laziness
- numbers are processed in javascript
- all locals and pushed values are stored on the stack instead, while fields are stored in memory
- there arent any float types but you can just put floats into normal int places and as long as they arent fields they work lmao

have fun
