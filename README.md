# Rubiks
A CLI for Rubiks cubes, with which you can:

## Create cubes

```
Cube cube
```

(This creates a Cube object named cube.)

## Modify cubes
```
turn cube RF'U
```

(This turns the Cube cube by RF'U.)

```
Turns t
assign RB2R' t
turn cube t
```

(This creates a Turns object called t,
assigns the turns RB2R' to t
and turns the cube by the content of t)


## Solve cubes

```
Turns turns
solve cube turns
echo turns
```

(This creates a Turns object called turns, 
determines the minimal number of turns to solve the Cube cube and stores those Turns in turns. 
Then it outputs the turns object.)


## View cube in command line
```
echo cube
```

(Outputs the cube over the standard output.)


## View cube in 3D
```
show cube
```

(Opens a window in which one can view the cube in 3D, using OpenGL)

![rubiks_show_example](https://user-images.githubusercontent.com/6805564/53095868-1a6aab00-351e-11e9-9e60-2c360215676e.png)


## Time and manage your solves
```
timer
```

(Opens the timer subprogram)


## Commands
Type help COMMAND for detailed help!

exit:            Exits the application

solve:           Solves a Cube with least turns

Cube:            Creates new Cube object

Turns:           Creates a new Turns object

echo:            Outputs Cube/Turns object

assign:          Assigns Cube/Turns to another Cube/Turns object

clear:           Deletes all Cubes/Turns and clears the screen

turn:            Turns a Cube object

input:           Allows to input a Cube manually

quicksolve:      Solves a Cube quickly, but with many turns

help:            Shows help

show:            Shows a Cube in 3D

timer:           Starts timer subprogram
