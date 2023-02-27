# PomodoroTimer
A cute Pomodoro timer widget for windows.

WARNING: This application is not ready to be used, it is feature complete, but consists of sveral bugs that make it completely impractical to use.
Please feel free to explore if you are the unity project directory on my page to explore more and fix bugs (the bugs relate to the Windows API)

When run, it opens a transparent fullscreen window that interacts with the windows API to allow full functionality of the rest of your desktop,
while displaying a small widget in the top right corner.

Pomodoro functionality:
-Set work and break intervals.
-Set the number of desired repetition.
-Pause/unpause timer.
-Reset the whole timer.
-Add repeats and change interval times at any point.

the transparent widget, is non intrusive yet still visible.

BUGS
-8% CPU usage from windows manager
-Hidden task bars misbehave while app is in use
-Secondary desktops in windows 11 become blurred and remain blurred even after the app is closed

Currently, the widget causes the windows manager to consume a lot of CPU cycles, this is caused because the application is constantly checking if the mouse is
interacting with a visible portion of the widget. This could be solved by introducing a more sophisticated version for checking this interaction.
eg. check for interaction only on collision enter with a small bounding box.
