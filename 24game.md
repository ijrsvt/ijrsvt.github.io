---
layout: 24solver
title: 24 Solver
order: 6
---
This is a solver for the [**24 game**](https://www.24game.com/). The premise of the game is to use addition, subtraction, multiplication and division to combine 4 numbers to reach 24. I played this game a lot as a kid in math club, and recently thought that it would be fun to programatically solve.

I initially wrote the solver in Python as it was easy to get the idea started. I wanted to access the solver anywhere and didn't feel like deploying actual infrastructure. So, I ported the code into Golang and compiled it down to WASM. The source codeis over on my [**Solver 24 GitHub**](https://github.com/ijrsvt/solver24). Happy Solving :) 