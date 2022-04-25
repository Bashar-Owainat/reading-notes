# swaggerAndTestConrollers

I write what I read in a quiz form

## what is swagger?
It's a language-agnostic standard for representing REST APIs. It enables both machines and people to comprehend a REST API's capabilities without having direct access to the source code.

## what is OpenApi?
It's a document that outlines your API's capabilities. The XML and attribute annotations within the controllers and models are used to create the document.

## why do we use swagger?
-	Reduce the amount of time and effort required to connect disconnected services.
-	Reduce the amount of time it takes to document a service correctly.

## what is the difference between OpenApi and Swagger?
OpenApi is a specification while Swagger is tooling that uses OpenApi specification .

## what is unit testing?
It's a way of logically isolating the smallest bit of code in a system and testing it.
## why do we need to test controllers?
since they are essential in any ASP.NET Core MVC application we have to make sure that they behave as intended.

## when testing controllers what should be focused on and what should be avoid?
When we test controllers we test its actions and behavior and we avoid routing, filter and model binding.

