# MVCMovieNET

This project was built using ASP.NET 4.6. The design was to essentially replicate the MVC Movie lab, with an older framework to get an idea of how to use legacy codebases, as not every organization using .NET will be employing .NET Core.

## How to Use

In order to use this project, a user will require Visual Studio 2017. Since the requirment for the lab was not to include a deployed site, there is no live URL for a user to navigate to. Therefore, the user will have to clone the repo from this directory:

https://github.com/jaatay/MVCMovieNET

Once the repo is cloned, the user will navigate and run the program from the progam.cs file inside the solution folder. 

Note: this will initialize the program and run the DbContext migrations that come in the files. This will in turn create a local database and seed it. Therefore, if for some reason a user does not have the ability to use an SQL database with Visual Studio, they will have to fix that before running this program or an exception will be thrown during build

Once the program is built, the user will be taken to the landing page.

![Landing Page](./Landing.jpg)

