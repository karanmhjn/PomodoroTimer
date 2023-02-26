# PomodoroTimer
A cute Pomodoro timer widget for windows.

When run, it opens a transparent fullscreen window that interacts with the windows API to allow full functionality of the rest of your desktop,
while displaying a small widget in the top right corner.

Pomodoro functionality:
-Set work and break intervals.
-Set the number of desired repetition.
-Pause/unpause timer.
-Reset the whole timer.
-Add repeats and change interval times at any point.

the transparent widget, is non intrusive yet still visible.

Currently, the widget causes the windows manager to consume a lot of CPU cycles, this is caused because the application is constantly checking if the mouse is
interacting with a visible portion of the widget. This could be solved by introducing a more sophisticated version for checking this interaction.
eg. check for interaction only on collision enter with a small bounding box.
