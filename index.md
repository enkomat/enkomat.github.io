
# Portfolio

### Isomorphic
* iOS puzzle game based on the concept of [graph isomorphism](https://en.wikipedia.org/wiki/Graph_isomorphism). Two graphs are isomorphic when they might not visually look similar, but the connections between the nodes are the exact same. This means you could move each of the nodes and make these dissimilar looking graphs the exact same. And that's the premise of the game. Mostly procedurally generated. Pretty sure the game would be better with more hand designed levels, though, so might have to make more of those.
* Interestingly, coming up with a good algorithm for checking whether two graphs are isomorphic or not is still a quite active area of computer science. The algorithm for checking the correct graph was much easier to create for this game, as the graphs are usually both isomprhic to begin with and in the case they are not, they contain such a small amount of nodes that is isn't going to take over a frame for even the oldest iPhone to process.
* ██████████████▁▁▁▁▁▁ 70%
* Longer gameplay video [here](https://vimeo.com/531702062).

![Title screen.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/IsomorphicLogo1.png "Title screen.")
![Solving the first level.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/IsomorphicLoop1.gif "Solving the first level.")
![Solving the fifth level.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/IsomorphicLoop2.gif "Solving the fifth level.")

### Zenga
* iOS puzzle game based on the concept of [Eulerian paths](https://en.wikipedia.org/wiki/Eulerian_path). Basically you need to jot down shapes and not draw too much over whatever you've already drawn. The aesthetic is supposed to be reminiscent of [Zenga](https://en.wikipedia.org/wiki/Zenga) type Japanese ink painting, where the name is derived from.
* Wrote a custom algorithm for path recognition. The algorithm is based on overlaying invisible nodes over the drawing, essantially creating a graph that represents the drawing in a more abstract form. It is then measured that the player does not draw over a certain edge of the graph multiple times, while not forcing the player to draw perfectly over the original drawing.
* Progress: ███████▁▁▁▁▁▁▁▁▁▁▁▁▁ 35%
* Longer gameplay video [here](https://vimeo.com/531702505).

![Title screen.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/ZengaLoop2.gif "Title screen.")
![Solving the first level.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/ZengaLoop1.gif "Solving the first level.")
![Solving the fourth level.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/ZengaLoop4.gif "Solving the fourth level.")

### Kanuuna
* iOS casual puzzler. You have a given amount of blocks with different colors and the map changes dynamically as you begin to plow through them. If the ball is not the right color, it will bounce off. The basic design could be used for something way less casual, but I ended up with this super bright and easily digestable thing. I guess I wanted to try to design something less minimalist and give myself a hall pass to juice everything up to eleven. The name means cannon in Finnish!
* ██████████▁▁▁▁▁▁▁▁▁▁ 50%

![Title screen.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/KanuunaLogo1.gif "Title screen.")
![Playing.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/KanuunaLoop1.gif "Playing.")

### Pops
* iOS casual puzzler. Your goal is to rotate the 3D shapes on top of each other and then tap to pop them when you match three or more. A spin on the classic Match 3 trope. The mechanics still feel pretty messy and there isn't as much depth to it as I'd like.
* Progress: ███▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁ 15%
* Longer gameplay video [here](https://vimeo.com/531703365).

![Title screen.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/PopsLoop1.gif "Title screen.")
![Playing.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/PopsLoop2.gif "Playing.")
![More playing.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/PopsLoop3.gif "More playing.")

### Spaghetti Master
* Python programming game for Windows/Linux/MacOS. You control a character in the game and use it to build structures. The only way to control the character is by programming Python and interfacing with the game with the language.
* This was a project for an university course, where each student was tasked to create a program with Python. Built using [Pygame](https://www.pygame.org/).
* The project's [GitHub repository](https://github.com/enkomat/ot-harjoitustyo) contains more information and full source code.
* Progress: ███▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁ 15%
