
## Projects

### Shift Select

* Minimalistic browser puzzle game. The current project I'm working on. Based on exploring the mechanic of selecting multiple items at once, like you would when holding shift and the left mouse button on your computer. The mechanic sounds like the most boring thing imaginable when written out, but some interesting things start happening when you begin messing around with the [XOR gate](https://en.wikipedia.org/wiki/XOR_gate) type weirdness of multiple overlapping selections.
* Built with vanilla JavaScript.
* You can try the very much unfinished version of the game [here](https://enkomat.github.io/shiftselect/)!
* Progress: ██▁▁▁▁▁▁ 25%

### Isomorphic

![Title screen.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/IsomorphicLogo1.png "Title screen.")
![Solving the first level.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/IsomorphicLoop1.gif "Solving the first level.")
![Solving the fifth level.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/IsomorphicLoop2.gif "Solving the fifth level.")

* iOS puzzle game based on the concept of [graph isomorphism](https://en.wikipedia.org/wiki/Graph_isomorphism). Two graphs are isomorphic when they might not visually look similar, but the connections between the nodes are the exact same. This means you could move each of the nodes and make these dissimilar looking graphs the exact same. And that's the premise of the game. Mostly procedurally generated.
* Interestingly, coming up with a good algorithm for checking whether two graphs are isomorphic or not is still quite an active area of research in computer science. The algorithm for checking the correct graph was much easier to create for this game, as the graphs are usually both isomprhic to begin with. In the case they are not, the graphs still contain such a small amount of nodes that it isn't going to take over a frame for even the oldest iPhone to go through a piece of code that would never work for a thousand nodes.
* Built with Unity and C#.
* Development in 2018 and 2019.
* Progress: ██████████ 100%
* Longer gameplay video [here](https://vimeo.com/531702062).

### Kanuuna

![Title screen.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/KanuunaLogo1.gif "Title screen.")
![Playing.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/KanuunaLoop1.gif "Playing.")

* iOS casual puzzler. You have a given amount of blocks with different colors and the map changes dynamically as you begin to plow through them. If the ball is not the right color, it will bounce off. The basic design could be used for something way less casual, but I ended up with this super bright and easily digestable thing. I guess I wanted to try to design something less minimalist and give myself a hall pass to juice everything up to eleven.
* Built with Unity and C#.
* Development in 2019.
* Progress: ██████▁▁ 75%

### Zenga

![Title screen.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/ZengaLoop2.gif "Title screen.")
![Solving the first level.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/ZengaLoop1.gif "Solving the first level.")
![Solving the fourth level.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/ZengaLoop4.gif "Solving the fourth level.")

* iOS puzzle game based on the concept of [Eulerian paths](https://en.wikipedia.org/wiki/Eulerian_path). Basically you need to jot down shapes and not draw too much over whatever you've already drawn. The aesthetic is reminiscent of [Zenga](https://en.wikipedia.org/wiki/Zenga) type Japanese ink painting, where the name is derived from.
* Wrote a custom algorithm for the path recognition of the game. The algorithm is based on overlaying invisible nodes over the drawing, essantially creating a graph that represents the drawing in a more abstract form. It is then measured that the player does not draw over a certain edge of the graph multiple times, while not forcing the player to draw perfectly over the original drawing. Basically, each drawing is a representation of a small node graph with at least one Eulerian path built into it.
* The next step would be to add a mechanic which would allow the player to add their own parts to the original painting, with a strictly limited amount of ink. This would allow for a much wider variety in the types of puzzles available, as you could introduce paintings that are incomplete.
* Built with Unity and C#.
* Development in 2018.
* Progress: █████▁▁▁▁▁ 50%
* Longer gameplay video [here](https://vimeo.com/531702505).

### Pops

![Title screen.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/PopsLoop1.gif "Title screen.")
![Playing.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/PopsLoop2.gif "Playing.")
![More playing.](https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/PopsLoop3.gif "More playing.")

* iOS casual puzzler. Your goal is to rotate the 3D shapes on top of each other and then tap to pop them when you match three or more. A spin on the classic Match 3 trope. The mechanics still feel pretty messy and there isn't as much depth to it as I'd like.
* Built with Unity and C#.
* Development in 2018.
* Progress: ██▁▁▁▁▁▁ 25%
* Longer gameplay video [here](https://vimeo.com/531703365).

### Spaghetti Master

<img src="https://raw.githubusercontent.com/enkomat/ot-harjoitustyo/master/dokumentaatio/main_menu_screenshot.png" alt="Main menu" width="300"/> <img src="https://raw.githubusercontent.com/enkomat/ot-harjoitustyo/master/dokumentaatio/level_1_screenshot.png" alt="First level" width="300"/> <img src="https://raw.githubusercontent.com/enkomat/enkomat.github.io/master/gifs/Screenshot%202021-06-22%20at%2012.39.27.png" alt="First level" width="300"/>

* Python programming game for Windows/Linux/MacOS. You control a character in the game and use it to build structures. The only way to control the character is by interfacing with the game through writing Python scripts. You write the code to solve a level with your chosen code editor and the game automatically updates the code to the game every time you save it, so it's less painful to iterate on your solution.
* This was a project for an university course, where each student was tasked to create a program with Python. Built with [Pygame](https://www.pygame.org/). I used [two](https://www.kenney.nl/assets/micro-roguelike) [different](https://www.kenney.nl/assets/game-icons) open source graphics asset packs from [Kenney](https://www.kenney.nl) for the project.
* Development in 2021.
* The project's [GitHub repository](https://github.com/enkomat/ot-harjoitustyo) contains more information and full source code.
* Progress: ██▁▁▁▁▁▁ 25%
