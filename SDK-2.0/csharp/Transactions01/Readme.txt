TransactedComment sample
==========================
     This sample shows a set of cmdlets that participate in Windows PowerShell 
     transactions. These cmdlets provide a comment log that can be changed, 
     and completed or rolled back along with the rest of the transaction. 
     It also provides a simple transactional resource manager that stores a string.

     For Windows PowerShell information on MSDN, 
     see http://go.microsoft.com/fwlink/?LinkID=178145 


Sample Language Implementations
===============================
     This sample is available in the following language implementations:

     - C#


To build the sample using Visual Studio:
=======================================
     1. Open Windows Explorer and navigate to TransactedCommentSample under the samples directory.
     2. Double-click the icon for the .sln (solution) file to open the file in Visual Studio.
     3. In the Build menu, select Build Solution.
     The library will be built in the default \bin or \bin\Debug directory.


To run the sample:
=================
     1. Open PowerShell
     2. Run Import-Module <full path to the sample dll>
     

Example use case:
================
     1. Start-Transaction
     2. Add-TransactedComment -UseTransaction "Hello World!"
     3. Get-TransactedComment
     4. Get-TransactedComment -UseTransaction
     5. Complete-Transaction
     6. Get-TransactedComment


Demonstrates
============
     This sample demonstrates the following:
     1. Usage of SupportsTransactionsAttribute
     2. Usage of CurrentPSTransaction
     3. Implementation of a .NET transacted resource manager.


