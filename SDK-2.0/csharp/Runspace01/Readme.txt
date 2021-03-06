Runspace Sample 01
==========================
     This sample uses the PowerShell class to run the 
     Get-Process cmdlet synchronously. The Name and
     HandleCount are then extracted from the objects 
     returned by the cmdlet and then displayed.

     For Windows PowerShell information on MSDN, 
     see http://go.microsoft.com/fwlink/?LinkID=178145 


Sample Language Implementations
===============================
     This sample is available in the following language implementations:

     - C#

To build the sample using Visual Studio:
=======================================
     1. Open Windows Explorer and navigate to Runspace01 under the samples directory.
     2. Double-click the icon for the .sln (solution) file to open the file in Visual Studio.
     3. In the Build menu, select Build Solution.
     The library will be built in the default \bin or \bin\Debug directory.

To run the sample:
=================
     1. Start a command prompt.
     2. Navigate to the folder containing the sample executable.
     3. Run the executable.

Demonstrates
============
     This sample demonstrates the following:

     1. Creating a PowerShell object to run a command.
     2. Adding a command to the pipeline of the PowerShell object.
     3. Running the command synchronously.
     4. Using PSObject objects to extract properties from the objects
        returned by the command.

