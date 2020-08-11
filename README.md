<div align="center">
  <img src="Resources/Branding/logo.png" />
  <br/>
  <b>The FreakC Programming Language</b>
  <br/>
  <br/>
  <a href="https://github.com/nguyenphuminh/FreakC/blob/master/LICENSE.md"><img src="https://img.shields.io/badge/license-MIT-blue.svg"/></a>
</div>

## What is FreakC ?
FreakC is an esoteric programming language that... has nothing to do with the C programming language. This programming language can not do anything useful, it is created to be a joke for fun.

## Compiler's usage
In ./FreakC (or ./FreakC/Source) open cmd and type this command:

    freakc "file path(don't include .fclang)"
    
Example:
    
    freakc "Examples/HelloWorld"
 
 Then, run the Batch file that has been generated to run the compiled code.

<li><b>The compiler only works on Windows, and can only be compiled to Batch.</b></li>

## Commands
<b><u>All necessary commands:</u></b>

<b>Functions that uses string:</b>
<li>HelloWorld[str] - Print out "Hello, World!"</li>
<li>GrabMeADrink[str] - Print out "Grab me a drink"</li>
<li>ILoveYou[str] - Print out "I love you!"</li>
<br/>
<b>Functions that uses integer:</b>
<br/>
<li>RandomNumMinimum[int] - Print out a random number from 0 to 99</li>
<li>RandomNumShort[int] - Print out a random number from 0 to 999</li>
<li>RandomNum[int] - Print out a random number from 0 to 99999</li>
<br/>
<b>Additional functions:</b>
<br/>
<li>Loop[fnc] - Loop the program endlessly</li>
<li>Sleep[fnc] - Timeout for a random time from 0 to 9 second(s)</li>
<li>ShutdownSystem[fnc] - Shutdown system</li>
<li>RestartSystem[fnc] - Restart system</li>
<li>EnterMatrix[fnc] - Printing out random numbers to make you feel like a hacker :)</li>
<li>EnterMatrixHacker[fnc] - Like the previous but has green color :)</li>

<br/>
<b>Comments</b>

Because FreakC compiles to Batch, you can comments in FreakC just like in Batch using:

    REM This is a comment in FreakC and Batch
    ::This is also a comment in FreakC and Batch

<b>Actually the informations above is not quite true because you can just comments by typing normal text :)</b>
<br/>
Note: After FreakC is compiled to Batch, all the comments will be removed in the generated Batch file.

## Convert FreakC to .EXE files
In "FreakC/Utilities/Scripts" there is a file called battoexe.bat which helps to convert .bat files to .exe files.

So to convert FreakC to .EXE files, you need to compile FreakC codes to Batch, and then convert the Batch file generated by simply dragging that Batch file onto battoexe.bat.

You can actually find plenty of other tools online that helps you to converts Batch files to EXE files.
    
## What is in the devkit ?
<li>A FreakC compiler</li>
<li>A FreakC terminal</li>
<li>Some optional utilities</li>
    
## 1.x Releases
All the 1.x releases have the compiler rebuilt completely different from all the 0.x version. It is now fast and versatile.

## Developers
<li>Lead Developer: Nguyen Phu Minh</li>

## Copyrights and License
Copyright © 2020 Nguyen Phu Minh

This language is licensed under the MIT License
