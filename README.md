# Gradient-Descent-Demo
## Learning Rate in 3D

An interactive 3D demo that shows what happens when a machine learning model learns with a step size that is too small, just right, a little too big, or far too big.

## What it does

A ball rolls down a bowl-shaped surface toward its lowest point. The lowest point is the best answer the model is looking for, and the height of the surface is how wrong the model currently is.

The only thing you change is the **learning rate**, which is the size of each step the ball takes. You can pick one of four presets or drag the slider to try any value:

- **Too small:** the ball barely moves and takes forever to get anywhere.
- **Smooth:** the ball glides down and settles at the bottom.
- **Overshoot:** the ball jumps past the bottom and bounces between the walls, but it still gets there, and in this demo it gets there faster than the smooth run.
- **Diverge:** each jump lands higher than the last, and the model gets worse instead of better.

You can drag to rotate the surface and scroll to zoom. A small plot in the corner tracks how the error changes at each step.

## Why it matters

The learning rate is one of the most important settings when training a model, and one of the easiest to get wrong. Too low wastes time. Too high ruins the training run. Reading about this is one thing, but watching it happen makes the idea much easier to remember.

The demo also shows something that often surprises people: overshooting is not automatically bad. A learning rate that is a little aggressive can train faster than a cautious one, as long as it stays below the point where training falls apart.

## How to use it

Download `learning-rate-3d.html` and open it in any modern web browser. It needs an internet connection the first time so it can load its 3D library.

## Notes

- This is a simple, clean example. Real models are much messier, so treat it as a way to build intuition rather than a precise picture of real training.
- This project was built with Claude, an AI assistant made by Anthropic. I described what I wanted and guided the design, and Claude wrote the code.
[Learning rate overshooting and undershooting visualization - Claude.html](https://github.com/user-attachments/files/33862533/Learning.rate.overshooting.and.undershooting.visualization.-.Claude.html)
