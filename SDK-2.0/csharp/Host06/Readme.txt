Host Sample 06
==========================
     This examples shows building a fairly complete interactive
     console-based host. This sample reads commands from the
     command line, executes them and displays the results to
     the console.

     For Windows PowerShell information on MSDN, 
     see http://go.microsoft.com/fwlink/?LinkID=178145 


Sample Language Implementations
===============================
     This sample is available in the following language implementations:

     - C#


To build the sample using Visual Studio:
=======================================
     1. Open Windows Explorer and navigate to Host06 under the samples directory.
     2. Double-click the icon for the .sln (solution) file to open the file in Visual Studio.
     3. In the Build menu, select Build Solution.
     The library will be built in the default \bin or \bin\Debug directory.


To run the sample:
=================
     1. Start command prompt.
     2. Navigate to the folder containing the sample executable.
     3. Run the executable

Demonstrates
============
     This sample demonstrates the following:

     1. Creating your own host interface, host user interface and
        host raw user interface classes.
     2. Building a console application that uses these host
        classes to build an interactive PowerShell shell.
     3. How to create the $profile variable and load the four
        different profiles:
            * current user, current host
            * current user, all hosts
            * all users, current host
            * all users, all hosts
     4. Implement the IHostUISupportsMultipleChoiceSelection
        interface.
     5. Implement the IHostSupportsInteractiveSession interface
        to support interactive remoting via the Enter-PSSession
        and Exit-PSSession cmdlets.
     6. Use the PSParser.Tokenize API to colorize the command line
        as it is typed.
