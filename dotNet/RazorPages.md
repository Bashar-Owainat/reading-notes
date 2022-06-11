# Razor pages

## What are Razor pages?
Razor Pages is a modern, simpler online application development model that, by using a file-based routing strategy, eliminates most of the ceremony of ASP.NET MVC. Each Razor Pages file in the Pages directory corresponds to an endpoint.

## Give an advantage for using Razor Pages.
Razor Pages can make it easier and more productive to code page-focused scenarios than controllers and views.

## Describe the App structure for Razor Pages.
The application structure is similar to MVC, however there are no controller and view folders. The Pages folder contains all Razor views that are referred to as "pages" in this context. These pages are similar to standard MVC views, but they additionally contain code that is normally stored in controller classes in MVC.

## What happens when sending a request in Razor Pages?
The default ASP.NET Routing configuration will look in the Pages folder for a Razor Page for that request. It searches for a page with the name specified in the request.

## What are the types of Razor Syntax?
There are two types of Razor syntax: 
-	Single statement block (It starts with @) it is utilized when you only want to interact with a single line of code from the MVC view page.
-	Multi statement block (must be written between @ {.……} )  using this type you can define more than one line of code statements and do processes.

