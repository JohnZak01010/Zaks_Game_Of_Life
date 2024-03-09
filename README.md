# Zaks_Game_Of_Life
Unity DOTS Community Challenge #1 by Turbo Makes Games

The Challenge:

Make the best performing Conway's Game of Life Using Unity's Data-Oriented Technology Stack and their Entity Component System!

Feel free to start with the standard rules of Conway's Game of Life and add some more dimensions and features that you find compelling. The main goal of this challenge is to use Unity DOTS in interesting ways to optimize for performance on a large scale with some simple rules.

The only restriction of this challenge is that you must use Unity DOTS/ECS as the core part of your application - i.e. don't just write a shader to run the simulation on the GPU, that's not really the point of this challenge.

This is an UNRANKED jam and is more about encouraging you to explore interesting data-oriented concepts with Unity DOTS and ECS.

For submission, you will need to provide:

Final Windows x64 Executable
Git repository with all source code publicly available
Development writeup - a few paragraphs to a few pages on your strategies for optimizing performance. Talk about what worked, what didn't work, things you wanted to try but couldn't. Also include some performance metrics about how many cells you can simulate at 60 and 30 FPS. Please also note the hardware you were testing on (Desktop/Laptop, CPU, GPU, Memory)
I'd highly recommend testing performance in a build of the application and using a tool like Graphy to gather FPS data.

Standard Rules of Conway's Game of Life:

Cells are arranged in a square grid
Cells can be considered live or dead
Cells live or die each generation based on neighboring cells (up, down, left, right, 4 diagonal corners)
A generation is a single update of all cells in the simulation
A live cell with 0 or 1 live neighbors dies next generation due to underpopulation
A live cell with 2 or 3 live neighbors lives on to the next generation
A live cell with 4 or more live neighbors dies next generation due to overpopulation
A dead cell with exactly 3 live neighbors becomes a live cell next generation due to reproduction


Original announcement below....

Hello All!

Starting March 8th, we'll be kicking off the first Unity DOTS Community Challenge! This challenge is more akin to a hackathon then a game jam where a challenge is given when the jam begins and participants will be tasked with completing the challenge using Unity's Data-Oriented Technology Stack and their Entity Component System.

This challenge is intended to be a lower commitment than a full on game jam, where ideally participants can complete the challenge in their spare time after work or on one of the two weekends the challenge spans.

While we won't be talking about what the challenge is until the kickoff day, challenge is intended to be simple enough where anyone even with limited DOTS/ECS experience will be able to complete it. Though the challenge will still have enough depth for advanced users to try implementing some more complex techniques to squeeze every ounce of performance out of it!

The spirit of this challenge is to encourage everyone to solve the same problem in unique and interesting ways. All submissions should be open sourced and include a brief writeup on your strategy for maximizing performance, so we can all learn from each other! Notable strategies will be discussed on an upcoming episode of The Hot Path Show.

If you are new to Unity ECS, we'd recommend checking out some of these learning resources:

Samples & Tutorials from Unity
Code Monkey Intro Tutorial
Turbo Makes Games Zombies Tutorial - a few things are outdated, but it is a good example of a fully featured project with ECS 1.0
We'll be announcing the details of the challenge on the March 8th episode of The Hot Path Show that will air at 1:00PM PST on the Turbo Makes Games YouTube Channel

Hope you're as excited for this challenge as we are 😀

- Johnny (Turbo Makes Games), Dani (Unity), Tobias (Knackelibang Productions)
