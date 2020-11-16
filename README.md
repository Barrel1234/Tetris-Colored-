# Tetris-Colored-
Tetris Game made with SFML and C++.

Tetris game is an arcade game in which the objective is to merge the shapes failling from above to completa a line below.

------------------------INSTRUCTIONS------------------------------------

1. Download and Install SFML 32 bit only.

2. With Visual Studio community edition 2017 or higher create a new c++ console application.

3. Create a new folder named SFML inside the project.

4.Copy and paste bin,lib and include folder  inside that SFML folder from the installed SFML.

5.Inside Visual Studio,under project properties select configuration ALL Configuration and platform Win 32.

6.Inside Linker options under the additional Library Directories browse and  provide the path of the lib folder in SFML.

7.Inside  input options under Additional Dependencies provide these values 

sfml-system-d.lib

sfml-graphics-d.lib

sfml-audio-d.lib

sfml-network-d.lib

sfml-window-d.lib

8. Inside C/C++ options under additional include browse and provide the path of the the include folder.

9.Select Configuration back to release,Click on Apply and Ok.

10.Start Local Windows Debugger..wait for a few moments and in your project directory a debug folder will be created.

11. Inside the Debug Folder copy and paste the the open32.dll and all the d-2.dll files from the bin folder of SFML.

12.copy and paste the Tetris Colored.cpp inside the editor.

13.copy and paste the images folder inside the second folder of the Tetris Colored folder.

14.Inside the editor start Local Windows Debugger for the final time..Play and Enjoy the Game.

15.Thank you.



