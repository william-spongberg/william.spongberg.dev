# william.spongberg.dev

#### Check out other versions of this website!

- [**HTML**](html/index.html) IN PROGRESS
- [**HTML/CSS**](html-css/index.html) TODO
- [**JavaScript**](js/index.html) TODO
- [**threeJS**](threejs/index.html) TODO

## About Me

Hello! I'm **Will**, a passionate software developer with experience in creating desktop, web, and mobile applications. I'm currently studying computer science at the **University of Melbourne**, with my main interests being **software engineering**, **artificial intelligence**, and **web development**. I'm always looking for new opportunities to learn and grow as a developer, so feel free to reach out if you'd like to collaborate on a project or just have a chat!

### Skills

**Python** | **C** | **C#** | **Java** | **SQL** | **JavaScript** | **Flutter** | **Dart** | **Prolog** | **Haskell**

## Projects

These are projects I've completed in my spare time for fun or to learn new tech. I've also included some of the projects I've completed as part of my university studies. Github links are provided for each project, and I'm happy to discuss any of them in more detail if you're interested.

- [**Google Chrome Built-In AI Challenge**](https://github.com/Chillerbag/Applyify)

  I recently competed in the **Google AI Challenge**, where myself and [**Ethan Hawkins**](https://www.linkedin.com/in/ethan-hawkins-24486a244/) created a Google Chrome extension using Google's new **Gemini Nano**, a locally-run and private AI model. Our extension, called **Applify**, streamlines the process of applying for jobs online by automatically finding the job's required skills, updating the user's resume and creating a draft cover letter. Find the challenge information [**here**](https://googlechromeai.devpost.com/).

- [**Bouncy Balls**](https://github.com/william-spongberg/BouncyBalls)

  **Bouncy Balls** is a simple game inspired by the many viral short videos online of balls bouncing around the screen, and the interesting sounds and visual forms they take. The game was created using the **Unity2D** game engine in a day as a fun little project to play around with the newest version of Unity (version 6). The game is available to play online at itch.io [**here**](https://wspongberg.itch.io/bouncy-balls), and the **android** and **web** builds can be found at the linked github repo.

- **Conway's Game of Life - now in [**Haskell**](https://github.com/william-spongberg/haskell-game_of_life) and [**Prolog**](https://github.com/william-spongberg/prolog-game_of_life)!**

  In preparation for my **Declarative Programming** exam in the second half of 2024, I implemented **Conway's Game of Life** into both **Haskell** and **Prolog**. Both versions run fully in the terminal without any extra libraries. I found Haskell to be far more intuitive and easy to work with than Prolog, but I enjoyed the challenge of working with both languages and learning more about functional and logic programming, and it was especially fun to see the differences in implementation between the two languages.

### School Projects

These are projects I've completed as part of my university studies. There are other projects I've completed over the years, but these have unfortunately been lost to time (and to my poor Git practices in the past). It actually brings me great pain to look at my first couple projects and see how poor my code quality and aversion to Git was - I'm glad to see how far I've come since then.

### 2024

#### Sem 2

- [**COMP30019 - Graphics and Interaction**](https://github.com/william-spongberg/COMP30019-Project-2)

  This class was focused on creating video games and the techniques used to create them. The two main projects incremented over my groups's work using the **Unity** game engine, where we created the 3D game **Into the Abyss**. We were given a them - eeriness - and then were tasked with creating a game that fit that theme with complex shading, lighting, and interaction. I lead a team of 4 and we created a game that was well received although unfinished due to time constraints and other commitments.

  I focused on the game's shading, infinite world generation (through use of Perlin noise), post processing and particle systems, and I took great joy in developing a fun and unique game with my fellow students. I'm pretty proud that the game ended up being a bit of fun, but I am disappointed that we were unable to finish in time. My main takeaway from this project was that I need to be more assertive and take more control of the project, as I was often too passive and let the project get out of hand. It was ultimately a great learning experience for me as a team leader, and with working with Unity, HLSL, C# and game design in general.

  (I have to say using Git with Unity is a nightmare, and I wholeheartedly encourage everyone to avoid Unity at all costs for large team projects if using Git - Unity creates so many random files and changes that it is impossible to merge and resolve conflicts without a lot of manual work.)
  
  Find the trailer [**here**](https://www.youtube.com/watch?v=hN0TE6nrwNc), and an early demo of the game can be found [**here**](https://wspongberg.itch.io/into-the-abyss).

- **COMP30022 - IT Project**

  This class was focused on creating a software project from scratch, with a focus on the software development lifecycle and agile methodologies. My group, Sprout, was tasked by [**NoMoss**](https://www.nomoss.co/) to create an **app** that would allow users to track, improve and master skills through the ancient Japanese martial art concept of [**Shuhari**](https://en.wikipedia.org/wiki/Shuhari). We created the **Momentum Master** app and were well received by both our client and our subject coordinator, and were able to have the app fully functioning and ready for release by the time of the handover.

  I was tasked with helping to implement the backend for this app through a **REST API** in **Node.js** using **TypeScript** that was hosted by **Vercel**, and also helped work on the front end of the app created through **Flutter** and **Dart**. Users could enter daily logs for what they had accomplished and attach these logs to skills in order to show their progress over time. They could also find online lessons and tutorials on how to become better at their skills, and could get coaching and feedback from other users in the app.

  Unfortunately, the app is not available for download as it was a private project that we handed over to our client NoMoss and is not for commercial use, but I am happy to discuss the project and show off the app if you are interested.

- **COMP30020 - Declarative Programming**

  This class was focused on learning **Prolog** and **Haskell** and the differences between **functional** and **logic** programming. While it was initially difficult to wrap my head around the new "backwards" way of coding for Prolog and Haskell, it ended up be a really rewarding experience and opened my eyes up to how much more efficient and powerful functional programming can be. In my opinion, they are excellent if you want to code something quickly and safely, but unfortunately I don't believe they will ever become mainstream due to the difficulty it takes to read and understand the code, and the lack of libraries and support for the languages.

  The first project was to calculate the value of a hand, and select which card should be removed for the most optimal results, in **Cribbage**, an English card game. This was done entirely in Prolog, and whilst it was difficult as my first introduction to functional programming it was fun and satisfying to work through. You can find the project [**here**](https://github.com/william-spongberg/COMP30020-Project-1).

  The second project, in Haskell now, really had me scratching my head for a while. Surprisingly this was not due to its complexity, but due to how difficult it was to make the program more efficient. The task was finding all valid haikus given a list of words, with all the syllable and word handling already done for us. In fact, I thought I completed this project in only a few hours, but then when I tried the more complex test cases it was taking exponentially longer and longer to run.

  I must have ended up rewriting this program about 20 times over before I finally found a method that I was satisfied with. The main difficulty was finding where the inefficiencies were actually coming from, as Haskell doesn't have the same debugging tools as other languages, and I had to rely on print statements and my own intuition to find the problem. I ended up realising that I needed to incrementally build up the haikus and delete words from the dictionary after I was done finding all variations of them, rather than trying to find all haikus and causing a lot of redundant work. This was a great learning experience for me, and I'm glad I was able to work through it and find a solution that I was happy with. You can find the project [**here**](https://github.com/william-spongberg/COMP30020-Project-2).

#### Sem 1

- **SWEN30006 - Software Modelling and Design**

  I actually ended up really loving this subject and had a great time working with my team mates, Josh and Ethan, over the course of our two projects. My main annoyances were the restrictive and awful [**JGameGrid**](https://www.aplu.ch/classdoc/jgamegrid/ch/aplu/jgamegrid/package-summary.html) library we had to use that completely went against all of the good software design principles they had taught us and wanted us to use. I could have a whole rant about how bad this library is, but I'll save that for another time (or if you ask me about it).

  Both projects were very similar, in that they gave us a codebase and we had to fix any bugs and add a new feature to it. It was really eye-opening to see how not thinking ahead and not following good software design principles can really come back to bite you in the ass when you want to improve upon your code. In all honesty it's made me a better programmer because I'm now always thinking ahead, and thinking about how I can make it easier for myself and others in the future.

  The first project was a basic ore mining simulator that was all jammed into one "monster" class, resulting in pretty much every software design principle that you can think of being murdered with an axe. It had private inner classes, it had global vars being touched by everyone, it had high dependencies on everything around it, cohesion was awful and talk about high coupling. You can find the project [here](https://github.com/william-spongberg/COMP30006-Project-1).

  The second project was much the same, with again using **JGameGrid** (gah) and this time horrible design for the card game **LuckyThirdteen** (they made a spelling mistake and we had to keep it so their testing would still work lol). It had basically the same issues as the first project, but required more complexity due to the bots we had to add and required basically a complete rewrite to get all the new rules and features in. You can find the project [here](https://github.com/william-spongberg/COMP30006-Project-2).

- **COMP30023 - Computer Systems**



- **COMP30024 - Artificial Intelligence**

### 2023

#### Sem 2

- **SWEN20003 - Object Oriented Software Development**

- **COMP20003 - Algorithms and Data Structures**

- **INFO20003 - Database Systems**

### 2022

#### Sem 2

- **COMP10002 - Foundations of Algorithms**

#### Sem 1

- **COMP10001 - Foundations of Computing**

## Resume

Download my resume [here](William_Spongberg_Resume_2024.pdf).

## Contact

- **Email**: [william@spongberg.dev](mailto:william@spongberg.dev)
- **LinkedIn**: [linkedin.com/in/william-spongberg](https://www.linkedin.com/in/william-spongberg)
- **GitHub**: [github.com/william-spongberg](https://github.com/william-spongberg)
