# POC Post-it FrameVR
## Context
This experiment is meant to streamline a brain storming process where people place post-its with ideas around.
## about
This prototype is an iframe placed inside the frameVR platform with some url parameters.
It uses frameVR rest api to spawn a sort of postit with the right content at the defined location (in url parameters)

## API
Write the url as is : 
`https://arthurmougin.github.io/postit-framevr/?position=-0.5;1.22;30.5&rotation=0;30;0&apikey=${apikey}`
Where `-0.5;1.22;30.5` is the intended formating for the position (x: -0.5, y: 1.22, z:30.5)
and same thing for the rotation with `0;30;0`.

## Found limitations of the solution
the real time spawning is not stable, and the users may not have the rights to move the spawned sticker, which defeats the point. 
More work can be spent if needs resume.
