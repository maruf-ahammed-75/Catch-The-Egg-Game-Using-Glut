```markdown
# Egg Catcher (GLUT)

Small, easy egg-catching game in C using OpenGL/GLUT.

Quick start
- Build: gcc egg_game.c -o egg_game -lGL -lGLU -lglut -lm
- Run: ./egg_game

Goal
- Move the basket and catch eggs dropped by a moving chicken.
- Gold = +10, Blue = +5, Normal = +1, Poop = -10.

Controls
- Mouse: move basket horizontally
- A / D or ← / → : move basket left/right
- S: Start / Restart
- P: Pause / Resume
- Q or ESC: Quit

Notes
- 60s play time by default.
- Chicken and egg speeds increase at 15s, 30s, 45s.
- High score saved to highscore.dat in the program folder.

That's it — short and ready to use.
```
