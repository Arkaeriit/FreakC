<div align="center">
  <img src="Resources/Branding/logo.png" />
  <br/>
  <b>Make Batch Programming Funny</b>
  <br/>
  <br/>
  <a href="https://github.com/nguyenphuminh/FreakC/blob/master/LICENSE.md"><img src="https://img.shields.io/badge/license-MIT-blue.svg"/></a>
</div>

## What is FreakC ?
FreakC is an esoteric programming language that... has nothing to do with the C programming language. This programming language's syntax is dirty and funny, but it can actually make many decent programs.

## What is in the devkit ?
<li>A FreakC compiler</li>
<li>A FreakC terminal</li>
<li>Some optional utilities</li>

## Compiler's usage
In the "FreakC" folder, open cmd and type this command to compile and run the code:

    freakc "file.fclang"
    
Example:
    
    freakc "Examples/HelloWorld.fclang"
 
If you want to compile the code only, type:

    freakc "file.fclang" --compile

<b>The compiler only works on Windows, and can only be compiled to Batch.</b>

## Tutorials 
<a href=https://github.com/nguyenphuminh/FreakC/blob/master/TUTORIAL.md>Click here to see tutorials</a>

## Samples
<a href=https://github.com/nguyenphuminh/FreakC/tree/master/Examples>Click here to see samples</a>

## Convert FreakC to .EXE files
In "FreakC/Utilities/Scripts" there is a file called battoexe.bat which helps to convert .bat files to .exe files.

So to convert FreakC to .EXE files, you need to compile FreakC codes to Batch, and then convert the Batch file generated by simply dragging that Batch file onto battoexe.bat.

You can actually find plenty of other tools online that helps you to converts Batch files to EXE files.

## Compile in Sublime:
In "FreakC/Utilities/Scripts" there is a file called "FreakC.sublime-build" which is the Sublime Text's build system for FreakC. To use it, please paste it in the "C:\Users\admin\AppData\Roaming\Sublime Text 3\Packages\User" or wherever your Packages folder is. Then, make sure that you have setted the environment variable for FreakC. After that, you will be able to compiles FreakC codes in Sublime Text.

## Frameworks
There are many frameworks in the utilities folder that you can use, I will definitely update the usage of them soon.

## 3.x Releases
All the 3.x releases have the compiler rebuilt completely different from the 0.x, 1.x versions. It is now fast and versatile, with much more power and ability to make some standard programs. Compare to the 2.x releases, there are not much differences, but the 3.x releases removes all the troll commands. Why is that? Well, it's simply because we can't find any use for them, and they also slow the compiler down, and make the compiler 2 times heavier, so removing them is 100% required. Also, the 3.x releases added if statements, and the ability to write Batch codes in FreakC, so HackerMan[fnc] is removed as well.

## Developers
<li>Owner/Developer: Nguyen Phu Minh</li>

## Copyrights and License
Copyright © 2020 Nguyen Phu Minh

This language is licensed under the MIT License
