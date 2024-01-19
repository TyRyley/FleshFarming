---------------------------------------------------------------------------

-- Welcome to the README file for the flesh_farming ASP.NET Core Web App (MVC) --
		-- login details are at the end of this README file --


> Name of the app:
	- flesh_farming

> Version:
	- Version 1.0

> Background:
	- This is the prototype of the Stock management website, used to manage the stock of a group of farmers company that farms meat, named Flesh Farming.

> Build (software used):
	- Visual Studio
	- C#
	- ASP.NET Core Web App (Model-View Controller)
	- SQL Server Management Studio 19 (SSMS)

> Installation instruction:
	- unzip folder
	- place unzipped folder in repos in the C Drive of your computer
	- ensure .NET Framework is installed
	- ensure that Visual Studio is installed (2019 or newer)

> How to open app without Visual Studio:
	- open the project folder named flesh_farming
	- the end of the address in your file explorer should be ... repos > flesh_farming
	- double-click on the file called flesh_farming.sln (this will open the project in Visual Studio)\\
	- click the green start button

> Specifications:
	> Hardware requirements (minimum):
		- 1.8 Ghz 64-bit processor
		- 4GB RAM
		- Video card that supports 1366 x 768
	> Software requirements (minimum):
		- Windows 10

> Functionality added:
	- There are 3 different types of users that can make use of this website [admin, employee, farmer].
	- A logged in Admin can:
		- add categories
		- add farmers to the database.
		- view list of products.
		- filter products by specific farmer.
		- filter products by category.
		- add products to the database.
	- A logged in Employee can:
		- add farmers to the database.
		- view list of products.
		- filter products by specific farmer.
		- filter products by category.
	- A logged in Farmer can:
		- add products to the database.

> Features added:
	- Authorization:
		- Microsoft.AspNetCore.Identity is used for different user roles
	- Viewing data:
		- linq queries used to form views

> Developer Contact info:
	- contact (email) developer:
		- Tyreece Pillay: ST10084621@vcconnect.edu.za

> FAQ (questions and answers in the event that you have a problem while the program is running)

	- Q: What do I do if the program crashes while it is running?
	  A: Close the command line program, and you may re-run the program. If that does not work, close any background application while you run the program.

	- Q: What do I do if the program started, and nothing is happening?
	  A: Close the program. Open your Task Manager and check if the program appears, if it doesn't appear, then open the program again, if it does appear, right-click on it, click end task and re-run the program.

	- Q: What do I do if I am unable to type into the program?
	  A: Hold down ALT key and press the Enter key to exit a windowed view of the program and you will then be allowed to type.

> Link to GitHub Repository:
	https://github.com/VCWVL/prog7311---programming-3a---part-2-ST10084621

> Code attribution (Referencing):
	- bootswatch: https://bootswatch.com/

> connection string in appsettings.json:

"ConnectionStrings": {
    "DefaultConnection": "Server = LAPTOP-CGJO9IIR\\SQLEXPRESS; Database=FleshFarmingST10084621; Trusted_Connection = True; MultipleActiveResultSets = true"
  },
-------------------------------------------------------------------------

> Login details (NOTE: the last character for each password is a comma):

- ADMIN (SUPER USER)

email: 
admin@admin.com
password: 
Test1234,


- EMPLOYEE

email: 
employee@employee.com
password: 
Employee123,

- FARMER 1

email: 
farmer1@farmer.com
password: 
Farmer123,

- FARMER 2

email: 
farmer2@farmer.com
password: 
Farmer123,

---------------------------------------------------------------------------