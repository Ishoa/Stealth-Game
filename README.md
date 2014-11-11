Stealth+Collection+Random Maze

basic game-play: navigate a maze, try not to be detected, collect determined amount of objects (intel),

random map generation:
* generate dense graph in grid shape
* do random size adjustment grid rows and columns
* use depth-first-search (with random weight to next-neighbour) to identify maze paths
* create boxes walls in blocked-off edges
* randomly assign collection items exit and entrance locations, and spawn points
* randomly assign type of floor (decides if player must use specific move action to cross) or not make sound

collection items are randomly placed 
random amount of collection items
enemies are randomly laced, and patrol randomly(wander)
some enemies patrol together(flock)
enemies can shoot at player

player agent can walk, run, or crawl
player agent has hp and stamina 
player can shoot at enemies
player can pick up usable Items:
	box: used to hide when out of sight of enemies to break agro
	

[E idle| sit around]
[E patrol| wander around looking for agents,avoid bullets]
[E HearSound|investigates a sound trigger]
[E TriggerAlarm|Notifies all Enemy agents of players last known location]
[E SeekPlayer|Moves towards player Location]
[E attack| attacks player agents]


[A idle|sit around]
[A move|move to target location using A*]
[A 
