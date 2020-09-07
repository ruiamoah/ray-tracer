# ray-tracer
## Ray Tracer using C/C++
The system handles
the rendering of ellipsoids, with a fixed camera situated at the origin in a right handed coordinate
system, looking down the negative z-axis. Local illumination, reflections, and shadows included.
The program takes a single argument, which is the name of the file to be parsed. For example:
> raytracer.exe testCase1.txt

HOW TO RUN RAYTRACER

1) POWERSHELL
    Open powershell and then in Release is where the exe is then to run 
    you go .\raytracer.exe then in the next line you enter the text file
    then open ppm file with GIMP or any program that can open it

PS C:\Users\Rui_A> cd .\Desktop\
PS C:\Users\Rui_A\Desktop> cd .\Release\
PS C:\Users\Rui_A\Desktop\Release> .\raytracer.exe
testParsing.txt
Saving image testParsing.ppm: 600 x 600
PS C:\Users\Rui_A\Desktop\Release>

2) FILE EXPLORER
    You can run the exe by clicking the exe then enter text file
    
Reflection Example

<img src = "keyReflection.png" width = "300">

Shadow Example

<img src = "keyShadow.png" width = "300">

Global Illumination

<img src = "keySample.png" width = "300">
