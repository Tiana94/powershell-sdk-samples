Runspace Sample 07
==========================
     This sample shows how to create a runspace and how to run 
     commands using a PowerShell object. It builds a pipeline 
     that runs the get-process cmdlet, which is piped to the measure-object 
     cmdlet to count the number of processes running on the system.

     For Windows PowerShell information on MSDN, 
     see http://go.microsoft.com/fwlink/?LinkID=178145 


Sample Language Implementations
===============================
     This sample is available in the following language implementations:
     - C#


To build the sample using Visual Studio:
=======================================
     1. Open Windows Explorer and navigate to Runspace07 under the samples directory.
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

     1. Creating a runspace using the RunspaceFactory class.
     2. Creating a PowerShell object
     3. Adding individual cmdlets to the PowerShell object.
     4. Running the cmdlets synchronously.
     5. Working with PSObject objects to extract properties 
        from the objects returned by the cmdlets.

