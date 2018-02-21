# Pre-requisites

Microsoft SQL Server Express 2012 (you need the SQLEXPRADV_x64_ENU.exe or 32-Bit equivalent).
Visual Studio 2015
Node Package Manager
Gulp

# Installation

* Clone the source from Bitbucket.
* Open the solution in Visual Studio running as Administrator. 
* From the Package Manager Console window in Visual Studio (or your preferred command line tool) run "npm install".
* You should now just be able to run the project in Visual Studio. The database tables will be generated automatically, but you will get a 404 if you try to access api/hospital with an HTTP GET request. You can either manually add some data to the tables or use the POST endpoint to submit data to your database. 




# Implementing Structuremap and/or AutoMapper in the solution
Both StructureMap and AutoMapper are used in this solution and the developer should take time to read the document at

http://wiki.pxl.int:8010/confluence/display/PE/Using+StructureMap+and+AutoMapper+in+the+Exemplar+API

when considering using either of these toolsets.